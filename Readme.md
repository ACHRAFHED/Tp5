# Angular - Json Server web application

this is a simple web application that uses Angular and Json Server to create a simple web application that can be used to create, read, update and delete data from a json file.


## Installation

clone the repository and run the following commands:

```bash
npm install
```

make sure you have json-server installed globally, if not run the following command:

```bash
npm install -g json-server
```

## Usage

1- make sure you have data/db.json file in the root directory of the project, if not create one and add the necessary data.

2- to run the application, run first the json-server using the following command:

```bash
json-server --watch data/db.json --port 8080
```

3- then run the angular application using the following command:

```bash
ng serve
```

4- open your browser and go to http://localhost:4200/ to see the application running.
## screenshots

the first screenshot shows the login page, where the user can login using his username and password.

<img width="960" alt="admin_co" src="https://github.com/ACHRAFHED/Tp5/assets/102471232/a7583f0d-d7bd-45a1-9401-7b9ab525cb02">

the second screenshot shows the home page, where the user can see the navigation bar and the logout button next to its username.

<img width="473" alt="admin_dp" src="https://github.com/ACHRAFHED/Tp5/assets/102471232/064e9d80-4d82-49cd-97bf-c19d619e2140">

the third screenshot shows the products page, where the user can see the list of products and search for a specific product using the search bar.

<img width="472" alt="admin_lp" src="https://github.com/ACHRAFHED/Tp5/assets/102471232/43659b0b-95f8-45bb-9281-b2978b61055b">

the third screenshot shows the products page, where the user can  create a new product.

<img width="960" alt="admin_np" src="https://github.com/ACHRAFHED/Tp5/assets/102471232/164f7e95-01e3-47f7-8925-b9339096372e">

the next screenshot shows that for an admin user, the add product component is available and he can add a product to the list of products.

<img width="960" alt="new_p_user" src="https://github.com/ACHRAFHED/Tp5/assets/102471232/ae258175-3638-4f00-9d80-dc44a4860294">

the last screenshot shows the products page, where the user can see the list of products and search for a phone using the search bar.

<img width="960" alt="search_app" src="https://github.com/ACHRAFHED/Tp5/assets/102471232/b0868265-870f-4453-9fb3-fc7e6c53526c">










