# twitoff-productizationandthecloud
#Web application development with Flask class practice 

##Installation 

TODO: instructions for git clone

##set up

TODO: instructions for virtual environment 

Also set up a database:
# Windows users can omit the "FLASK_APP=web_app" part...
'''sh
FLASK_APP=web_app flask db init #> generates app/migrations dir

# run both when changing the schema:
FLASK_APP=web_app flask db migrate #> creates the db (with "alembic_version" table)
FLASK_APP=web_app flask db upgrade #> creates the specified tables
'''


##usage

'''sh
#mac:
FLASK_APP=hello.py flask run

#windows:
set FLASK_APP=hello.py
flask run
'''
