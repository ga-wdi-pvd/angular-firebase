# AngularFire
<!-- - Explain the difference between HTTP and Websockets, and provide an advantage and disadvantage of each. -->
- Explain what AngularFire is and how it differs from Firebase.
- Create and configure a Firebase back-end.
- Create a Javascript front-end application that communicates with a Firebase back-end.

## Framing

We've incorporated Angular into a MEN and Rails app respectively.
Today we'll be exploring another back-end alternative: Firebase.

## Firebase

#### What Is Firebase?

Firebase is a PaaS, or "Platform as a Service." That means it offers a number of cloud-based computing services, including the one that matters to us today: a realtime database. Not only can we access a Firebase DB programmatically using code, but we can also interact with data via a graphical interface in the browser.

Like MongoDB, Firebase is a NoSQL database.

<details>
 <summary><strong>What does this mean?</strong></summary>
Firebase has a non-relational database which stores data in one big JSON tree.
</details>

#### Why Use Firebase?

It's fast.
* Firebase uses Websockets to maintain a constant, open connection between the client and the database. Rather than use a traditional call-and-return system of requests and responses like HTTP, the browser and server are constantly in communication with each other and are immediately aware of changes on either end. Using Firebase, we can establish three-way data binding in an Angular application between the controller, the browser and the database.

> If you're interested in learning more about Websockets, [start here](http://www.html5rocks.com/en/tutorials/websockets/basics/).

It's user friendly.
* Firebase's graphical interface means we only need to load up a browser in order to explore what we have in our database.

Perhaps the biggest selling point: multiple clients can easily use the same database/API.
* It's just a matter of including the proper credentials in your application.

There are lots of notable apps that use Firebase, including Shazam and NPR One. [There are plenty more](https://firebase.google.com/customers/).

## AngularFire

One way to connect an Angular application to a Firebase DB is **AngularFire**.

AngularFire is a Javascript library created by Firebase. It provides us with an intuitive means of interacting with a database not unlike Mongoose or ngResource. We will be using the AngularFire library to access Firebase from Angular. We'll explore how to use it by building a todo app later on in this lesson but if you'd like to learn more, [the official documentation is a good place to start](https://github.com/firebase/angularfire).

## Walkthrough: A To-Do App

To demonstrate how to use Firebase and Angular together, let's create a simple todo app...

**[Click here](\todo.md)**

## Break

## You Do: Grumblr and Firebase

Now it's your turn. For the remainder of the lesson, you will be adding Firebase to Grumblr...

**[Click here](\grumblr.md)**

## Break

## Closing / Questions

## Resources

- [AngularFire Quickstart](https://github.com/firebase/angularfire/blob/master/docs/quickstart.md)
- [Sample AngularFire App](https://www.firebase.com/docs/web/examples.html)
- [Firebase Hosting](https://firebase.google.com/docs/hosting/quickstart)
- [Firebase CLI Tools](https://github.com/firebase/firebase-tools)
- [Intro to Websockets](http://www.html5rocks.com/en/tutorials/websockets/basics/)
- [AngularFire2 - The Official Library for Firebase and Angular 2](https://github.com/angular/angularfire2)
