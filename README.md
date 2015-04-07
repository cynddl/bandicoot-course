# bandicoot-course
Slides and ipython notebooks for the mobile phone data analysis course



## Random useful commands

Launching _IPython notebook_ remotely:

    # Server
    ipython2 notebook --no-browser --port=8889

    # Client
    ssh -N -f -L localhost:8889:localhost:8889 {user}@{netmob-server}

Connecting to _RStudio_ remotely:

	# Client
	# Ask to get rstudio-server started (need root user)

	# Client
	ssh -N -L 8787:localhost:8787 {user}@{netmob-server}