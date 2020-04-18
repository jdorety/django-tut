# Django Models

## Overview

### What's a model in Django?

- A Python object
- Define the structure of stored data
  - includes field types, along with other parameters
- Handles database interactions
  - model definition is independent of database engine

### Designing models

It's best practice to have separate models for every "object" (group of related information). Models are also good for selection-list options that might need expanding or modification later.

Django can define relationships between objects with `OneToOneField`, `ForeignKey`, and `ManyToManyField`.

## Model definitions

Models are usually defined in an applications's `models.py` file. They can have an arbitrary number of fields, of any type. Each field represents a column of data that we want to store in the database tables.
