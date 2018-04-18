Frontend Challenge for Developer Candidates
===========================================

To better assess a candidates development skills, we would like to provide the following challenge. 

Prerequisites
-------------

* [Git](http://git-scm.com/)
* [npm](https://www.npmjs.org/)

Installation
------------

First of all - create a fork of this project.

To start:

```bash
$ npm install
```

To develop:

```bash
$ npm run dev```

To build for production:

```bash
$ npm run build
```

To lint you code:

```bash
$ npm run lint
```

Visit [http://localhost:4000](http://localhost:4000)

---

Project description
-------------------

We want you to develop a small application that allows sending money from one user to another. Application needs to be one page app.

Make sure you commit your changes to repository when needed. Make sure you use node.js packages where possible. 

1. Add axios to the project
2. Implement List component. It should show data from http://localhost:4000/data.json in the list. Add columns Name, Email and Friend count.
3. Change Home component with List component to ensure that it is the initial page in the system. 
5. Implement Form component. Make sure that Form opens with detailed data when clicking on an item in the List. Choose yourself which fields will be editable on the Form. Implement tag and email edit fields.
4. On the Form component you will need an additional block that has selection field with the list of other users, a field for amount and action button to send money. Money can be sent only from / to active users. You may want to use vuex. 
6. Add Bootstrap 4 to the project, change custom layout to your taste, would be nice if everything would be centered vertically and horizontally. Responsiveness would be a nice thing to see. 

Evaluation criteria (in order of importance)
-----------------
1. Code organization
2. Code readability (including comments)
3. Commit history - structure and quality


