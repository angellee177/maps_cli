# An small packages to convert address.csv into LatLong.csv

## Context and Problem statement
The CLI should be able to read address on csv files line by line, and export it as Latitude and Longitude.

Success criteria:
* Can read csv files from process.stdin
* Can convert the address into Latitude and Longitude
* Print out each line of the result on terminal.

## Considered Options

### Options 1 Typescript
* Pros
  * Strong static type programming languages, which mensure type errors are eliminated before the codes were deployed.
  * Quite similar with Node.js, So, it will save more time for the deployment and learning curves,
  * Support a lot of library that make it more easier to build the features.

* Cons
  * Built-time overhead, Typescript codes need to be compiled into JS before it can be executed in the browser or on the server which make the deployment time increase if there is any changes.
  * Not relevant with current company tech stack.

### Options 2 Kotlin
* Pros
  * Strong static type programming languages, which mensure type errors are eliminated before the codes were deployed.

* Cons
  * Not really familiar with Kotlin, might need more time to learn and the deployment.

### Options 3 PHP
* Pros
  * Quite similar with PHP, So, it will save more time for the deployment and learning curves,
  * 
  * 

* Cons
  * Dynamic programming languages, which might occurs type errors on deployment.
  * Not relevant with current company tech stack.

## Decision outcome
// what did choose
// why?
  // what was the balance of tradeoffs that resulted in 1 decision being right for today
  // some decisions are correct today and terrible later, if it's not clear why a potentially
  // suboptimal longer-term decision was made, then add more context to the 1st section and
  // explain the pro's of the chosen option or cons of the skipped ones in terms of that context.
  
### { details/appendices should be sub-sections of Decision outcome }