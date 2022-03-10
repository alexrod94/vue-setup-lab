# vue-setup-lab

## Lab Goal

In this lab you'll start exploring how Vue.js works and how to create a project using this web development framework.

Your goals for this lab will be the following:

- Installing the Vue.js CLI in your computer
- Creating a new Vue project with a specific set of configurations
- Creating a new Vue component inside your project and showing it in the home screen
- Showing data from your JavaScript inside your HTML
- (Bonus) Creating a "Hello World" function that fires when you press a button
- (Bonus) Creating two different routes and navigating between them

We'll be following the official Vue.js guide for most of this lab.

## Installing the Vue CLI

The first step before creating your first Vue project will be to install the CLI. You only need to take this step once on your computer.

You can find the instructions [in this link](https://cli.vuejs.org/guide/installation.html). Remember to add the "-g" command in order to install Vue in your computer instead of just inside a specific folder.

If you're working on Mac, remember you'll need to add the keyword "sudo" before the command in order for it to work.

## Create a new Vue project

Creating a new project on Vue is as simple as inserting a command on your console once you've installed the CLI globally. You can see the exact steps to follow [in this link](https://cli.vuejs.org/guide/installation.html).

Once you're creating a new project, you'll be able to choose which features you want. In this case, we want you to choose a few features manually:

- Babel
- Router
- Linter / Formatter

We also want you to create a Vue 2 project instead of a Vue 3 one. If you have any questions, the documentation is your best friend!

## Create a new Vue component inside your project and show it in the home screen

Have you created your first project yet? Great! Now you'll start navigating inside the project's structure.

In order to make your life easier, we recommend you to install the [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) extension. It will help you create new components and add functionalities in an easier way.

Once you've created your new project and navigated inside the folder the CLI has created, you can now create your first Vue component!

Here's a helpful guide in case you're stuck: [How to create a Vue component](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Vue_first_component).

Pro tip: if you use the Vetur extension, you just need to write "vue" inside your .vue file and choose the appropriate template to get a basic structure.

Once you've created your new component, we want to show it inside the App.vue file. We've already seen in class how to do that; but [here's a step by step guide](https://flaviocopes.com/vue-import-component/) that'll help you with this task.

## Showing data from your JavaScript inside your HTML

Now that you have your new component, we're going to practice how to link the elements inside the `<script>` with our `<template>`
