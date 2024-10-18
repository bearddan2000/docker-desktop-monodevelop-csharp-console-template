# docker-desktop-monodevelop-csharp-console-template

## Description
This is a POC project to demonstrate monodevelop a integrated development environment.

This is a barebones installation no pluggins where added.

ie.
without a volume
`docker run --rm` ...
with a volume
`docker run --rm -v $(pwd):/app` ...

Supports X11 display forwarding from docker container.

## Tech stack
- monodevelop

## Docker stack
- ubuntu:20.04

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`