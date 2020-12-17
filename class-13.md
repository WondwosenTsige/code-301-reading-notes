### [Table of Contents](https://wondwosentsige.github.io/code-301-reading-notes/Home)

## Read 13

### Sending form data



- The web uses a client/server architecture; clients sends requests to servers using HTTP protocol & servers answers using the same protocol

__Client side__

- The form element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. 

- The two most important attributes are action and method.

- The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form 

- The method attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method


- The GET method is the method used by the browser to ask the server to send back a given resource.


- The POST method is a method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.

- HTTP requests are never displayed to the user without useing tools such as the Firefox Network Monitor or the Chrome Developer tools.


__Server side__

- Whichever HTTP method we choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs. The way you access this list depends on the development platform.

- Sending files with HTML forms is a special case. Files are binary data or considered as such whereas all other data is text data. Because HTTP is a text protocol, there are special requirements for handling binary data.

- The encrypt attribute let us specify the value of the Content-Type HTTP header included in the request generated when the form is submitted. This header is very important because it tells the server what kind of data is being sent.

































=====================================

__Attributions for the following Reference materials and their authors__

[MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data)[EJS Partials- Hensle Joseph](https://medium.com/@henslejoseph/ejs-partials-f6f102cb7433)






[>> NEXT (Read-14a)](https://wondwosentsige.github.io/code-301-reading-notes/class-14a)