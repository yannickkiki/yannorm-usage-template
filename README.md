# Usage template of [yann-orm](https://github.com/yannickkiki/yann-orm)

## Getting started tutorial
* Download or clone this repo
* Install requirements
```
pip install -r requirements.txt
```
* Update `DB_SETTINGS` in `/src/settings.py` with your database connection 
  settings

Let's assume that we have a table `employees` (with the fields 
`id`, `first_name`, `last_name`, `salary`, `age`) in our database.

To manage that table, we added a model `Employee` in `/src/models.py`.
You can also register your own models there.

* Now, you can go to `src/main.py` to give a try to the 
  features provided by yannorm.
  You can find a list of these features in the README file of the 
  [project](https://github.com/yannickkiki/yann-orm)
  