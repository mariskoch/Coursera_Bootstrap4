# Front-End Web UI Frameworks and Tools: Bootstrap 4 - Assignment I

This documentation is related to the week 1 assignment in the Coursera course
[Front-End Web UI Frameworks and Tools: Bootstrap 4](https://www.coursera.org/learn/bootstrap-4).

This course is part of the Coursera course set
[Full Stack Web Development with Angular](https://www.coursera.org/specializations/full-stack-mobile-app-development).

### Assignment I

This is small documentation about the first assignment.

The task was to style the html page `aboutus.html` according to the specifications given in the task.
Bootstrap 4 was supposed to be used to create a responsive design.
The task can be
found [here](https://www.coursera.org/learn/bootstrap-4/peer/e9axj/assignment-1-bootstrap-and-responsive-design).

### lite-server

This project uses Node.js. To start the lite-server for development, execute: `npm start`. This runs the start script
specified
in
`package.json`. The start script starts the lite-server.

The server can then be reached under `http://localhost:3000/aboutus.html` unless specified differently in the
configuration of the lite-server.

> lite-server uses BrowserSync, and allows for configuration overrides via a local `bs-config.json` file in your
> project.

According to the [lite-server documentation](https://www.npmjs.com/package/lite-server), there is a config file for the
lite-server. It is located at `./configs/bs-config.json`.