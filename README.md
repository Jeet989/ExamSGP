# ExamSGP

> ExamSGP is a application which can be used by the faculties to conduct online exams for the students. The application is built using React, Electron, and Node.js. This application is built as a part of the course project for the course Software Group Project-IV. The application has features like creating exams, adding questions, and also directly connecting a google forms link to give the exam. The exam is given on the desktop application which is cross-platform (Windows, Linux, and MacOS). The application also has features like blocking screen sharing once exam has started, unable to switch windows and video proctoring. This type of features helps in preventing cheating during the exam and also helps in maintaining the integrity of the exam.

## Application Preview

[![Application Preview](https://img.youtube.com/vi/73P5Bx3zq_A/0.jpg)](https://www.youtube.com/watch?v=73P5Bx3zq_A)
<br />

## Key Features of the Application

- Create Exams
- Video Proctoring
- Screen Sharing Block
- Switching Windows Block
- Creating Classrooms for Students and much more.

## Tools & Technologies Used

- [![Node.js][Node.js]][Node.js-url]
- [![React][React]][React-url]
- [![Electron][Electron]][Electron-url]
- [![MongoDB][MongoDB]][MongoDB-url]

[Node.js]: https://img.shields.io/static/v1?style=for-the-badge&message=Node.js&color=339933&logo=Node.js&logoColor=FFFFFF&label=
[Node.js-url]: https://nodejs.org/en/
[React]: https://img.shields.io/static/v1?style=for-the-badge&message=React&color=222222&logo=React&logoColor=61DAFB&label=
[React-url]: https://reactjs.org/
[Electron]: https://img.shields.io/static/v1?style=for-the-badge&message=Electron&color=47848F&logo=Electron&logoColor=FFFFFF&label=
[Electron-url]: https://www.electronjs.org/
[MongoDB]: https://img.shields.io/static/v1?style=for-the-badge&message=MongoDB&color=47A248&logo=MongoDB&logoColor=FFFFFF&label=
[MongoDB-url]: https://www.mongodb.com/

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)

### Clone

> Clone this repo to your local machine

```shell
git clone https://github.com/Jeet989/ExamSGP.git
```

### Setup

> Install server npm packages

```shell
cd server && npm install && cd ..
```

> Install website npm packages

```shell
cd client && cd desktop-app && npm install
```

> Install desktop-app npm packages

```shell
cd client && cd web-app && npm install
```

> Start the server

```shell
cd server && npm start
```

> Start the website

```shell
cd client && cd desktop-app && npm start
```

> Start the desktop-app

```shell
cd client && cd web-app && electron .
```
