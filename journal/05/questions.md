 Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > create, read, update, and delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Post for create, get for read, put for update, and delete for..hmm... ;P delete!

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object relational Maps, Mongoose?

04. Which two `HTTP` request types include a body?

  > I believe it's post and get.

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  >a await, and async?

06. What are the three types of data relationships? Provide an example of each.

  > One to many - dealership to cars
  one to one - owner to car
  many to many - cars to motorcycles

07. What is middleware?

  > I refer to it as the bouncer to the bar, lol. But it's basically the link allowing information from API's to and fro.

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > load and extract? I'm not certain

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > async getWinter(query) {
    const winter = await dbContext.winter.find(query)
  }

  I'm again not certain, i'm really bad with the terminology of things to be quite frank.

10. What is a ***virtual property***?

  > something that we don't store in MongoDB
