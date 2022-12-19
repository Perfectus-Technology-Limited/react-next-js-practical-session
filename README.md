# Building real world nextjs basic auth application

In this project, we will be building a React application where users can perform the following tasks:

- Register to the application by providing their `name`, `email`, and `password`.
- Log in to the application by providing their `email` and `password`.
- Be redirected to the `/dashboard` page after successful authentication.

The focus of this project is to learn basic real-world use cases in a practical manner. Therefore, we will be using a backend server with an authentication endpoint built using the Nest.js framework. You can find the repository [HERE](https://github.com/theetaz/simple-auth) for the backend service. The backend service is deployed on an AWS server, and you can find the complete Postman collection HERE for the backend auth service.

`BASE_URL=https://ujkp2xeahs.us-east-1.awsapprunner.com`

Link to postman collection [Here](https://www.getpostman.com/collections/b43dc97f487af89db05b)

## Important Notes
- Use the latest version of Next.js with TypeScript to build this frontend application.
- Use Redux to manage the state of the application.
- Create 3 page routes with the following naming conventions:
  - `/auth/register` -> Register user page.
  - `/auth/login` -> Login page.
  - `/dashboard` -> Protected route, only logged-in users can see this page. Add the logged-in user's name to this page along with a logout button.
- You can use any CSS or UI framework to build this application.
You have complete freedom over the UI design (a responsive, sleek design would be great ;D).
- After completing the project, upload it to your personal GitHub repository and share the URL with us.
- We expect basic error handling and UX flow as we are frontend developers.
- Please use the API we have deployed on our servers as the auth API. The base_url and Postman collection have been provided in the readme file."
