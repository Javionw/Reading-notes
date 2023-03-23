# Local Storage and how to use it on websites

## Q: Why would a developer use local storage for a web application?

A: Local storage is a web API that allows developers to store key-value pairs in the user's web browser. This makes it a convenient way to store data for a web application because it is persistent across sessions and does not require server-side storage or retrieval. Developers can use local storage for a variety of purposes, such as caching data, saving user preferences, or storing data temporarily before sending it to a server.

## Q: What information should not be stored in local storage?

A: It is generally not recommended to store sensitive information in local storage because it is accessible by any script running on the same origin (i.e., domain and port) as the page that set the data. This means that if an attacker is able to execute a script on the same origin as the web application, they can potentially access and manipulate the data stored in local storage. Therefore, developers should avoid storing sensitive information such as passwords, credit card numbers, or other personally identifiable information in local storage.

## Q: Local storage can store what type of data? How would you convert it to that type before storing?

A: Local storage can store string values only, so if developers want to store other data types such as numbers, booleans, or objects, they need to convert them to strings before storing them. There are several ways to do this depending on the data type:

For numbers and booleans, developers can use the toString() method to convert them to strings before storing them in local storage.

For objects, developers can use the JSON.stringify() method to convert the object to a string in JSON format before storing it in local storage. Then, when retrieving the data from local storage, they can use the JSON.parse() method to convert the JSON string back into an object.

For example, to store a number in local storage, developers can convert it to a string using the toString() method and then set it in local storage using the setItem() method: