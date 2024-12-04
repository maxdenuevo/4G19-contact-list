# <img src="https://skillicons.dev/icons?i=react" height="40" alt="react logo"  /> Contact Management Application

Technologies: HTML, CSS, JS, React, React Router, and Context.

Small contact management application with CRUD operations.

The example should look [like this](preview.gif)

Or you can use one of these images:
[Image 1](src/img/contact-list-1.png) and
[Image 2](src/img/contact-list-2.png)

## How to start this project

1. Install the `/node_modules`

```bash
$ npm install
```

2. Run the webpack development server

```bash
$ npm run start
```

## Instructions:

1. You have to add the code needed to make your application handle contacts, specifically:
   - Create
   - Update
   - Delete
2. Ask the user for confirmation before deleting, use the Modal component for that.

All the functionalities must be implemented in the `actions` object inside the `flux.js` file.

`fetch` the data from the API: https://playground.4geeks.com/contact/docs

## This project is divided in:

### Two different views:

1. Contact: Contains the list of contacts.
2. AddContact: It's just a form used to create or update contacts.

### One component:

1. ContactCard: It just displays one contact.

## Hints:

- Start with some dummy content in the store (`flux.js`).
- Use Postman to try the API endpoints before coding.

## Sources:

This exercise is part of the complete 4Geeks Academy Full Stack course:

[![4Geeks Academy](https://img.shields.io/badge/4Geeks%20Academy-blue.svg)](https://4geeks.com/interactive-coding-tutorial/contact-list-context)
