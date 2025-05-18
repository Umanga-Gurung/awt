## HTTP Methods
**HTTP** methods are the different types of requests a cilent can make to the server. They allow backend to recognize what kind of response the cilent except.

### 1.GET
**GET** is used to request data from a specified resource.GET requests should never be used when dealing with sensitive data because  the query string (name/value pairs) is sent in the URL of a GET request.
### 2.POST
**POST** is used to send data to a server to create/update a resource.The data sent to the server with POST is stored in the request body of the HTTP request so can be used when dealing with sensitive data.
### 3.PUT
**PUT** method is used to request the server to store the included entity-body at a location specified by the given URL.
### 4.DELETE
**DELETE** method is used to request the server to delete a file at a location specified by the given URL.

*********

## HTTP Status Codes
HTTP Status codes are numeric values sent by the server to the client.
### 1xx: Information
These codes indicate that the server has received the request and is processing it.
1. **100 Continue**
2. **101 Switching Protocols**
3. **102 Processing**
### 2xx: Successful
These codes indicate that the client’s request was successfully received, understood, and processed by the server.
1. **200 OK**
2. **201 Created**
3. **204 No Content**
### 3xx: Redirection
These codes indicate that the client needs to take additional actions to fulfill the request. They are often used when the requested resource has moved to a different location. 
1. **301 Moved Permanently**
2. **303 See Other**
### 4xx: Client Error
These status codes are used when there was something wrong in the client side.

1. **400 Bad Request**
2. **401 Unauthorized**
3. **404 Not Found**
### 5xx: Server Error
These status codes indicate that the problem is in the server side.

1. **500 Internal Server Error**
2. **502 Bad Gateway**
3. **503 Service Unavailable**

**************

## CSS selectors
These are used to add styling to the selected tags.

1. **Universal Selector (*)**: Selects all elements.
```css
*{ 
  text-align: center;
  color: blue;
}
```
2.**Type selector**: Selects all the elements of given type.
```css
p {
  text-align: center;
  color: red;
}
```
3.**Class selector**: Selects all the elements of specified class.
```css
.center {
  text-align: center;
  color: red;
}
```
4.**ID selector**: Selects the element with the given id.
```css
#para1 {
  text-align: center;
  color: red;
}
```

*********************

## GIT Basics
1. **init**: This command is used at the beginning of the project. This is neccessary because this command creates a hidden file .git which helps in tracking changes.
      ```
      git init
      ```
2. **add**: This command is used to add changed files and folders. git add . adds all changed files or mentioning file names will only add specfic files.
      ```
      git add fileName
      ```
3. **commit**: This command saves a permanent snapshot with a message. It lets Git know what changed and when.
      ```
      git commmit -m "commit message"
      ```
4. **push**: This command sends the local commit to a remote repository. It uploads the changes to the git repository.
      ```
      git push
      ```
5. **pull**: This command is use to fetch changes from the the git repository.
      ```
      git pull origin branch-name
      ```
6. **clone**: This command is used when creating a copy of an existing repository.
      ```
      git clone repository-url
      ```
7. **branch****: In Git, branches are the copies of a project where multiple people can work together without affecting one another. git branch is used to create a new branch.
      ```
      git branch branch-name
      ```
***********
## Callback Function
A callback function is a function that is passsed as an argument to another function.
***********
## Higher Order Function
A higher order function is a function that accepts another function as a parameter or returns a function.
********
## Array Methods
1. **filter()**: Retruns a new array that pass certain condition.

2. **map()**: Iterates through each elements of the array, applies a function to the element and returns a new array.

3. **forEach()**: Runs a function for each item and does not return a new array.

4. **push()**: Adds a new element to the end of an array.

5. **pop()**: Removes the last element of an array and return it.




