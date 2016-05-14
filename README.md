![pic](./conda.png)

# conda

Read about it here : [http://conda.pydata.org/docs/](http://conda.pydata.org/docs/) and checkout [bioconda](https://bioconda.github.io/)

## my collection of conda builds 

Stuff I like and use and not up on [bioconda](https://bioconda.github.io/) yet. 

| Package |Url |install|
|:---|---:|---:|
|glia|[https://anaconda.org/sjnewhouse/glia](https://anaconda.org/sjnewhouse/glia)|`conda install -c sjnewhouse glia=9049ffc`|
|    |[recipe](https://github.com/snewhouse/conda/tree/master/recipes/glia)||
|nextflow|[https://anaconda.org/sjnewhouse/nextflow](https://anaconda.org/sjnewhouse/nextflow)|`conda install -c sjnewhouse nextflow=0.18.3`|
|    |[recipe](https://github.com/snewhouse/conda/tree/master/recipes/nextflow)||



***

Notes:
bioconda's removal of zlib from build process has made it "less" smooth with builds that require zlib
