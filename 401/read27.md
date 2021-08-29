# Reading27

## Using Models

- Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms.

- Django apps uses models to access and manage data.
- Models basically refers to the database, the tables of data/information about objects.

### Model Relationships

- one to one (OneToOneField)
- one to many (ForeignKey)
- many to many (ManyToManyField)

### Model Primer

- Models are usually defined in an application's `models.py` file. They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata. The code fragment below shows a "typical" model.

### Feature Inside Models

- Fields
- Metadata
- Methods

### Model management

- Model classes can be used to create, update, or delete records, and to run queries to get all records or particular subsets of records as in the following:
  - Creating and modifying records by defining an instance of the model then calling save():
    - record = MyModelName(my_field_name="Instance #1")
    - record.save()
  - Searching for records by using the model's objects attribute

## Django Admin

- The Django admin application can use your models to automatically build a site area that you can use to create, view, update, and delete records. This can save you a lot of time during development, making it very easy to test your models and get a feel for whether you have the right data.

### Registering models

- First, open `admin.py` in the catalog application (/locallibrary/catalog/admin.py). It currently looks like this — note that it already imports django.contrib.admin:

### Creating a superuser

- In order to log into the admin site, we need a user account with Staff status enabled. In order to view and create records we also need this user to have permissions to manage all our objects. You can create a "superuser" account that has full access to the site and all needed permissions using `manage.py`.
