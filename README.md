# Catalogue


The Tasks have been done using Fast API in Python. MySQL is used as backend database. 

## Preconditions:

- Python 3

## Clone the project

```
git clone https://github.com/nnibin/Catalogue.git
```

## Run local

## Create virtual environment
```
python -m venv venv
source venv/bin/activate
```


### Install dependencies

```
pip install -r requirements.txt
```

### Database

create a database 'catalogue' and a table 'ITEMS' in it with given columns. Either directly import the excel file or use the url '/insert' to import the data to the table.


### Run server

```
uvicorn app.main:app --reload
```


## API documentation (provided by Swagger UI)

```
http://127.0.0.1:8000/docs
```


