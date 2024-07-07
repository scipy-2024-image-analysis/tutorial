# Part 0.2: Launching the Jupyter notebooks

The materials on this website are actually the tutorial notebooks. We encourage you
to follow along with the workshop in a fresh, blank notebook. However, if you
would like to be able to run the completed notebooks locally, you can use the instructions below.

If you cloned the workshop repository, then you already have the notebooks in the `tutorial` subfolder.
If you have not then you can download the notebooks as follows:

### Cloning via git
To clone the repository containing the tutorial materials to your computer, open
your command line and navigate to the folder where you will download the course
materials into. Then, clone the repository. This will download all of the files necessary for
this tutorial.

 ```bash
 git clone https://github.com/scipy-2024-image-analysis/tutorial
 ```

### Downloading a .zip file
To download the notebooks as a .zip file using this link:  
https://github.com/scipy-2024-image-analysis/tutorial/archive/refs/heads/main.zip 
Then, using your file browser, navigate to the downloaded file, unzip it (optionally to 
a different location on your computer), and navigate to the contents of the folder `scipy-2024-image-analysis`.


## Launch the `jupyter lab` application

Navigate to the `tutorial` subdirectory of the
`tutorial` directory you just cloned or downloaded.

```
cd <path to repository>/tutorial
```

Remember to activate the `image-analysis-24` conda environment if you haven't already.

```bash
conda activate image-analysis-24
```

To start the Jupyter application, enter:

```bash
jupyter lab
```

The Jupyter interface will open in a browser window and you will see the notebooks
in the file browser on the left.

````{important}
The notebooks were converted to MyST Markdown files (with a .md extension), to better visualize 
on GitHub and provide a nice rendered look on the web. To open these workshop notebooks in the 
Jupyter interface you will need [`jupytext`](https://jupytext.readthedocs.io/en/latest/index.html) 
in the environment, which was installed as part of `image-analysis-24`. Then, right click 
the notebook name in the file navigation panel from the Jupyter interface, and click "Open with -> Notebook".

Or, as an alternative you can first convert them to normal `.ipynb` using `jupytext` from the command prompt:

```bash
jupytext –to ipynb <notebook_file>.md
```

````
