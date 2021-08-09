# Project Tracker
## By Adrian Camacho :electric_plug:

---

### Project Description :pencil:

* This project is a web application that allows the user to add, update and delete a project. As well as add, update and delete volunteers to the project. 
---
### Tech Stack :floppy_disk:
1. _Ruby 2.6.3_
2. _Git_
3. _rspec gem_
4. _pry gem_
5. _capybara gem_
6. _Sinatra_
7. _Postgres_
8. _PSQL_
9. _HTML_
10. _Bootstrap_
---
### Installation Instructions :pushpin:
1. Clone this repo: `https://github.com/chonnessey/volunteer-tracker.git`
2. Enter new directory `cd volunteer-tracker`
3. Install dependencies with the `bundle` command.
4. To create a database for the project enter a psql terminal with the `psql` command.
5. Create a database called volunteer tracker with the command `CREATE DATABASE volunteer_tracker;`.
6. Connect to the database with the `\c volunteer_tracker;` command.
7. Create tables for projects and volunteers with the commands `CREATE TABLE projects;` and `CREATE TABLE volunteers;`.
8. You will need to create a testing database that mirrors you're development database with the following command `CREATE DATABASE volunteer_tracker_test WITH TEMPLATE volunteer_tracker;`
9. To run the Sinatra local server run the command `ruby app.rb` and then navigate to `localhost:4567`.
10. Fill out the forms below and have fun!
---
### Known Bugs :bug:
1. No known bugs.
2. Please open a pull request if you have any issues!
---
### Test Suite/Specification :chart_with_upwards_trend:

> See [spec folder](https://github.com/chonnessey/volunteer-tracker/tree/main/spec) for rspec test suite which includes 27 passing tests. View test results from project directory by running `rspec`.
---
### Contact Info :inbox_tray:

You can reach me at: <adriancamacho18@gmail.com> :rocket:
___
### License is GPLv3 and I make no claim to copyright. :guardsman:
<br />

> You can't steal what is freely given. Enjoy!

<br />
<br />
<br />
<br />
<p align="center">
  <small>Made in Portland, Oregon.</small>
</p>