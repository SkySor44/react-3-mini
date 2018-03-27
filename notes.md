<h1>Notes</h1>

<h2  style ="color: #4889f2" >JSON Objects: </h2>
<p>property names in quotes, all quotes are double quotes, values are only strings and numbers, no trailing commas(comma on last property value),  always have brackets before and after the JSON object</p>

<h2  style ="color: #4889f2" >REST -Representational State Transfer</h2>
<p>Get(read), put(update), post(create), delete</p>
<p>CRUD -Create, Read, Update, Delete: an acronym that describes a web app that can do all these things. These are constraints in the web dev world so when you send one of these requests to another server they do what these tell you to do. Someone could be an a-hole and send back a delete everything response to your get response.</p>

<h3  style ="color: #4889f2" >API - Application Program Interface: Its how you communicate to other programs.</h3>

<p>PUT http://www.devmounta.in/api/students/9435/?name='Jenny' updates a specific student's name. protocol, server location, folder, file, param, query, updated value</p>

<p>Javascript is syncronus or it works from top to bottom</p>

<h2  style ="color: #4889f2" >Axios is a promised based library used to gather data from servers.</h2>
<p> Promises enable your website to do other tasks while it retrieves data from servers. Without promises this doesn't work</p>

<p>All you have to do is axios.get(URL) or any other request as a method to get an object from an api</p>

<p>Promised Objects have 3 responses when a request is made to a server: pending, resolved, or rejected</p>

<p> You can set the axios.get() to a variable and then do that variable.then(create variable name for response) and it will show when available.</p>

<h3>EX: let promise = axios.get(fsdfkjasl;)
    promise.then(serverResponse) => {console.log(serverResponse)}
    </h3>

<p> The common practice is to call the variable res. From the example above res would replace the serverResponse variable</p>
<p>If you need to perform something after you get the date back you need to put the action in the .then method after the data comes back</p>

<p>Anytime you interact with a 3rd-party API look at their documentation which tells you how to interact with the server</p>

<p>ALWAYS BIND YOUR METHOD IF YOU USE THE "THIS" KEYWORD</p>

<h2 style ="color: #4889f2">React Lifecycle Methods</h2>
<p>If you are using the this keyword in a React built-in lifecylce method you do not need to bind. EX: componentDidMount, constructor, render</p>
<p>componentDidMount() is invoked right away to go and get the data from the server. If you have data you want on the screen the second the page loads get it in the componentDidMount method.</p>