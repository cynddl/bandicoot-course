# bandicoot-course
Slides and ipython notebooks for the mobile phone data analysis course



## Random useful commands

Launching _IPython notebook_ remotely:

    # Server
    ipython2 notebook --no-browser --port=8889

    # Client
    ssh -N -f -L localhost:8889:localhost:8889 {user}@{d4d-server}