# Secfi backend assignment

## Description
At Secfi we use a microservices architecture. Imagine we want to rebuild our authentication service, and we ask you to do it.

Users should have the following attributes:
* Username
* First name
* Last name
* Password
* Avatar

The API should allow the following operations:
* Create user
* Login
* Update user
* Remove user (self-removal)
* Avatar upload (can be a part of user update operation)

The proposed implementation scope doesn't require any privileged roles and operations (e.g. removing other users), but you are welcome to define and add them.

## Requirements
* The microservice should be written in Python, TypeScript, Java, Kotlin or Scala.
* Password should be stored in encrypted format.
* For the avatar, pick a way of storing you think is
most efficient.
* Make sure to implement the necessary authorization controls (users can update/remove/etc only themselves).
* It should run in a Docker container.

Besides that you're free to choose any framework or library you need, although you should be prepared to defend your choices.


## Evaluation
After you finish the assignment, we ask you to answer the following questions:
* How much time did you end up spending on it?
* What are some of the design decisions you made?
* What do you like about your implementation?
* What would you improve next time?

## Submission
Please create a repo and send us a link (if it's a private repo, please add @secfiEngInt github user to it).

Good luck! If you have any questions, please don't hesitate to reach out.
