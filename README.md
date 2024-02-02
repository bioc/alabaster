# Umbrella for easy installation

|Environment|Status|
|---|---|
|[BioC-release](https://bioconductor.org/packages/release/bioc/html/alabaster.html)|[![Release OK](https://bioconductor.org/shields/build/release/bioc/alabaster.svg)](http://bioconductor.org/checkResults/release/bioc-LATEST/alabaster/)|
|[BioC-devel](https://bioconductor.org/packages/devel/bioc/html/alabaster.html)|[![Devel OK](https://bioconductor.org/shields/build/devel/bioc/alabaster.svg)](http://bioconductor.org/checkResults/devel/bioc-LATEST/alabaster/)|

This is an umbrella package that enables easy installation of all packages in the [**alabaster**](https://github.com/ArtifactDB/alabaster.base) framework.
It allows users to pull down all relevant packages with a single `BiocManager::install()` call, allowing them to (un)serialize every known resource.
Of course, the flipside is that the R installation may now contain a lot of transitive dependencies that are not really necessary.
Advanced users or developers may prefer to install individual _alabaster_ packages based on their use cases.
