# My Awesome YouTube Channel

Welcome to my YouTube channel! 🎉 In this channel, I share exciting content related to web development. Whether you're interested in Angular, Javascript, or Productivity tips, you'll find something valuable here.
[YouTube Channel](http://youtube.com/@neweraofcoding)

## About Me

I'm Sam, and I'm passionate about product engineering and web development. I create videos that will help you learn web development.

## What You'll Find Here

- **[ Angular ]**: [Learn the fundamentals. I explained everything you need to get started with this JavaScript framework written in TypeScript. It is the web development framework for building the future. works at any scale. Loved by millions. Build for everyone.  open-source framework for building single-page client applications using HTML and TypeScript.]
- **[ Javascript ]**: [JavaScript is a powerful programming language that can add interactivity to a website. JavaScript is easy to learn. It's the foundation of frontend web development.]
- **[ Career Tips ]**: [self-assessment, goal setting, action planning, implementation, and refinement. By following these steps, you can develop a road map for achieving your career goals. Tips to improve your career development. Cultivating a beginner's mindset is a critical part of career growth. critical part of your professional growth.]
- **[ Common Errors ]**: [Mistakes to Avoid in Software Development Projects.]
- **[ Development Tools ]**: [Top Software Development Tools List.]
- **[ Typescript ]**: [TypeScript extends JavaScript by adding types to the language. TypeScript speeds up your development experience by catching errors. TypeScript can help enhance and improve your web development projects.]
- **[ Git & GitHub ]**: [GitHub is where over 100 million developers shape the future of software together. Contribute to the open-source community and manage Git repositories. This practical guide gets you to jump right into using GitHub, learning the basics of Git. Git and GitHub are two of the most essential tools in the world of software development.]
- **[ Video Conferencing Tool ]**: [Unlock the potential of video conferencing software development. Dive into our guide for insights on key features and cost factors.  If you're looking to integrate video communication into your app or planning to build a video streaming/conference app from scratch, create a fully customized audio & video conferencing app.]


### About the app
# Todo App

Hey there! 🙋‍♂️ Welcome to the Todo App project. This is a full-stack app where .NET is used for the backend and Angular for the frontend. Feel free to check it out and suggest improvements! 😄

# What's This Project About? 🤔

Basically, this app lets you keep track of your to-do list. You can add tasks, remove them, and mark them as completed. Pretty simple, right? But I’ve tried to use modern tech stack to build it.


# Tech I Used 💻
*Here are the main technologies I worked with:*

◉ SCSS for styles

◉ JavaScript/TypeScript for the frontend (Angular)

◉ C# for the backend (ASP.NET Core)

◉ HTML for structure

◉ .NET Core 8.0 for backend API


# Code Breakdown 📂

*Here’s how the project is organized:*

**Main Folders:** 

◉ .config: This folder has .NET configuration. There’s a file called dotnet-tools.json, which is used to manage tools like dotnet-ef (for migrations).

◉ Project1: This is the main part! It has the backend and frontend code. Inside, you’ll find:

    ◉ clientapp/: Frontend Angular code lives here.
https://localhost:44465/

    ◉ controllers/: This is where API requests are handled.

    ◉ migrations/: Entity Framework migrations for the database.

    ◉ models/: The C# models for database. 
    configuration folder

    ◉ utilities/: Some helper functions.

    ◉ views/: Razor Views (the UI for backend rendering).
ViewModels
Properties folder
    ◉ wwwroot/: Static files like CSS and images.

**Files inside Project1:**

    ◉ Project1.csproj: This is the C# project file that defines project properties and dependencies.

    ◉ WeatherForecast.cs: This is a sample file I added to test the API. It’s just returning some basic weather forecast data.
https://localhost:44465/weatherforecast  get api
 {
        "date": "2024-11-07T20:13:25.0158859+05:30",
        "temperatureC": -4,
        "temperatureF": 25,
        "summary": "Scorching"
    },

    ◉ appsettings.Development.json & appsettings.json: These files are for storing application settings (like database connection strings). The development one is for when I run the app locally.

    ◉ libman.json: This is for managing front-end libraries. Basically, it’s used by the library manager to handle front-end libraries like jQuery, Bootstrap, etc.

    ◉ openapi.json: This is for API documentation. It’s like a guide to the APIs I built, so you can see all the routes and requests.

    ◉ Readme.md


◉ TestProject1: This is where I’m trying out unit testing with NUnit. It has a basic test in unittest1.cs to check if stuff works.

◉ obj: A bunch of files here are automatically generated when the project builds. You can ignore most of this unless you’re really into build systems.

# How to Run This Project 🚀

**Want to run this on your own machine? Cool, here’s how:**

# What You’ll Need:

◉ .NET 8.0 SDK (You can download it here - https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

◉ Node.js (for the frontend part; grab it here - https://nodejs.org/en)

◉ Visual Studio or Visual Studio Code (up to you)

# Steps to make this work:

1. Clone the repository: 

        git clone https://github.com/your-username/Todo-App.git

2. Go to the project Folder:

        cd Todo-App

3. Install frontend requirements(inside clientapp):

        cd clientapp
        npm install

4. Run the backend part:

        dotnet run

5. Now, run the frontend part:

        ng serve

You have reached the end, Open through your browser and check it out!


# To run the tests i have written:

◉ Want to run the tests I wrote, you can go to the TestProject1 folder and use this command:

-        dotnet test
-        dotnet test TestProject1

This command will run the tests to show if it works or breaks

# How You Can Contribute 🙏

**I’d appreciate any feedback, suggestions, or contributions! If you want to help:**

1. Fork this project.
2. Make changes in your forked repository.
3. Open a pull request through my repository.


# Conclusion

Thank you for exploring this project! This is just the beginning of great applications using .NET 8.0 and Node.js. If you're a beginner or someone experienced, this project aims to provide practical insights into building web APIs and connecting front-end and back-end techs.

Feel free to fork this repository, experiment with the code, and build upon it.

If you have any questions or need further help, feel free to reach out!

  



https://localhost:<port>/swagger/index.html

https://localhost:7054/api/todoItems get
GET /api/todoitems	Get all to-do items	None	Array of to-do items
GET /api/todoitems/{id}	Get an item by ID	None	To-do item
POST /api/todoitems	Add a new item	To-do item	To-do item
{
  "name": "walkhjghj ",
  "isComplete": true
}
PUT /api/todoitems/{id}	Update an existing item  	To-do item	None
{
    "id": 2,
  "name": "walkhjghj ",
  "isComplete": true
}
DELETE /api/todoitems/{id}    	Delete an item    	None	None

https://localhost:7054/home FE of pie shop

whenever there is change in db delete .cs and .designer.cs file and create new migration
Add-Migration MyMigration -context DataContextName
add-migration Initial -context PieShopDbContext 

 dotnet tool update --global dotnet-ef
 dotnet tool install --local dotnet-ef 

update-database -context PieShopDbContext 

  Categories
Pies
Orders
OrderDetails -> OrderLines

open terminal and run these commands-
dotnet build will build using a solution file if one is present (the *.sln file).
dotnet run however requires a project file (*.csproj).
dotnet --version check .net sdk installed or not

https://localhost:7054/Order  GET html


https://localhost:7054/Order/Details?orderId=1 GET html



dotnet new console -o app
cd app
code . # to open project in VSCode

dotnet build

Flow-
create model
data access
controller-data
api

it creates 2 APIs one Is to get all employees list and another one is to get details of particular employee.
http://localhost:52334/api/employee
http://localhost:52334/api/employee/2

learn how to create build and publish this project to use those apis in frontend

### useful commands to run project

### Packages used

## Subscribe and Stay Updated!

Don't miss out on new videos! Subscribe to my channel and hit the notification bell 🔔 to receive updates whenever I upload fresh content. Let's learn, laugh, and explore together!

[!Subscribe to My Channel](http://youtube.com/@neweraofcoding)

## Connect with Me

- **YouTube**: [YouTube Channel Link](http://youtube.com/@neweraofcoding)
- **Facebook**: [Facebook Page Link](https://www.facebook.com/learnangular2plus/)
- **Instagram**: [Instagram Page Link](https://www.instagram.com/angular_development/)

Feel free to reach out, comment on videos, and share your thoughts. I appreciate your support! 🙌

## License

This project is licensed under the MIT License.

---

If you have any questions or need further assistance, feel free to ask! 🚀

##  Steps to contribute and generate PR(pull request)

 ###  clone the repository
clone the forked repository to your system. Go to your GitHub account, open the forked repository, click on the code button and then clone the repository.
If you want to use the terminal, use the following commands after you fork the repository, open the terminal type the given command
```
git clone repo url
```
### create a branch
 create a branch on your local repository to solve a problem.

Terminal commands
```
git checkout -b your_new_branch_name
```   
###   add & commit
add your changes(folder) to that branch.
Make necessary changes and commit those changes. Terminal commands
```
git add .
git commit -m "your-commit-message"
```
### push changes to github
finally, push your local repository to the remote repository compare & submit a pull request

terminal commands
```
git push origin 
```
Go to your repository on GitHub, you'll see a compare & pull request button. Click on that button.

Now submit the pull request.
   
For quick approval of the pull request, reach out to me on the mentioned social media channels.
```bash



 _____ _                 _     __   __            
|_   _| |               | |    \ \ / /            
  | | | |__   __ _ _ __ | | __  \ V /___  _   _   
  | | | '_ \ / _` | '_ \| |/ /   \ // _ \| | | |  
  | | | | | | (_| | | | |   <    | | (_) | |_| |  
  \_/ |_| |_|\__,_|_| |_|_|\_\   \_/\___/ \__,_|  
                                                  
                                                  
______                                            
|  ___|                                           
| |_ ___  _ __                                    
|  _/ _ \| '__|                                   
| || (_) | |                                      
\_| \___/|_|                                      
                                                  
                                                  
______      _               _   _               _ 
| ___ \    (_)             | | | |             | |
| |_/ / ___ _ _ __   __ _  | |_| | ___ _ __ ___| |
| ___ \/ _ \ | '_ \ / _` | |  _  |/ _ \ '__/ _ \ |
| |_/ /  __/ | | | | (_| | | | | |  __/ | |  __/_|
\____/ \___|_|_| |_|\__, | \_| |_/\___|_|  \___(_)
                     __/ |                        
                    |___/                         

 


```
---------
```javascript

if (youEnjoyed) {
 //  (star ⭐ & fork 🍽️) this repository.
 // - Fork this repository by clicking on the fork button at the top of this page. This will create a copy of this repository in your account.
    starThisRepository();
}

```
---------
happy coding fellas!!💕✨
-----------
 


