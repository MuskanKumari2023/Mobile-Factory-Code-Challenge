
# Mobile Factory Code Challenge


This is a backend project involving API.


## Description

Being a beginner,This project was a bit hard for me but I did not give up and put in my best effort possible.To begin with the project,firstly I read the problem statement carefully and marked the important information,edge cases,input-output and the things which I was expected to do.I have knowledge of Javascript,node.js and express.js hence I decided to implement the backend in respective language.Alongside,for building API and establishing server,I used POSTMAN which is very user friendly.I used hyper terminal to setup and start the server.


## Steps I followed

I created a folder"backend task" to get started with the project.I opened hyper and headed over to backend task directory.I created a basic app.js file by "tocuh app.js" and a config.json file to store the given data locally in json format.I stored the datasets provided in problem statement as object of arrays in config.json file.I used VSCode as code editor.I opened my project folder in VSCode.I initialized npm by npm init command in hyper.After this installed express and bodyParser by "npm i express body-parser"command.Now I was ready to write the code and put in my logic.In the process I also made an object of array as config.json to store data locally.I then headed over by importing express and body-parser.Afterward,I setup a server to listen at port 8004 and initialized nodemon to start the live server.I had to access the data from config.json file and for that I used "fs" node module to extract the data.I used "fs.readFilesync" to read data and saved it in json format by parsing it to JSON.Further,I set up post request at "/order" route and wrote logic of my code.After that I headed over to postman and entered the url of my server as "http://localhost:8004/order?" and queried the key value pair.I extracted those query put by user and stored them into variables:"screen","os","camera","port","body".I also set a boolean status as false to handle the edge case that all query parameters should be unique.I initialized a total_price variable as well to store total price.Then,I checked the queries by if else statement and added their prices if it was available otherwise I had also initialized a var as missing part if query parameter was not found and accordingly set the value of status as true.After implementing all the logic,I created an object as "user_order" and put in all the things to be dispalayed when post request made.Finally set the status code as 201 to reflect that everything is ok and send it.I also added a default catch err to handle any kind of unwanted error. In postman,I put the localhost url and queried key value pair and set it to post type.I finally send the file and got output in JSON format beautifully formated.This what I did to post output by implementing API. 


## 🚀 About Me
I am Software Engineer enthusiast and I find fun in programming and learning new technologies.


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://muskankumari2023.github.io/Decorated-Personal-Site/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](linkedin.com/in/muskan-kumari-4a0090207)



## 🛠 Skills
Javascript, HTML, CSS , C,C++,Python,Node.js,Express.js


## Lessons Learned

Since I was an absolute beginner,It was a bit challenging for me.I took it as a challenge and learned things from google and Youtube and implemented it.I found that nothing is impossible and all we have to do is search concepts on google and implemet it.


## Tech Stack



**Server:** Node, Express

