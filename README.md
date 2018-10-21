# minimal docker setup for SCIP and Julia

For testing Julia packages that rely on [SCIP](http://scip.zib.de/). Useful primarily for [SCIP.jl](https://github.com/SCIP-Interfaces/SCIP.j), forked from [texlive-julia-minimal-docker](https://github.com/tpapp/texlive-julia-minimal-docker).

Steps to upload a new image after making changes:

    docker build -t leethargo/scip-julia .
    docker login -u leethargo
    # enter password
    docker push leethargo/scip-julia

