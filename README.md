# What I Learned In Term 2, Week 16 At Code Immersives

&nbsp;

## Hard Coding

Hard coding is the software development practice of embedding data directly into the source code of a program or other executable object, as opposed to obtaining the data from external sources or generating it at runtime. Hard-coded data typically can only be modified by editing the source code and recompiling the executable, although it can be changed in memory or on disk using a debugger or hex editor. Data that are hard-coded usually represent unchanging pieces of information, such as physical constants, version numbers and static text elements.

Hard coding requires the program's source code to be changed any time the input data or desired format changes, when it might be more convenient to the end user to change the detail by some means outside the program.

Hard coding is often required, but can also be considered an anti-pattern. Programmers may not have a dynamic user interface solution for the end user worked out but must still deliver the feature or release the program. This is usually temporary but does resolve, in a short term sense, the pressure to deliver the code. Later, softcoding is done to allow a user to pass on parameters that give the end user a way to modify the results or outcome.

&nbsp;

# Node.JS Frameworks

## Express JS

https://expressjs.com/

    // Install
    npm i express

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

&nbsp;

## Morgan

https://www.npmjs.com/package/morgan

HTTP request logger middleware for node.js

Morgan helps log what requests are being made to the server. Before using, install the morgan library using the command `npm i morgan` in the terminal

    npm i morgan

&nbsp;

## JSON Viewer

https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh

The most beautiful and customizable JSON/JSONP highlighter that your eyes have ever seen. Open source at https://goo.gl/fmphc7

Makes viewing JSON Objects neater & prettier to look at.

&nbsp;

## MVC, Model View Controller

- Model - Database
- View - Client, show on screen
- Controller - Handle the logic

Model => Controller => User

&nbsp;

## MongoDB

https://www.mongodb.com/

MongoDB is a document-oriented NoSQL database used for high volume data storage. Instead of using tables and rows as in the traditional relational databases, MongoDB makes use of collections and documents. Documents consist of key-value pairs which are the basic unit of data in MongoDB. Collections contain sets of documents and function which is the equivalent of relational database tables. MongoDB is a database which came into light around the mid-2000s.

INSTALLATION & USE

https://shashank6341.medium.com/installing-mongodb-on-macos-catalina-big-sur-or-older-d47c18b0c57d

&nbsp;

## Payload

### Data = Payload

In computing and telecommunications, the payload is the part of transmitted data that is the actual intended message. Headers and metadata are sent only to enable payload delivery.

    {
        "status":"OK",
        "data":
            {
                "message":"Hello, world!"
            }
    }

In this example, the string Hello, world! is the payload, the part that the recipient is interested in; the rest, while vital information, is protocol overhead.
