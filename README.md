This project was bootstrapped with Create React App, and it is literally just one page saying 'Hello World'.
* I have created this simple project as wanted to play around with Jenkins and Docker and understand CI/CD better.
* As a result, I have created a simple Jenkins Pipeline, hosted on AWS EC2 instance and packaged an application with a Docker by creating an image and pushing it to Docker Hub.
* Currently, the pipeline is triggered by a push to master since it is a very simple application. If the app was more complicated, I would aim to create a multibranch pipeline where the build and all necessary tests were kicked off by the creation of a pull request. Only then, after all tests were successful, on push to master, I would deploy to Docker Hub.

<img width="1777" alt="todo-list with task being edited" src="https://user-images.githubusercontent.com/72078274/119966619-67624500-bfa3-11eb-8e41-6e3ced9f913c.png">
