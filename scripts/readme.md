### Setup Instructions

Using Anaconda

```
$ conda create -n tmpsf matplotlib xz thredds_crawler requests xarray netcdf4 ipykernel
```

To add the `tmpsf` environment to jupyter as a selectable kernel

```
$ python -m ipykernel install --user --name tmpsf

```