The notebook works with Clipper release 0.2

### Dependencies

* Install [Docker](https://docs.docker.com/engine/installation/)
* Install Python: currently Clipper supports Python 2 only
* Create an Anaconda environment. One straightforward way is to first install
[conda](https://conda.io/docs/user-guide/install/index.html), and then create the
 environment by running `conda create -n ml-serve python=2.x anaconda`,
where `ml-serve` is the name of our Anaconda environment
* Activate the environment: `source activate ml-serve`
* Install Clipper within the environment: 
`pip install git+https://github.com/ucbrise/clipper.git@develop#subdirectory=clipper_admin`
