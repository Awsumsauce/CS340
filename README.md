# CS340
# Module 8 Journal

1. How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

   When I write my programs, I try to do it in a way that keeps things organized and easy to understand. One of the best examples of this was my CRUD Python Module. Instead of just putting all of the
   code for the database directly inside the dashboard project itself, a separate "CRUD_Python_Module.py" file was used that handled all of the database actions such as create, read, update, and delete.

   Doing this made my projects a lot easier to manage because each part had a clear job. The CRUD file handled talking to the database, and the dashboard file is what handled displaying the data.
   If something needed to be changed in the database connection, this meant I only had to update one thing. Doing this made my code easier to read, fix, and reuse. In the future, I could then
   use the same CRUD file in another project that connects to MongoDB without having to rewrite that section again.

2. How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

   Whenever I approach a problem, I try to understand what is being asked. Then, I find it easier to break that problem into smaller parts. For Project Two, I thought about three major things: how to get the data,
   how to show the data, and how will everything work when the user interacts with it. This project was different from other projects in different courses because it involved multiple pieces working together.
   I had to make sure the database, the dashboard, and the user interface all worked correctly at the same time.

   I also learned the importance of testing edge cases, such as handling empty inputs and certain dashboard features not syncing after filters were changed. These are important things that need to be considered with
   a user in mind. In the future, I will spend more time testing different user actions and scenarios so my programs are more stable and user friendly.

3. What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

   My definition of a computer scientist is someone who builds systems that help people use data in a useful way. In the project, I completed a dashboard that allows the users to filter animals, visualize the data,
   and view the animals location on a map. Instead of having to search through all of the raw data, the user can quickly find what they need. This kind of work matters because companies vastly rely on data to
   help them make decisions. A tool like this helps an organization to save time and to work more efficiently. For a company like Grazioso Salvare, this could mean finding the right rescue animal a lot faster.
   Overall, computer scientists help turn information into tools that people can easily use.
