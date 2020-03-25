
# Resources for CSCI 6333/6315 project

Hey guys, since Chen stressed the importance of the project I wanted to drop some great resources here so that we can start to figure out the implementation. No stress though! :D

Also, feel free to send any suggestions for additions to this page via Discord =)
Once we get Git up and running, we'll be able to collaborate on code/whatever easier.
---
## Main idea / goal
We want to build a **functioning mobile app/website** that can host our home services app.
Given the requirements of the project, I suggest we build a functional, responsive, beautiful **_web app_**.

Some reasons for my suggestion:
1. Just learning javascript is enough for coding almost everything!
   - You only have to learn to code the features you're **interested** in building; i.e. nothing is overwhelming
   - We can distribute coding tasks amongst ourselves as our project evolves

2. **No limit** on what features we can add! (i.e. we are not sacrificing any functionality)

3. We only need **_one_ coding environment**!
   - Node.js is the **only environment you need to setup** for deployment on:
     - Windows
     - Mac
     - Linux
     - Android
     - iOS
     - Anything with a modern browser

   - This will save time! Setting up dedicated environments for Android/iOS specific development would give us less time to build our app =(
     - It would also be harder to learn
     - Large teams (10+) usually use these tools

4. Modern web development **looks great on a resume!** Responsive web apps are hot on the job market ; )

5. These apps can look and work fantastic using the dev tools available now in 2020!
---
## The Stack
The **_stack_** for our project is simply the list of technology our app runs on. **This is vitally important!**
These parts of our stack are **fixed** by Dr. Chen and are **non-negotiable**:
- Amazon Web Services (AWS) Aurora Relational Database
- MySQL functionality

That being said, we have *freedom* over **_everything else_!** =)
This is **great news** because we have some incredible tools here in 2020 that will make you feel *powerful* because you can build anything you imagine!

I'm sure Dr. Chen will be proud of our work by the end of the semester =)

---
## Links
### Link to big picture reference
https://stackabuse.com/using-aws-rds-with-node-js-and-express-js/
This article is a great reference for LOTS of things so I'm putting it first.
##### **Please note:** That article is **_not_** for starting out learning! It is moreso a longterm reference for implementation details.
####
Our code will look different but we will inevitably have to use such technologies.

### Links to general/educational resources

Our **stack** for our app looks something like this:
(Note that each technology can serve one or more functions)

- [Node.js](https://nodejs.org/en/):
    - Feature-rich javascript environment, only one language to learn
	- We add only the tools we need
	- Supports both front-end and back-end tools! SUPER powerful
	- [Here's a fantastic free course](https://www.udemy.com/course/node-js-api-tutorial/), only ~3 hours. I'll be refreshing my skills with this!
- [AWS Aurora](https://aws.amazon.com/rds/aurora/)
    - Relational database service
    - MySQL compatible
    - Can plug in easily to a Node.js project!
- [React](https://reactjs.org/)
    - Used to build super responsive, beautiful websites
    - Basically the visual part of our app (works to enhance HTML)
    - **Minmal coding** to achieve professional, easily extended features
- [Express](https://expressjs.com/)
    - The networking part of our stack
    - This makes a normally difficult task **almost effortless!**
- There are lots of other tools we'll discover as we move forward