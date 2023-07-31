# Mealternative (Backend)

The backend repo which powers up 
It mainly handles all actions related to authentication, recipe operation and user informations.

- CRUD with mongoDB using mongoose
- custom auth implementation using jwt without using a fully managed service
- Multi user posting and interacting (likes, bookmarks etc)
- Pagination and randomise display recipe
- Sorting based on all sorts of different criteria

## Introduction

This project is not built for production usage, I've built this website maily to refresh
my knowledge on the MERN stack. Some of the functionality implementation may not be best
practice (like building a auth system myself..). However, this project does showcase how
to effectively interact with mongoDB using mongoose, hopefully you could find something
useful from this repo.