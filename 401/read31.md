# Reading 31

## Guide to Docker

**Docker is as Linux containers which are a type of virtualization. Virtualization has its roots at the beginning of computer science when large, expensive mainframe computers were the norm.**

- With Docker We can faithfully reproduce a production environment locally.
- Docker can be shared among team members so everyone is working on the same setup.
- We can run a production database with Docker

- **How is Docker is Linux containers ?**

Linux containers which are a type of virtualization. And Virtualization has its roots at the beginning of computer science when large, expensive mainframe computers were the norm.

**Install Docker**
after downloading and installing Once Docker is done installing we can confirm the correct version is running. It should be at least version 19.

- $ docker --version
- Docker version 19.03.5, build 633a0ea

## Django for APIs

- Django REST Framework works alongside the Django web framework to create web APIs. We cannot build a web API with only Django Rest Framework; it always must be added to a project after Django itself has been installed and configured.

- Django REST Framework is added just like any other third-party app. Add the djangorestframework library

- Add it to the INSTALLED_APPS config in our settings.py file

- Ultimately, our API will expose a single endpoint that lists out all books in JSON. So we will need a new URL route, a new view, and a new serializer file.

- There are multiple ways we can organize these files however my preferred approach is to create a dedicated api app. That way even if we add more apps in the future, each app can contain the models, views, templates, and urls needed for dedicated webpages, but all API-specific files for the entire project will live in a dedicated api app.
