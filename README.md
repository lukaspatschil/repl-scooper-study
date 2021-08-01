# REPL Scooper study

This are the tasks for the repl scooper study.

## Prerequisites

In order to be able to perform this task you will need to have the following software installed:

- Visual Studio Code
- Node.js >= 12.x.x
- npm 6.x.x

## Installation

In order the start the tasks the following steps will need to be taken:

Install the dependencies by running `npm install` inside the root directory of the project. After doing so install the `REPL Scooper` plugin. THe plugin can be found in the Visual Studio Code Marketplace at [this](https://marketplace.visualstudio.com/items?itemName=LukaSpatschil.repl-scooper) link. After successfully installing the plugin you are ready to go.

Note: There is no problem with having additional plugins or themes installed, as long as they don't interfere with the tasks or your ability to solve them.

## Execute tasks

In order to execute the tasks you can use:

- Task 1: `npm run task1`
- Task 2: `npm run task2`
- Task 3: `npm run task3`

Otherwise fullfil the tasks as described and have fun.

## Tasks

### Task 1

To help you understand the plugin better you will have to use Node.js to get the name of all parent directories of index.ts and return their names in an array.
Take the supplied file path provided in `filepath` and use native JavaScript functions to extract the parent directories and save them inside an array.
The array should look like this: ['home', 'artifacts', 'AE', 'FSE-2018']

#### Hints: 
- Use the path module
- String.prototype.split
- String.prototype.splice


### Task 2

You shall retrieve all the ids of the repositories from the organization octokit. To make it easier you can use the valid configuration {org: "octokit", type: "public",} saved inside `config`.

The required package to work with the GitHub API has already been imported for you.

This task is finished if you have created an lambda expression returning all the ids of repositories from the octokit organization. This can also be as a `Promise`.

#### Hints:
- Use the installed package @octokit/rest and the repos.listForOrg function.
- You can ‘filter’ objects keys in an array with Array.prototype.map.


### Task 3

Create a function to calculate the days needed to reach a vaccination percentage from 70%.

The function takes the current population, vaccinated people and the amount of vaccines used per day as parameters. Then it returns the days needed to reach 70% of the population vaccinated.

A valid example would be:
4.515.964 people are vaccinated, there are about 80000 vaccines per day and Austria has about 9 million people.
This would mean it will take 22,30045 days to get to 70%.