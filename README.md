# python-web-bottle-mvc-traefik-postgres-pop

## Description
Simple web app that serves static pages
for a bottle project.

Uses sqlalchemy query a table `pop`.

## Tech stack
- python
  - bottle
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- postgres
- ssl

## Docker stack
- python:latest
- postgresql
- alpine:edge
- traefik:v2.4

## To run
`sudo ./install.sh -u`
- [Availble at](https://myapi.docker.localhost)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
