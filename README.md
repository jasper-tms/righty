### Python code for the "righty" GridTape-TEM dataset

Install this package into your python environment directly from GitHub using pip:

    pip install git+https://github.com/jasper-tms/righty

Then launch python and get started by looking at the dataset's description:

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
    
