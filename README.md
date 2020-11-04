# Backend Developer Checklist
A list of topics/concepts that (most) backend developers should be familiar with. 

### The Basics
* Master at least one modern programming language, backend framework & database. 
* In 2020: Javascript, Python, Ruby are all a good place to start. But get familiar with other programming languages (especially other paradigms).
* Practice writing code and solving problems. A lot. Codewars, CodeChef, Leetcode are all great platforms to get started. 
* Build (a lot of) small side-projects, but go big once in a while (e.g build a clone of Youtube or WhatsApp). 
* Slow code is bad (with few exceptions), learn how to properly use common algorithms and data structures.

### Version Control (i.e Git)
* Make it a habit to commit often and early. 
* Commits with too many changes are not good (again commit early and often). 
* Writing good commit messages is also important. Look up a convention and stick to it. 
* Not putting all your code in one branch is important. Learn Gitflow (or equivalent).
* If you're planning to work with a team (hopefully), learn how to use Pull Requests. 
* Giving and receiving feedback about code is key, learn how to do it (and practice a lot). 

### Databases
* Being good at databases is not about using Postgres over MySQL or MongoDB over Postgres. 
* It's about good database design, it's about writing efficient queries and it's about building a reliable backup system (among other things). 
* Learn how to deploy a database, migrate a database, make schema changes without unleashing hell (see migrations). 
* Get familiar with both SQL and NoSQL (and when to use each one).
* Don't write slow search queries. Learn about indexing.  
* Learn to use (or live with) an existing ORM. They are here to stay. 

### Deployment
* Practice deploying on a VPS (DigitalOcean is a good place to start, Heroku doesn't count). 
* Look into SSH keys, how to generate one, how to use it, how to disable root login. 
* Learn server security and networking best practices, how a firewall works. 

### Automated Testing
* A good understanting why testing is important. 
* Get familiar with the basic types of tests (unit, integration, performance tests ...)
* Learn few tools and libraries that makes writing tests easy. 
* Writing tests is one thing, running them is a whole different thing. Get yourself familiar with Continuous Integration. 

### API Design
* RESTful and JSON is the new normal when it comes to API. Start there.
* Like almost everything else in software, API Design has best practices and conventions. Look those up. 
* Don't implement only the happy case, send an error code and/or message when things go wrong. 
* GrapQL is an interesting take on implementing an API, definitely get familiar with that.

### Code Readability
* Get familiar with the right (and wrong) way to organize your code.
* How you name files and folders is critical (for your teammates). Think it through before you click save. 
* Learn and stick to (your team, programming language, framework) conventions.
* For example don't use Java conventions while writing Python code. 
* Comments are important. But code as documentation is even better (when possible). 

### Communication
* Writing is only half the job. Being able to explain your ideas is super important. 
* Practice explaining complex technical concepts and implementations. Your team will be grateful. 
* Get familiar with giving and receiving feedback about code, yes it's uncomfortable but really important. 
* There is an art to giving and receiving feedback, get familiar with [the basics](https://buffer.com/resources/how-to-give-receive-feedback-work/). 

### Something missing?
Don't hesitate to open a PR and share your thoughts. 
