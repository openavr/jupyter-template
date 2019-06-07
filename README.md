Jupyter Notebook Project Setup Template
=======================================

Jupyter Installation
--------------------

Install `python` `venv`:

    $ sudo apt install python3-venv

Create a virtual environment:

    $ python3 -m venv $PWD/venv

Activate the virtual environment:

    $ source venv/bin/activate

Install `Jupyter`:

    $ pip install --upgrade pip
    $ pip install -r requirements.txt

Start `Jupyter`:

    $ jupyter notebook

or to avoid automatically loading `Jupyter` in a broswer:

    $ jupyter notebook --no-browser
