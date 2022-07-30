### Python code for the "righty" GridTape-TEM dataset

#### Installation
Install this package into your python environment directly from GitHub using pip:

    pip install git+https://github.com/jasper-tms/righty
    
To then later pull updates from github, use:

    pip install --force-reinstall git+https://github.com/jasper-tms/righty

#### Get started
Launch python, import this package, and get started by looking at the dataset's description:

    import righty
    print(righty.info.dataset_description)

See what other information is available:

    print(righty.info.descriptions)
    # Or if you want to print these descriptions formatted nicely:
    import json
    print(json.dumps(righty.info.descriptions, indent=2))
    
Then access the info you are interested in, e.g.:

    voxel_size = righty.info.voxel_size
    shape = righty.info.shape
    
