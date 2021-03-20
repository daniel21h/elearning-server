## Backend e.learning
![Badge](https://img.shields.io/static/v1?label=DH&message=DOSOMETHINGGREAT&color=0070f3&style=<0070f3>&logo=rocket)

## Description

The e.learning is an application geared towards education, offering courses in the field of several areas of knowledge with content in video format.

###### Project under development

## Techologies

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)

## Features

###### Authentication
- [ ] It allows the creation of users and the authentication of created users. These users will be the administrators of the application who will be responsible for all content creation that will be consumed on their front end.

###### Course management
- [ ]  Allow courses to be maintained (registered / updated) in the application, these will be authenticated routes where only authenticated users can access it.

- [ ] The registration of courses can only be done by administrators authenticated in the application.

###### Class management
- [ ] Allow classes to be maintained (registered / updated) in the application, these will be authenticated routes where only authenticated users can access it.

###### Courses listing
- [ ] In order for the user to be able to view the courses available on the platform, you must create a route that will be accessed to make this search in your database.

- [ ] This route must receive a parameter in the Header, as if you were sending a token. This token will be the MAC address of the user's device. This id will be used to make a relationship between classes, and classes completed by a user.

###### Class listing
- [ ] In order for the user to be able to view the classes available on the platform, you must create a route that will be accessed to make this search in your database.

## Getting Started

Before you begin, you will need to have the following tools installed on your machine:
- [Git](https://git-scm.com)


The project can be built with npm or yarn, so choose one of the approach bellow in case you don't have any installed on your system.

Npm is distributed with Node.js which means that when you download Node.js, you automatically get npm installed on your computer
- [Node.js v14.16.0](https://nodejs.org/) or heigher.

Yarn is a package manager built by Facebook Team and seems to be faster than npm in general.
- [Yarn v1.22.5](https://yarnpkg.com/) or heigher.

Also, it’s good to have an editor to work with the code like [VSCode](https://code.visualstudio.com/).

## :information_source: How To Use

Follow the instructions below to download and use the project from this repository:

```bash
# Clone this repository
$ git clone https://github.com/daniel21h/elearning-server.git

# Go into the repository
$ cd elearning-server

# Install dependencies
$ yarn install

# Run the server
$ yarn dev:server

# The server will start at port 3333.
# Go to http://localhost:3333
```

---

Made with :blue_heart: by Daniel Hessel :wave: [Get in touch!](https://www.linkedin.com/in/daniel-hessel-240731176/)