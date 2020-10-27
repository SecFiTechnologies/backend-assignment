# Secfi backend assignment

At Secfi we use a microservices architecture. Imagine we want to rebuild our authentication service, and we ask you to do it. The service should expose an API that allows CRUD operations on a `users` table with the following interface: 
```
interface IUser {
  firstName: string;
  lastName: string;
  userName: string;
  password: string;
  avatar: string;
}
```
Some requirements that you should bear in mind when doing this project:
* It should be written in Python
* It should run in a Docker container
* The password should be stored in an encrypted format
* For the avatar, pick a way of storing you think is most efficient

After you finish the assignment, please answer the following questions:
* How much time did you end up spending on it?
* What are some of the design decisions you made?
* What do you like about your implementation?
* What would you improve next time?

The assignment doesn’t have a hard time limit but we also don’t want to take too much of your time, so try to spend a maximum of 4/5 hours on it. If you have any questions, please don't hesitate to reach out.

Good luck! 
