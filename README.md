#Pipenv

Pipenv is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world. Windows is a first-class citizen, in our world.

It automatically creates and manages a virtualenv for your projects, as well as adds/removes packages from your Pipfile as you install/uninstall packages. It also generates the ever-important Pipfile.lock, which is used to produce deterministic builds.

Pipenv is primarily meant to provide users and developers of applications with an easy method to setup a working environment. For the distinction between libraries and applications and the usage of setup.py vs Pipfile to define dependencies, see ☤ Pipfile vs setup.py.


# Step 1:

Create a new repository


# Step2

Clone to local machine

# Step 3 

create a pipenv file

`pipenv install`

# Step 4 install standard libraries

`pipenv install pandas
`

Your Pipfile should look something like this:


[[source]]
name = "pypi"
url = "https://pypi.org/simple"
verify_ssl = true

[dev-packages]

[packages]
pandas = "*"

[requires]
python_version = "3.7"


# Step 5 Install Jupyter notebook in this enviroment
`
pipenv install ipykernel
pipenv shell
`
Now lets bash in to the enviroment  and install our kernel in the noteboook

`python -m ipykernel install --user --name=pipenv_class`

now lets launch the notebook



# Step 6 Package your model



# Step 7 Install your model via pipenv


'pipenv install -e git+https://github.com/JalatorrS1/class_dim_reduction.git#egg=dim-reduction'








#sources
https://realpython.com/pipenv-guide/
https://pipenv.kennethreitz.org/en/latest/




