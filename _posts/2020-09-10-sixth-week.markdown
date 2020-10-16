---
layout: post
title:  "What's GraphQL?"
date:   2020-10-09 
categories: jekyll update
---

In this week I set up a Graphene Django project. But let's rewind.

## What's GraphQL?
It's a query language for API, useful in my case to:
- describe data provided by a server in a statically typed Schema
- request data in a Query which exactly describes your data requirements and
- receive data in a Response containing only the data you requested.

## What's Graphene? 
Graphene is a library that provides tools to implement a GraphQL API in Python using a code-first approach. Instead of writing GraphQL Schema Definition Language (SDL), we write Python code to describe the data provided by the server.

## What's Graphene-Django?
Graphene-Django is built on top of Graphene and provides some additional abstractions that make it easy to add GraphQL functionality to a Django project.

Source: <a href="https://docs.graphene-python.org/projects/django/en/latest/" target="_blank">https://docs.graphene-python.org/projects/django/en/latest/</a> 


 