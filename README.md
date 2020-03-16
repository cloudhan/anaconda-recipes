# Memorandum

## build package

Install `conda-build` to work with recipies, e.g.
```
conda install conda-build
conda build <recipe_dir>
```

Refer to https://docs.conda.io/projects/conda-build/en/latest/resources/index.html for writing recipies.

## work with anaconda

```
conda install anaconda-client
anaconda login
anaconda update <path_to_built_pkg> # will should in conda build log
```

Refer to https://docs.anaconda.com/anaconda-cloud/user-guide/tasks/work-with-packages/#uploading-packages for more details.
