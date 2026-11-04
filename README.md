# Flask Blog

Simple blog app built with Flask and SQLite. You can create, view, edit and delete posts.

## Running it

```
pip install -r requirements.txt
python init_db.py
python app.py
```

Then go to http://127.0.0.1:5000

## Routes

- `/` all posts
- `/<id>` single post
- `/create` new post
- `/<id>/edit` edit a post
- `/<id>/delete` delete a post (POST)
