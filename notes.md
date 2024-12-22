#Project Notes#
------------------------------
- This is file ***notes.md*** is intended to be read alongside its accompanied ***etl_flow.md***. 
- ***etl_flow.md*** focuses on project steps and intended goals. If you don't need all the extra information, this file is more straightforward.
- ***notes.md*** focuses primarily on the authors thoughts and reasoning
as well as breadcrumbs for author or other developers. Three digit numbers tether headings from respective .md files together as rudimentary bookmarking.

##Virtual Environments 001##
------------------------------
- It is good practice to make sure you use a virtual environment before starting a project.
This guarantees that your environment is isolates and modules/libraries are orderly.

- Locate to directory: *bash:* python -m venv <virtualenvname>
- Activate venv *bash:* .\<virtualenvironmentname>\Scripts\activate
- To deactivate *bash:* deactivate
- List packages *bash:* pip list
- Easy requirements.txt *bash:* pip freeze > requirements.txt

##Extraction 002##
------------------------------
- Trying to make a .ts extraction script that showcases Strong Typing for correctly handling data as well as potential ability to do light transformations? i.e. changing values like phone number from num to string etc.

- Improve on the previous project by pulling from at least two or three sources. The trick here is to make the pipeline as modular as possible and to explore how to make the scripts handle generic and specific ETL usecases for different data sources.

##Transformation##
------------------------------

##Loading##
------------------------------

##Schema##
------------------------------

##PostgreSQL##
------------------------------