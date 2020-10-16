---
layout: post
title:  "What's GraphQL?"
date:   2020-10-16 
categories: jekyll update
---
# Working with Apollo
In this week I worked on Apollo to create server and client for my work. I was not able to develop my own project, I'm still working with tutorials. 

## What's Apollo?
Apollo is a platform for building, querying and managing a data graph: a unified data layer that enables applications to interact with data from any combination of connected data stores and external APIs. Most importantly, it uses GraphQL!

## Apollo Server 
Apollo Server is an extensible, open-source JavaScript GraphQL server. With it, you can define:
- A GraphQL schema that specifies all of the types and fields available in your graph
- A collection of resolvers that specify how to populate each field of your schema with data from your back-end data sources

## Apollo Client
Apollo Client is a customizable, open-source JavaScript GraphQL client with powerful caching and state management features. It enables developers to define queries directly within the UI components that use them, and automatically update those components as query results arrive or change. 

Source: <a href="https://www.apollographql.com/docs/intro/platform/" target="_blank">https://www.apollographql.com/docs/intro/platform/</a> 

# What about metadata?
I identified the various processes that lead me to get metadata for the various journals I have. The process is: 
- Download data (they are usually structured into different bib, xml, json schemas)
- Clean data
- Convert to json my JSON schema

## Where am I?
I'm pratically done with:
- Digital Humanities Quarterly (direct xml download from their web page -> my JSON schema)
- All journals (the main part of my dataset) which have their data on Crossref (Crossref API request -> my JSON schema)
- Computers and the Humanities and IJHAC (direct bibtex download from their webpage -> my JSON schema)

## What's left out?
- Data that have to be scraped from the websites
- Datacite API (I'm waiting because it's possible to query through GraphQL)

# Issues: 
- Ask for help with Apollo Client
- Check the code for DHQ


 