# Flask Boiler Plate API

Documentation
- Flask
  - https://flask.palletsprojects.com/en/1.1.x/
- Flask SQLAlchemy
  - https://flask-sqlalchemy.palletsprojects.com/en/2.x/
- Flask Marshmallow
  - https://flask-marshmallow.readthedocs.io/en/latest/
- Marshmallow-sqlalchemy
  - https://marshmallow-sqlalchemy.readthedocs.io/en/latest/

## API Endpoints

- Get all guides
    - URL:http://localhost:5000/guides


- Create a guide
    - URL: http://localhost:5000/guide
    - Send Body of json:
    '''json

        "title": "some title"
        "content": "some content"
    '''

- Edit a guide
    - URL: http://localhost:5000/guide
    - Send Body of json:
    '''json

        "title": "some title"
        "content": "some content"
    '''
