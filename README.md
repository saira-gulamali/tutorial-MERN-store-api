# 04 Store Api App

Taken from Node Tutorial and Projects Course - John Smilga

## Description

API provides data for a furniture store (including name, price, company, rating).

## Tech Stack

- node
- express
- mongoDB
- mongoose

## Usage

To start/run the app:

- npm install
- configure .env file with MONGO_URI connection string
- npm start
- connect from the browser on localhost:5000
- as there is no FE for this API, connect from Postman or insomnia to make BE requests

## Queries

- http request query parameters include:

* featured: true/false
* company: ikea, liddy, caressa, marcos
* name: all names matching a string
* sort: by name, price, rating, company (-name means descending), where there is more than 1 sort criteria append additional criteria with a comma
* fields: fields to display for each record, where there is more than 1 field append additional fields with a comma
* numericFilters: (price and rating only), use > or < or >= or <= for example, price<30,price>10 , where there is more than 1 numeric filter append additional filters with a comma
* page: page number
* limit: no of records to display per page
