# Umbrella for easy installation

This is an umbrella package that enables easy installation of all packages in the **alabaster** framework.
It allows users to pull down all relevant packages with a single `BiocManager::install()` call, allowing them to (un)serialize every known resource.
Of course, the flipside is that the R installation may now contain a lot of transitive dependencies that are not really necessary.
Advanced users or developers may prefer to install individual _alabaster_ packages based on their use cases.
