# Livestock detection (DeepForest)

<p align="center">
    <a href="https://github.com/eds-book/95199651-9e81-4cae-a3a7-66398a9a5f62/actions/workflows/nightly-build.yaml/badge.svg">
        <img alt="Continuous integration badge" src="https://github.com/eds-book/95199651-9e81-4cae-a3a7-66398a9a5f62/actions/workflows/nightly-build.yaml/badge.svg">
    </a>
    <a href="http://mybinder.org/v2/gh/eds-book-gallery/95199651-9e81-4cae-a3a7-66398a9a5f62/main?labpath=notebook.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://zenodo.org/badge/latestdoi/880931043">
        <img alt="doi" src="https://zenodo.org/badge/880931043.svg">
    </a>
    <br/>
</p>

<p align="center">
<img src="images/thumbnail.png" alt="thumbnail" width="500"/>
</p>

## How to run

### Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

### Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/eds-book-gallery/95199651-9e81-4cae-a3a7-66398a9a5f62.git
    ```

4. Move into the cloned repository
    ```bash
    cd 95199651-9e81-4cae-a3a7-66398a9a5f62
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate 95199651-9e81-4cae-a3a7-66398a9a5f62
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

## Troubleshooting

Following the guidelines in <a href="https://deepforest.readthedocs.io/en/v1.4.1/getting_started/install.html#geopandas-errors/">DeepForest documentation</a>, for Mac M1 and M2 users, you may need to install the `geopandas` package via conda after the step 5. You can do this by running the following command:

```bash
conda install -c conda-forge geopandas
```
</div>