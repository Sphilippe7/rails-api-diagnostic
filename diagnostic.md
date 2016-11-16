# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
The purpose of a backend is to connect the client to a web based server to retrieve,
update, or post information
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The "M" which stands for the Model, is what gets used by the controller.
```

Which layer in the MVC pattern communicates with the model?

```bash
The controller directly communicates with the Model and lets it know what to do.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// your response here
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The controller has all the CRUD actions
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
Create
Patch
Delete
update
Show
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. The controller receives the request and speaks to the Model
2. The model retrieves the stored data and then sends it back to the controller
3. The controller then sends that information back to the server
4. The user receives the information
```

What is the command to generate a new rails-api app?

```bash
rails console
```

What is the command to start an instance of a rails server?

```bash
Bundle exec rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
bundle exec rake db:drop
bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
