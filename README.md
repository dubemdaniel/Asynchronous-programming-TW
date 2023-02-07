# Asynchronous-programming  
A lot of data may take a long time to be submitted to a database. Through asynchronous programming, a user can easily move from one screen to another while the function continues. For instance, when a photo is loaded on Instagram, a user doesn't have to wait for the app to finish loading it to continue.The user can continue in the app or leave the app while the photo loads.

How asynchronous programming works: 
The easiest way to see how asynchronous programming works is to compare it to synchronous programming. And, we’ll use a yummy example.

Synchronous programming:
Synchronous programming follows a strict set of sequences.
When the code runs in a synchronous program, it will follow each step of an algorithm. It does so in order and will wait for the present operation to finish before continuing on to the next. Synchronous programming follows a “Bake a cake” algorithm. Measure the ingredients.
Mix flour, eggs, and sugar. Heat oven and bake. Eat. Each step must happen in order. The ingredients must be measured, mix must be mixed, before the mix is baked. And, to taste like a cake, it should be baked before it is eaten. Because only one person is doing all the work, you must complete one task fully before starting the next.

Synchronous programming has a one-track mind. It follows the guide step by step. Asynchronous programming Asynchronouses cake baking, by contrast, allows multiple people to be working on the task at once. One person can gather and measure the ingredients while another person begins mixing the ingredients together.
Asynchronous programming allows multiple processes to be started, let the processes do their work, and when their job is finished, it gets the result and puts it through the steps. If the oven finishes heating before the cake mix is fully prepared, asynchronous programming says that is okay.
Synchronous programming would never have started the oven without the mix having been prepared. When the mix is completed, it sends an update to the algorithm to come back and pick up the result of the mix and push it through the process. Now, when the cake mix is prepared, it can be passed into a heated oven that is already heated to the right temperature, ready to bake the cake.
Unfortunately, asynchronous programming won’t help you eat your cake, but it will help get the cake down the line faster. The baking must still happen before you can eat it. (And, if the eater is called to eat before the cake is ready, like how the oven was heating before the cake mix was ready, the one eating can pace the kitchen hungrily.) 

Asynchronous functions:
 Asynchronous functions are often found in front end applications and used particularly in independent, high volume, IO tasks.
Front end applications benefit from its use because it enhances the flow of an application. Backend processes may use asynchronous functions to run many tasks or make lots of network calls. In the backend, asynchronous programming allows the computer to do more, faster. It calls a lot of functions whose response times are indefinite and processing the results.
An example is web scraping, then storing the result in a database: the process is routine, and it doesn’t matter what order the results get written to the directory—they just need to have a file name. Asynchronous programming exists in: Java, JavaScript, Typescript, Dart.
The most common use of the asynchronous function is to make a call to an API. Because network times and retrievals are uncertain, asynchronous functions say, “Get me the data from a website (or REST API), and when it gets here, insert that fetched data back into my script.” Async functions are used to: Interact with an API, Slow down an application’s UX. They can also be used to create delays in a user’s activity.
Why would you want to slow down an app? Because computers can do things incredibly fast, and, when executed, it is jarring to a user. So, designers intentionally slow down the application. A message can be sent almost instantly to another user. Often, the loading circle is not a necessary circle saying the message is taking time to send.
Instead, it’s there because it helps a user understand what is going on and feel more comfortable using the app. Yes, sometimes it takes a message a couple seconds to send because of network delays. Encoding a message will also take a little bit of time to happen on a user’s device before it is sent over a network.
Items on the screen can appear and disappear instantly, and it is through animations that helps a user follow what is happening on the screen. Animations can be asynchronous because, while they perform their operation over a period of time, other functions can be operating in the background.

When to use asynchronous functions:
 Asynchronous is not always the best way to go. Asynchronous programs add more complexity and make the code more unreadable. Young programmers will often use async functions too much because they think it acts as a safeguard to ensure their code works at run-time. A general rule for when to use async functions: 
Good for: Tasks that may take a while; high iteration. 
Bad for: Simplicity.
