# React for UI/UX Designers and Frontend Developers

## Overview

What is React? 

React is a frontend JavaScript library to created web components based on similar concepts as a MVC or Model, View, Controller methodology, similar to Angular.

The key differences between React and Angular is that React is just a frontend library to create purely frontend UI Web Components while Angular is a Frontend Framework which allows for frontend, middleware, and backend Web Development.

React is just a library to generate a view.

Additionally React has packages that can be installed that utalizes popular design systems such as Bootstrap, Material Design, etc.

Utalizing various packages for React, one can create frontend components that are interactive, similar to Figma prototypes that can be easily implemented into a larger web development pipeline.

The basis is around the markup that React uses to create theses frontend UI web components.

The world wide web is created with HTML/CSS/JS.

HTML is a markup language, CSS is styling, and JS is the interactive components for example animation of visual web assets.

React uses a different markup langauge called JSX which is writing JavaScript as Markup which creates HTML elements on to the virtual DOM. 

This is the basis of component based UI Frontend Development.

Also there is React Native which is React.JS for mobile development. Which creates cross platform iOS and Android apps from a single code base while having Native functionality.

The key difference between Native and Hybrid mobile applications are things related to accessing functionality on the mobile devices for example GPS, or camera functionality.

As UI/UX Designers and Frontend Developers being able to utalize React.JS and React Native allows for collaboration with other developers, backend developers who would be creating the rest of the web app or mobile app.

## Limitations of Figma, Adobe

User Interface, User Experience and Interaction Designers who utalize Figma, Adobe are limited because of the realities of development based on the prototypes that are able to be replicated, for example creating UI Animations demonstrations in Adobe After Effects. 

Although Figma is useful in Rapid Prototyping to create low fidelity mockups to be sent to developers who could create the screens in React. 

Mainly the disconnect between designers who use Figma and developers who use React is the realities of UI Frontend Web Development, the limitations on team resources, etc.

Many large scale UI design systems do not heavily utalize animations and transitions for example, rather the designers would be working on massive design files that are created with Master Component methodology, as well as autolayout. 

User Experience could be an issue in regards to not being able to actually implement some of these prototypes.

Or having to create custom code to fit the design specs when for example the designer could design based on the bootstrap design system.

UX Researchers would most likely only be utalizing Figjam, creating Mindmaps, conducting User Interviews, User Testing, and most of the time are hands off in regards to the pixel perfect specs of User Interface Design, as well as it's implementation by Frontend Developers. 

## Why learn React as a designer

It's not about a designer who can code or a developer who can design. It's about the disconnect between designers and developers who are unable to speak the same language. 

As well as the availability of only certain React packages that allow for animations, and interactions that improve usability.

Without having the developer having to create custom solutions, as so can allocate more to the backend of the app. 

Useful for smaller teams, startups, and teams within larger corporations, with design contractor teams, senior designers, directors, having one designer there that can understand the language that the developers are speaking. 

Or in development teams having a developer there that can bridge the divide between the designers and developers. 

At the end of the day it is your decision to learn React or not. 

To be a specialist that purely uses Figma, or a specalist that only uses React. 

### Final Words

As of January 2024, there are 100-200 hybrid/on-site jobs on Linkedin in the San Francisco Bay Area Silicon Valley for UI/UX Designers. 

While there are 1000-3000 hybrid/on-site jobs for UI/UX Frontend Developers. 

## Utalizing React.JS, and installing packages

With your shell of choice, personally I prefer WSL2 which is a Linux subsystem within Windows.

There is also powershell, command line, etc.

The following are for Linux. 

    npx create-next-app@latest

Next.js is a full-stack React framework.

This should install it globally on your local machine.

Or just use NPM

NPM is package management for installing packages via the command line.

    npm install -g create-react-app

If you run into permission denied use sudo

    sudo npm install -g create-react-app

If you would like to know where you are in the file system

    pwd

To create a new directory

    mkdir newdirectory

To navigate into new directory

    cd newdirectory

Now create a new project with this command

    create-react-app test-project

After everything runs successfully, if you run into issues search stackoverflow

navigate into test-project

    cd test-project

Then run the React app locally with npm start

    npm start

This command will start the web server that is hosted locally on your machine

On your web browser of choice enter this into the url

    http://localhost:3000

React is cross browser