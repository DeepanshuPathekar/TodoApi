<h1 align="center">Flask API using JWT</h1>

<p align="center">Made with ❤️ using python </p>

This project is made using `RESTFul API in Flask` with `JWT` and `Flask-SQLAlchemey` for authentication and authorization and testing is done using Postman. To show the working example of this project I have added the `TODO` route so if the user is authorized then he can create his todo list.

## :wrench: How to Install

`git clone https://github.com/DeepanshuPathekar/TodoApi` <br>
`pip install -r requirement.txt`

## :memo: Working

1.Using a login route the user can generate the **JWT** token which is signed by using a secret key and using that token in his header user can get access to all the info based on wheather user is admin or not.

![alt text](/images/token.JPG)

2.Once the user add that token to header using **x-access-token** as key if user is authorized then the user can see the info (here I have generated the token for the admin so we are able to see all the info).

![alt text](/images/all_user.JPG)

3.This is how we can also perform all the other CRUD operation like **PUT** , **POST** , **DELETE** .

## :bookmark: Todo route

Using todo route user can easily make his todo list and it is safe from the malicous user as no unauthorized user can view another user's todo list.

![alt text](/images/todo_route.JPG)

