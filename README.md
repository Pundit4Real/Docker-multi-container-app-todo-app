# Multi Containers App

This is a repo for new users getting started with Docker.

This is a simple todo application built using **ExpressJS and Node.**
All todos are saved in a **MongoDB database.**

If you view the code of the sample application, you will notice that it has a compose.yaml file. 
This file tells Docker how to run your application. Open the compose.yaml file in a text editor to explore the instructions.


You can try it out using the following command.

```docker compose up -d```

The **-d** flag tells docker compose to run in detached mode.

And open http://localhost:3000 in your browser.


When developing with Docker, you may need to automatically update and preview your running services as you edit and save your code. We use docker compose watch for this.

Run the following command to run your project with compose watch.

```docker compose watch```

Now change the text in line 18 of the app **app/views/todos.ejs** to see your changes in real time.

Have a look of the original copy of the project on the docker github account
```https://github.com/docker/multi-container-app⁠```