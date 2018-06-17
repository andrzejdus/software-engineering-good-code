# Software Engineering
Qualities of good code - OOP edition

## what is software engineering?
ok, so what is ~~~software~~~ engineering?

**engineering** is the application of **scientific**, **economic**, **social**, and **practical** knowledge in order to **invent**, **design**, **build**, **maintain**, and **improve** structures, machines, devices, systems, materials and processes

**software engineering** is the study and application of engineering to the design, development, and maintenance of software

## code = API
Even private code has an API

## why
* 75% reading (understanding code)
https://blog.codinghorror.com/when-understanding-means-rewriting/
* easier maintenance
* it's cool

## consistency
* naming
  * increase/decrease
  * add/delete
  * insert/remove
  * prev vs previous
* in names, parameters etc.
* use of standard patterns
* error handling
e.g. `throw Error` vs `console.error()`
* ... consistent code style in general

Examples
* git
  * `git fetch` + `git merge` = `git pull` vs `git checkout` + `git branch` = `git checkout -b`
  * `git commit` ignores local, unstaged changes in foo.txt; `git commit foo.txt` doesn’t
  * `array_key_exists('b', $b)` vs `property_exists($c, 'd')`

## orthogonality
* functions have no side effects

Examples
* sides of rectangle vs square

## discoverability
* it should be easy to understand code by exploring it 

## adaptation

## information hiding
* encapsulation - logical hinding 

## loose coupling
* inheritance couples code more than composition 
* favor object composition over class inheritance

## model the problem domain

## be minimally complete
* make you code do all that is needed, but nothing more

## beware of extra generality
* you may never need extra generality
* when it comes you may have more knowledge how about the use of your code
* it's easier to add code to simple API vs complex one

## Demeter Law

## Heisenbugs
* state bugs

## design patterns
* GoF
* why design patterns?

## SOLID
* of course :-D

## class should define what to do not how its done

## prefer composition over inheritance
* yup!
