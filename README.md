# REPL Scooper study

This are the tasks for the repl scooper study.

## Execute tasks

In order to execute the tasks you can use:

- Task 1: `npm run task1`
- Task 2: `npm run task2`
- Task 3: `npm run task3`

Otherwise fullfil the tasks as described and have fun.

## Tasks

### Task 1

To make you help you understand the plugin better you will have to use node to get the name of all parent directories of index.ts and return their names in an array.
The array should look like this: ['home', 'artifacts', 'AE', 'FSE-2018']
Hints: path module, String.prototype.split and String.prototype.splice


### Task 2

You shall retrieve the ids of the repositories from the organisation octokit. To make it easier you can use the valid configuration {org: "octokit", type: "public",}.
Hints: Use the installed package @octokit/rest and the repos.listForOrg function. You can ‘filter’ objects keys in an array with Array.prototype.map.


### Task 3

The function takes the current population, vaccinated people and the amount of vaccines used per day. 4.515.964 people are vaccinated, there are about 80000 vaccines per day and Austria has about 9 million people.