
to make env 
* pip install virtualenv
*  python<version> -m venv <virtual-environment-name>
* source env/bin/activate

create db 
>>>from main import app, db
>>> app.app_context().push()
>>> db.create_all()
>>> exit()

# Todo_App
