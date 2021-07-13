# Jupyter Napari Desktop
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Fifourche/omero-analysis-desktop.git/HEAD?filepath=napari.ipynb)


Run [Napari](http://napari.org/) in a Linux desktop using Jupyter.

This is based on https://github.com/ryanlovett/nbnovnc

Either [run on mybinder.org](https://mybinder.org/v2/gh/ome/omero-analysis-desktop/master) or build locally with [repo2docker](https://repo2docker.readthedocs.io/):

To build locally:

 * Install [Docker](https://www.docker.com/) if required.
 * Create a virtual environment and install repo2docker from PyPI.
 * Clone this repository.
 * Run  ``repo2docker``. 
 * Depending on the permissions, you might have to run the command as an admin.

```
pip install jupyter-repo2docker
git clone https://github.com/ome/omero-analysis-desktop.git
cd omero-analysis-desktop
repo2docker .
```

Open the displayed URL, then go to `/desktop` in the menu option on the right-hand side.

Use napari
==========

Once the desktop is open go back to the main Jupyter Notebook window, open `napari.ipynb` and execute the cells one at a time. You should see Napari open in the desktop window.
