# calories-tracker

For 19th March class we will have to complete the following tasks:

- [ ] Adapt the `home` function from `app.py` to calculate the calories by breakfast, lunch and dinner, and also the sum of
calories by day. 
- [ ] Display the foods/portions by breakfast, lunch and dinner in a prettier way (maybe an ordered/unordered list)
- [ ] Create a new function in `app.py` for the `Add food` functionality. The function should both support
the rendering of the `Add food` template and also the creation (POST) of the food (a `Food` entry in the database).
- [ ] Create the above `Add food` HTML template that will contain an HTML form matching the `Food` model attributes.
- [ ] Create a navbar (using the Bootstrap Nav component) and add two items: 
  - Home (will create a new Welcome page describing what the app does)
  - Log Food (will replace the existing `home` function)

# Good to know

### Installation
You need `Flask` and `Flask-SQLAlchemy` Python libraries. 

You can install them with `pip install` or using the `requirements.txt` file:

`pip install -r requirements.txt`

### Create database

Create the database with:
`flask shell`

```python
from models import db, Food
db.create_all()
```

### Run the app

Start the app with:
`flask --app app --debug run`
