Javascript Organization Dependency Search
====================
Ever wondered how many projects in a given Github organization have a lib dependency? This script was created to solve this problem.

This project will search all projects in an organization for a specific dependency in the package.json file.


File output example:
```json
[
   {
      "repo":"repo-name-a",
      "dependencies":{
         "lib-dependency":"^2.5.0"
      }
   },
   {
      "repo":"repo-name-b",
      "dependencies":{
         "lib-dependency":"^1.5.0"
      }
   }
]

```
# Personal Token
To run this project you will need to generate a [Github Personal Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

# Install
Clone this repository ` and install it dependencies with this command:
```
npm install
```

# Running
Just execute the command bellow and wait for the `data.json` output:
```
npm start
```
