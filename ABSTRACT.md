# Florida Man uses cache as database

Florida Man loves speed. He loves it so much that he’s going to do the unthinkable—he's going to use a cache as his primary database. We'll explore just how Florida Man will do this without losing persistence and without having to drop ACID—that's atomicity, consistency, isolation, and durability. And we'll see that Florida Man can have all the CRUD a database provides and the blazing fast speed that a cache provides.

We'll do this with an app that would make Florida Man proud. I've cooked up a service that screen scrapes websites with articles featuring his exploits and loads them into Redis—my cache of choice. On top of this, I've built a website that allows users to view and search for articles—using tags, keywords, and vector search.

I'll show how all of it works—covering the details above—and explain what vector search and embeddings are in a way that even Florida Man could understand. And, of course, I'll demo it live so we can find the Florida Man stories you need to see.

When it's all said and done, you'll see how a cache like Redis can be persistent, ACID-compliant, and even searchable. You'll have an intuitive understanding of vector search, and—best of all—you'll have an app that you can use to start your own projects.