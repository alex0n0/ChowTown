# React Clicker Game [Batman Ver.]

App is a Batman themed memory game requiring you to click on each option only once.

[Click here](https://beanstalk88.herokuapp.com/) for an interactive demo.

![screenshot 1](/public/screenshot1.png)

## Features

- Single page
- Responsive
- Randomised options after each click
- Tracks current score + session high score
- Shake animation after loss

## Getting Started

Begin by cloning the [reactclickergame](https://github.com/alex0n0/reactclickergame) repository, install dependencies and start the React app:

```terminal
git clone https://github.com/alex0n0/reactclickergame.git
cd reactclickergame
npm install
npm startreactapp
```

## Folder Structure

```text
reactclickergame/
├── public/
│   ├── background.jpg <- application background
│   ├── batman-blk.jpg <- clicker button emblem
│   ├── batman.png <- image above background
│   ├── index.html <- index file with bootstrap.min.css link
│   ├── instructionsimage.jpg <- instructions panel background
│   └── logoDC.png <- home link logo
├── src/
│   ├── components/
│   │   ├── imagetile.css
│   │   └── imageTile.js <- image tile component
│   ├── utils/
│   │   └── villains.js <- array of villain details
│   ├── App.css <- styling for app
│   └── App.js <- body of application
├── package-lock.json
├── package.json
└── server.js
```

## Deployment

An express server is included to serve the built project for deployment. To run it locally, build the React application and then start the server:

```terminal
npm run build
npm run start
```

To view the application in the browser:

```terminal
http://localhost:5000
```

## Built With

- React.js
- Animate.css
- Express

## License

This project is MIT licensed. See details [here](https://github.com/alex0n0/reactclickergame/blob/master/LICENSE).
