# Django Rest Tutorial

This repository contains a tutorial project available on the Django Rest Framework documentation website, in the Tutorial section. I read and implemantaded all six steps, in sequence: 1- Serialization, 2- Requests and responses, 3- Class based views, 4- Authentication and permissions, 5- Relationships and hyperlinked APIs, and 6- Viewsets and routers; but the latter i purposely ignored (the viewset class implementation and router use) since the generic view class was more useful for another project i was doing at the same time.
Overall, that guide is a good first contact with the Django Rest Framework documentation and was very helpful for my personal learning, reason why i decided upload it here.

Regarding the function and use of the system, it is a basic CRUD of snippets of programing code by their respective owners (users). Each user can CRUD their own snippet, and can also view others creations. So an authentication is required to do something in DB, but isn't to read only. Users need to be created in the system-admin area.
To see it working it's necessary to have the Django Rest Framework installed (it's recommended that it be in a virtual environment) and apply the migrations to have the sqlite3 database file.
