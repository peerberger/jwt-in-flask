# jwt-in-flask
 
- Clone or download as zip.
- Install packages.
    ```
    pipenv install
    ```
- To create the dtabase, do **one** of the following.
    - Open the python interpreter, and run the following command.
    ```
    >>> from app import db
    >>> db.create_all()
    ```
    OR
    - Run the **create_db.py** file.
    ```
    pipenv run python create_db.py
    ```