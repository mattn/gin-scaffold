# Gin Scaffold

`Gin Scaffold` is CLI to generate scaffolds for the `gin` framework.
For now the project only supports `mongodb` and `mgo` as database.

## Installation

	go get github.com/dcu/gin-scaffold

## Initializing a project

	gin-scaffold init <project path>

## Creating a model

	gin-scaffold model <model name> <field name>:<field type>

## Creating a controller

	gin-scaffold controller <controller name>

## Creating a scaffold

	gin-scaffold scaffold <controller name> <field name>:<field type>

## Running

	go run <project name>.go

## Accessing

	Open browser, and access to http://localhost:4000. (Default port:4000)

