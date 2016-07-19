# ood_auth_mapdn

## Introduction

**NOTE:  Work in progress!**

This is a simple MySQL-backed system for managing the mappings between 
X.509 Distinguished Names (DNs) and local users in Globus style
grid-mapfiles.

## Components

* mapdn.py -- The core of the software, a Python program that can add, delete,
or list DNs in the database.  Should only be run as a privileged user, since
it can do pretty much anything to the database.

* User self-service scripts (bash)
..* add-my-dn
..* delete-my-dn
..* list-my-dns

* Administrative scripts (bash)
..* add-user-dn
..* delete-user-dn
..* list-user-dns

* mapdn.sql -- The schema of the mapdn database.

## Installation

TODO

