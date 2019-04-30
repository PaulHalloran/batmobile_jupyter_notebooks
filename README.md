# batmobile_jupyter_notebooks

remote lon in:

ssh groupserv

jupyter lab --no-browser --port=8888

in second window ssh -Y -N -L localhost:8888:localhost:8888 groupserv

then in local browser:
http://localhost:888
