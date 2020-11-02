## Getting started with Python and Jupyter Notebook

The assignments have to be programmed in Python 3 and handed in as a Jupyter notebook.
This notebook contains your code, the output, and any explanation or interpretation that is required.

You can use a notebook from the start, but you can also write your python code separately first (you may find this easier for testing) and then put it in a notebook later.

---

### Software requirements

- Python 3
- [Jupyter Notebook](http://jupyter.org/install)

If you don't yet have Python 3 on your computer, the easiest way to install everything is [Anaconda](https://www.anaconda.com/download/) (choose the latest Python version).
This includes Jupyter as well as any additional libraries you may need.
If you already have Python 3 installed, you can also install Jupyter manually using pip:

    python3 -m pip install --upgrade pip
    python3 -m pip install jupyter 

*Tip: If you really can't get things to work on your own computer, there are also ways to work with Jupyter in the cloud, such as [Google's Colab](https://colab.research.google.com/).*

---

### Running Jupyter

In a terminal (Linux/Mac) or command prompt (Windows) run:

    jupyter notebook

This opens a browser tab showing the Jupyter dashboard.

---

### Creating a notebook
Navigate to the desired folder in the Jupyter dashboard and click `New` -> `Python 3`. This will open a new empty notebook.

*Tip: Once you're in a notebook, click on `Help` in the menu bar for a tour of the user interface and further documentation.*

---

### Saving a notebook as PDF
With the notebook open, click `File` -> `Download as` -> `PDF`.

*Tip: Behind the scenes, Jupyter uses LaTeX to generate the PDF. If you run into errors, you can also click `File` -> `Print Preview` and save the result as a PDF.*

---

### Plotting data
You are free to choose how you create the plots in your reports.
A good option is [matplotlib](https://matplotlib.org/).
There is a nice tutorial [here](http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb).

---

### Homework submission
- Hand in your notebook file (ends in `.ipynb`) as well as a PDF version of the notebook.
- Put your name and student number at the top of your report *and* in the file name.
- Explain what your code does (or is supposed to do).
- Give clear labels to the axes of plots and the columns of tables.
- If you've made any changes or additions to the provided code, include them in your report.
