# Django Blog

The project consists in a blog made from the chapters 1, 2 and 3 from the book Django 2 By Example.

## Description

Currently the app only has a post model.  
There is a superuser to manage the site and a *normaluser*.

### Model structure

####Post
| title       | slug     | author | body | publish  | created  | updated  | status |
|-------------|----------|--------|------|----------|----------|----------|--------|
| VARCHAR 250 | SLUG 250 | USER   | TEXT | DATETIME | DATETIME | DATETIME | STATUS |


### Routes
```text
/admin
```


