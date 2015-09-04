# Why SQL Matters 

## Objectives

1. Understand why learning SQL and database management are essential skills for a web developer

## Web Developers <3 Databases

As a full-stack web developer, you'll frequently be working with databases, very likely databases based on SQL, to manage the data associated with your applications. Think about the web apps you're familiar with. Facebook saves user data and persists your associations to your friends, Amazon has an enormous database of items for sale, the New York Times has a storage system for all of their articles. Most of the sites you interact with every day, and consequently most of the sites you'll work on or build, need databases to persist data.
We've already seen how we can build Ruby programs that model real-world objects and environments. With SQL and database management skills, we'll learn to store representations of the Ruby objects our programs create and retreive them at the appropriate time.

Later on, we'll learn how to connect our Ruby (and even later, Ruby on Rails) applications to a SQL databases. For example, a basic web application might have many users. So far, we've learned how to build a Ruby `User` class that produces user objects. But, we don't yet know how to store those users and their details. If a user signs up for their app and then we loose all their information immediately, we're not likely to be providing a very popular app. We need a way to take our Ruby objects, store them in a database and retrieve them at the appropriate time, for example when an existing user signs back in to our app. 

We've already built out domain models in which instances of classes are related to one another. With the SQL skills we'll be learning in this unit, we'll be able to put it all together and build apps that actually save that data. 

