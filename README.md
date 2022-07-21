# React Solo Project

## Getting Started

We are using "yarn" instead of "npm" in this project.

1. Install yarn. `npm install -g yarn`
2. Install all node modules. `yarn`
3. Boot up the server. `yarn start`

### Hosting (Not necessary in sprint 1)

1. Go to the official Firebase website and set up a project.
2. Enable Firebase Hosting by going into the hosting section under Build dropdown.
3. Inside your repo run the following commands (one at a time):
4. `npm install -g firebase-tools`
5. `firebase login`
6. `firebase init`
7. `firebase deploy`
8. If you run into trouble take a look at: https://www.geeksforgeeks.org/how-to-deploy-react-project-on-firebase/

### Firebase (if you need authentication or a database in your project)

1. If you don't need authentication or a db, you can ignore the 'login', 'firebase' and 'authSlice' files and skip this section.
2. Go to the official Firebase website and set up a project.
3. Enable Firebase Firestore if you need a database or Firestore Authentication if you need user authentication.
4. If you need user authentication, make sure to enable google authentication in the settings.
5. If you used `yarn` to install all dependencies, you shouldn't need to install anything else.
6. Change the name of the '.env.local.example' file to '.env.local' and write your api key and other information (can be found in the settings of your project on the firebase website).
7. The 'Login' component is commented out in 'App.js'. If you don't need it, delete it. If you do need it, move it to the page where you need it.
8. You can import the 'Login' component on the page you want the user to log in. At the moment the logic is set up to support authorization with Google. If you want to add others (email, username and password, github) You will have to implement this on your own.
9. Clicking on the "Continue with Google" button should open a pop-up that logs you in. If this doesn't work, check your firebase keys and if you have google authentication enabled. Once you are logged in, it will automatically update the state in the 'authSlice' reducer with your information (display name, email and access token). If you need any of these, you can get them with a useSelector hook in the component where you need them.
10. You can check if the user is signed in by checking the state of the 'authSlice'. If user is false (empty), the user isn't signed in.
11. You are free to style the buttons or the login component as you see fit. You can (probably a good idea) move the log out button somewhere else, depending on your project. as long as you import all the necessary things and don't change the function/logic, it should work.

### Folder Structure And Advice

1. You can adjust the folder structure if you have other preferances.
2. The "redux" folder contains an example reducer (counter). You can delete this.
3. You can use whichever CSS library you wish, or just plain CSS/SASS (preferably modules).
4. Once you delete the dummy text in App.js, don't forget to also delete the logo.svg (unless you need it for some reason?).
5. Try to write clean code. Follow the DRY (Don't Repeat Yourself) and KISS (Keep It Stupid Simple) principles. If possible, try to follow SOLID principles as well. You should already be familiar and know how to implement the first 2. Read up on SOLID (might be harder to implement).

<!---
*** WHEN YOU ARE UP AND RUNNING, DELETE EVERYTHING ABOVE ME EXCEPT THE VERY TOP LINE. ***
*** RENAME THE TOP LINE WITH YOUR PROJECT NAME. ***
-->

## Sprint Progress

Fill in all the sprints with your objectives for each sprint. Update your progress by checking off the tasks for each sprint.

### Sprint 1

- [ ] [*Fill me in with Sprint 1 milestones*]
- [ ] [*Fill me in with Sprint 1 milestones*]
- [ ] [*Fill me in with Sprint 1 milestones*]
- [ ] [*Fill me in with Sprint 1 milestones*]

### Sprint 2

- [ ] [*Fill me in with Sprint 2 milestones*]
- [ ] [*Fill me in with Sprint 2 milestones*]
- [ ] [*Fill me in with Sprint 2 milestones*]
- [ ] [*Fill me in with Sprint 2 milestones*]

### Sprint 3

- [ ] [*Fill me in with Sprint 3 milestones*]
- [ ] [*Fill me in with Sprint 3 milestones*]
- [ ] [*Fill me in with Sprint 3 milestones*]
- [ ] [*Fill me in with Sprint 3 milestones*]

## Project Overview

### Description

[*Replace me with a description of your project.*]

### Mockups

[*Replace me with mockups*]

| ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png) | ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png) |
| -------------------------------------------------------------------- | -------------------------------------------------------------------- |
| ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png) | ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png) |
