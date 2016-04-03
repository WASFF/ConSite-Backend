# Convention Website

To be completed.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [RVM](http://rvm.io)
* [Postgres](http://postgresql.org) (see Postgres below)

## Postgres

### Mac OS X

I reccomend using the postgres app from [here](https://github.com/PostgresApp/PostgresApp/releases). This was developed with 9.3.7.0

### Ubuntu

`apt-get install postgresql-9.1`

## Installation

1. `git clone 'git@github.com:WASFF/ConSite-Backend.git'` this repository
2. change into the new directory
3. Install the version of ruby if prompted by RVM
4. `bin/setup`

## Running / Development

* `rails s`
* Server will be running at [http://localhost:3000] by default

### After updating

Stop all running rails servers/consoles and run `rake db:migrate`

### Code Generators

TO BE COMPLETED

### Running Tests

All tests are written in rspec, to run them:

1. Ensure you have installed everything according to "Installation" and/or "After updating" above
2. Run `rake db:test:prepare`
3. Run `rspec spec`

Enjoy Nyan Cat :D

### Deploying

TO BE COMPLETED

## Further Reading / Useful Links

TO BE COMPLETED
