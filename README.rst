.. image:: https://img.shields.io/badge/python-3.6+-blue.svg
        :target: https://www.python.org/downloads/release/python-360/

.. image:: https://img.shields.io/github/license/mashape/apistatus.svg
        :target: https://github.com/nivlab/NivLink/blob/master/LICENSE
        
.. image:: https://zenodo.org/badge/182183266.svg
   :target: https://zenodo.org/badge/latestdoi/182183266

NivTurk-Shiyi-modified
=======
This is the modified verision of nivturk. 
You use the .yml file to set up your virtual environment (cloned from my desktop).

Niv lab tools for securely serving and storing data from online computational psychiatry experiments.

Configuring environment
^^^^^^^^^^^^^
**Use the following link to configure environment manually**
[the link of conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

**Or use the shiyienvironment.yml file to clone my environment and follow this guidance:**
[Use the terminal or an Anaconda Prompt for the following steps:](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#id2)

1. Create the environment from the environment.yml file:
2. conda env create -f environment.yml
3. The first line of the yml file sets the new environment's name. For details see Creating an environment file manually.
4. Activate the new environment: conda activate myenv
5. Verify that the new environment was installed correctly:
6. conda env list

**Next, enter code below to install dependencies:**
cd nivturk
pip install -r requirements.txt

"command cd means find location, so substitude nivturk with the file location of your downloaded nivturk folder"

Documentation
^^^^^^^^^^^^^

For details on how to serve your experiment, how the code is organized, and how data is stored, please see the
`Documentation <https://nivlab.github.io/nivturk>`_.

Citation
^^^^^^^^

If you use this library in academic work, please cite the following:

  | Samuel Zorowitz & Daniel Bennett. (2022). NivTurk (v1.2-prolific). Zenodo. https://doi.org/10.5281/zenodo.6609218

Acknowledgements
^^^^^^^^^^^^^^^^
NivTurk was developed with support from the National Center for Advancing Translational Sciences (NCATS), a component of the National Institute of Health (NIH), under award number UL1TR003017.
