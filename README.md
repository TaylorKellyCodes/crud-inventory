#Rigid Insulation Inventory App

##This is an app that I can use to monitor how much inventory I have for my small business at each of my 3 locations. I sell building supplies and I have business partners that are eager to take over more responsibility. I have a location in Durham NC, Concord NC, and Greensboro NC. This helps me keep the numbers all in the same place and when I choose to let my business partners take over more of the business, it will allow me a more hands-off approach while still being able to check in anytime, anyplace.


Link to project: (Coming soon, researching the best back-end service to use to host.)

Screenshots:

[![Inventory-1.jpg](https://i.postimg.cc/KvP6Ky1J/Inventory-1.jpg)](https://postimg.cc/XpvHhmcC)
[![Inventory-2.jpg](https://i.postimg.cc/K8QCNrrT/Inventory-2.jpg)](https://postimg.cc/LJYy4PW4)
[![Inventory-3.jpg](https://i.postimg.cc/vZGpfS9M/Inventory-3.jpg)](https://postimg.cc/mt6XGj86)

How It's Made:

Tech used: JavaScript, Node.js, MongoDB, Cloudinary, Multer, Passport for authentication, bcrypt, MVC Architecture, Bootstrap, HTML, and CSS.

This is a CRUD application with full Create, Read, Update, and Delete capabilities. You can make an account with any username and password and it will save them to your computer. This ensures you can stay logged in if you exit out of the window and come back to the application.

The /profile page shows all of the locations and gives you the ability to create a new location. I made this because I am in talks with individuals in Wilmington NC as well as Fayetteville NC and expect to have locations there soon.

If you click on the picture of a location, you are taken to a /post page with a unique id created by MongoDB. This is where the stock of each location is stored. Each transaction will be recorded with a name and either a "-" to reduce the number in stock at a location (for a sale) or a "+" to add to the number in stock at each location (for a shipment received). There is also a delete button on this page that will delete the entire page and remove it from MongoDB. I also added a "like" option with a number counter because it was a fun little addition.

Optimizations

I would like to add different profiles, like an admin profile for me that would allow me to see all locations as well as a "user" profile so they can only see information about the location they are managing. I would also like to add the ability to add pictures when someone adds an update for a sale or shipment received as proof of inventory.

Lessons Learned:

This is my first personal CRUD app, and it won't be my last. I like how flexible it can be based on what you want to do with it. Nothing feels better than writing routes and having them work for the first time. Also, thank goodness for Multer, bcrypt, and Google Passport. I love being able to leverage these middlewares to do more work and since I have access to these free tools, I was able to save a lot of time.

How to run:

Bring up the terminal and navigate to the folder containing the project then open in a code editor like VS Code. Then, enter:

`npm install`

then

`npm start`

Then

go to localhost:2121 in your browser.
