# Usage template of [yann-orm](https://github.com/yannickkiki/yann-orm)

## Getting started tutorial

#### First steps
* Download or clone this repo
* Install requirements
```
pip install -r requirements.txt
```
* Update `DB_SETTINGS` in `/src/settings.py` with your database connection 
  settings


Let's assume that we have a table `employees` (with the fields 
`id`, `first_name`, `last_name`, `salary`, `age`) in our database.
To manage that table, we can add a model `Employee` in `/src/models.py`.
You can do the same thing to register your own models.

Now, you can execute `src/main.py` to try the features provided by 
the `ORM`. You can find a list of these features in 
the [project](https://github.com/yannickkiki/yann-orm) description.
