# LL-Shopper
## A LinkedIn Learning course project led by Daniel Khan to introduce various databases for Node.js developers.
>### Setting up the environment
>1. We will use Docker to create local environments for our databases. To set up a MongoDB docker conatiner, type:
> -`$ docker pull mongo`
> -`$ docker run --name mongodb -p 37017:27017 -d mongo`   
>2. Next, to set up a Redis container using Dokcer, type:
> -`$ docker pull redis`
> -`docker run --name redis -p 7373:639 -d redis`
>3. Finally, to set up a MySQL contianer using Docker, type:
> -`$ docker pull mysql`
> -Note, you will have to set up an environment password for your mysql database
> -`$ docker run --name mysql -p 3406:3306 -e MYSQL_ROOT_PASSWORD=[your_password] -d mysql`
### Now that everything is set up, you are ready to use the app. Signing in to different users will create new sessions, with personal baskets and orders.
![Screen Shot 2021-05-09 at 3 10 07 AM](https://user-images.githubusercontent.com/47705904/117563467-103c1500-b074-11eb-8e0b-d2f623538716.png)
![Screen Shot 2021-05-09 at 3 11 17 AM](https://user-images.githubusercontent.com/47705904/117563483-3a8dd280-b074-11eb-8f3e-51fa07f62b5a.png)
**Clicking on a user allows us to log in as them and start a session**
![Screen Shot 2021-05-09 at 3 11 33 AM](https://user-images.githubusercontent.com/47705904/117563488-42e60d80-b074-11eb-8886-ee36b484dfed.png)
![Screen Shot 2021-05-09 at 3 12 25 AM](https://user-images.githubusercontent.com/47705904/117563501-65782680-b074-11eb-9bb2-993e49027847.png)
**Starting a session allows us to add items to a basket and create orders**
![Screen Shot 2021-05-09 at 3 13 29 AM](https://user-images.githubusercontent.com/47705904/117563515-880a3f80-b074-11eb-953d-36b9dda4c164.png)
