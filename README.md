<div>
<img src="http://omarwagih.github.io/gitter/images/sample.jpg" width=350/>
<img src="http://omarwagih.github.io/gitter/images/gridded_sample.jpg" width=350 style="display:inline"/>
</div>

# gitter: An R Package for Quantification of Pinned Microbial Cultures


gitter allows robust and quick quantification of pinned colony sizes in plate images. gitter works by first finding the grid of colonies from a preprocessed image and then locating the bounds of each colony separately. It includes several image pre-processing techniques, such as autorotation of plates, noise removal, contrast adjustment and image resizing.

**Please refer to [http://omarwagih.github.io/gitter/](http://omarwagih.github.io/gitter/) for installation instructions, example code and documentation**

For github installation:

```
devtools::install_github('omarwagih/gitter')
```

Note: The package `PET` which is a dependency of gitter has been removed from CRAN so the auto-install may fail. To get around this, you can try manually installing `PET` from the [CRAN Archives](https://cran.r-project.org/src/contrib/Archive/PET/) before trying to install gitter i.e.:

download [`PET_0.5.1.tar.gz`](https://cran.r-project.org/src/contrib/Archive/PET/PET_0.5.1.tar.gz) from the Archives, then run the following in your command line:

```
R CMD INSTALL PET_0.5.1.tar.gz
```


<small>
If you use gitter, please cite the following work: <br>
<i>Wagih, O. and Parts L. (2014) gitter: a robust and accurate method for quantification of colony sizes from plate images. G3 (Bethesda) pii: g3.113.009431v1</i> <a href="http://www.ncbi.nlm.nih.gov/pubmed/24474170">pubmed</a>
</small>
