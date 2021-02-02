## E02: Names
---
### Reveal Your Intent
* If you need a comment, the name doesn't reveal intent
* Variables should describe themselves

### Describe the Problem
* If you have to read the code to understand a name, the name has failed to communicate

### Avoid Disinformation
* If a name doesn't mean what it says, that's disinformation
* If you have to look a comment, you're using the wrong name
* Concrete names for abstract classes is disinformation
* The name should be as abstract as the class

### Pronounceable Names
* pretty self explanatory
* `PC_GWDA` and `PC_GWDB` are bad names
* `getYYYY` should be `getYear`

### Avoid Encodings
* Hungarian Notation, etc...

### Parts of Speech
* Classes and Variables are nouns
  1. i.e. Account, MessageParser
  2. Avoid noise words (Manager, Processor, Data, Info)
* Variables (properties) should also be nouns or predicates
  1. i.e. Account, Deposit account might hold an instance of the Account Class
  2. isLate, hasName, isOld
* Methods are Verbs
  1. postPayment, getPrice
  2. If method returns a boolean then should be written like predicate (isPostable, hasName)

### Scope Rule
* The *bigger* the scope, the shorter a class/method name should be
* The *shorter* the scope, the longer the class/method name should be

### Recap
* Choose your names thoughtfully
* Communicate Intent
* Always avoid disinformation
* Pronounceable Names
* Avoid Encodings
* Choose Parts of Speech Well
* The Scope Rule