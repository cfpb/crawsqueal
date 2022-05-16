From the repo's root, compile front-end assets:

```
yarn
yarn build
```

Create a Python virtual environment and install requirements:

```
cd viewer/
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Set required environment variable pointing to crawl database:

```
export CRAWL_DATABASE=../cfgov.sqlite3
```

Run the Django webserver:

```
./manage.py runserver
```