# Pizza-order-and-delivery-website

## [Click to try!](https://flora-pizza.herokuapp.com/)

## Functions achieve

* A web application for handling a pizza restaurant’s online orders.
* Users can browse the restaurant’s menu, add items to their cart, and submit their orders, and restaurant owners can add, update, and remove items on the menu.

## Techniques

 Python, Django, HTML, CSS, JavaScript

## How to achieve

![Image of architecture](https://github.com/YJZFlora/Pizza-order-and-delivery-website/blob/master/Architecture.png)

## How to run in local
* Run app:
```python3 manage.py runserver```

* Make changes of the app:
```python manage.py makemigrations```

```python [manage.py](http://manage.py/) migrate```

* Admin user can open admin site here:
(http://127.0.0.1:8000/admin)

* OR Admin user can open manage shell for database management:

 ```python3 manage.py createsuperuser```
 You will be prompted to enter a username, email address, and strong password.

  ```python3 manage.py shell```

  * open table of the database
  ```from orders.models import <table name>```

  * fetch cartain rows from table
  ```f = <table name>(<attribute>=<value>, <attribute>=<value>)``` OR
  ```Basics.objects.filter(Size="small")``` OR
  ```one = Basics.objects.get(id=3)```

  * delete certain rows
  ```one.delete()```

  * save changes to the table
  ```f.save()```

  * fetch all rows of the table
  ```Basics.objects.all()```

## Future work

* Optimize the front-end UI design. 
* Use React to refactor the code of JavaScript.
* Add dynamic functions. 

## References

https://docs.cs50.net/web/2020/x/projects/3/project3.html

https://www.youtube.com/watch?v=6DI_7Zja8Zc

https://docs.djangoproject.com/en/3.0/howto/deployment/checklist/
