# Data Modeling with Postgres

### Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.


### Project Description

In this project we will create a Postgres database with tables designed to optimize queries on song play analysis. We will create a database schema and ETL pipeline for this analysis. We will then test our database and ETL pipeline by running queries given to us by the analytics team from Sparkify and compare your results with their expected results.As part of this project, we will define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.