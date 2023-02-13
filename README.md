# Getting Started with Create React App
I have maded JWT tokens for the API and also checked the edge cases of the application.I also dockerized this application.

#### website Link    :          https://spritle-y4mi.onrender.com <br>
#### API Link        :          https://spritleapi.onrender.com<br>
#### Video Link      :          https://drive.google.com/file/d/15G_p8SLwwWFwToPq0d_LtFZDpWSXJIuE/view?usp=share_link<br>
#### Docker FrontEnd :          docker pull rameshkannan0078/spritle:tagname<br>
#### Docker BackEnd  :          docker pull rameshkannan0078/spritle_backend:tagname

# Getting Started with Docker

1.)Pull the FrontEnd from Dockerhub

###  docker pull rameshkannan0078/spritle:tagname<br>

2.)Pull the backend from DOckerhub

###  docker pull rameshkannan0078/spritle_backend:tagname

3.)Run the Front End Using

docker run -d -p 3000:3000 --name spritle rameshkannan0078/spritle:tagname


4.)Run the Backend End Using

docker run -d -p 3001:3001 --name spritle_backend rameshkannan0078/spritle_backend:tagname

# Getting Started with Nodejs

1.)Make the path of frontend in cmd.
### npm install
It will install all the packages of frontend

http://localhost:3000

2.)Make the path of Backend in cmd.

### node index.js

It will install all the packages of backend

http://localhost:3001
 ##### Make both are running simultaneosuly
