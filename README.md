# Starting Up docker container

### Prerequisites

    1. Docker

### How to start docker container

```bsh
docker-compose build && docker-compose up
```

# FizzBuzz Challenge Answers

### 1. What was your reasoning behind the tech stack used for this challenge?

The tech stack I chose for this project was **React**, **Flask**, and **MongoDB**.

I chose React because it's a widely recognized frontend framework that allows for fast re-rendering and component re-useability. The main reason was due to the experience and familiarity I have with React.

For the backend, I decided to go with Flask because it is lightweight compared to DJango.

The reason I went with MongoDB is that it's lightweight. There is also no need for a relational database based on the requirements for this project.

### 2. What piece of this challenge did you find the most challenging and why?


For me, the most difficult part of this project was figuring out what tech stack to use and why that is the best choice. Sometimes as developers, we tend to go with a preferred tech stack instead of one which is efficient for the project. I also struggled to get a docker container for the project. I used a ton of resources and a lot of trial and error. I was also having trouble getting my backend to connect to my local database. My mongodb local instance was running on windows and not connecting to WSL. Instead, I had to create a MongoDB database using MongoDB's database service.


### 3. How would you deploy this application for external users to use?


To start off, I would find a free web hosting solution like Vercel and deploy my frontend. I would deploy my MongoDB database using MongoDB Atlas. For my backend, I can also use Vercel but have other options like Heroku. I am not very familiar with hosting a docker container but I believe we can also find a way to host it using the containers created through docker-compose. I would need to look more into this.


### 4. After deploying your code, it seems to have gone viral as the most awesome app ever created in the history of time itself. How would you handle scaling and support your FizzBuzz app?


There are many ways we can handle scaling to support my FizzBuzz app like database optimization, or setting up load balancing.


# Images to showcase app

## Fizz, divisable by 3
![image](https://user-images.githubusercontent.com/86801740/235403736-25fa460f-4e02-4d3a-a617-c85a0a845e4d.png)
## Buzz, divisable by 5
![image](https://user-images.githubusercontent.com/86801740/235403753-66bd9f2a-115b-45dd-b343-54acdcae1f69.png)
## FizzBuz, divisable by 15
![image](https://user-images.githubusercontent.com/86801740/235403767-39d6085c-eff7-4d87-b2bc-1645a25c5449.png)

## Disabled button on no input
![image](https://user-images.githubusercontent.com/86801740/235403799-573c06fd-658d-4b1b-be68-9a76025247e6.png)

## Handle NaN
![image](https://user-images.githubusercontent.com/86801740/235403815-4d80ffd5-a851-4a28-a7db-c6fdf6d52de6.png)


