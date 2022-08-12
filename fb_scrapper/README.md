# Facebook page SCRAPER with Selenium,  FastAPI, MongoDB as a database, Docker Compose for deployment 
## How to start the application

**The commands:**

First you have to git clone the files by entering in your terminal:
```
$ git clone https://github.com/naouresboufaied/Facebook_scapper.git
```  
to start the application:
```
$ docker-compose up -d
```
To create the images and start the containers (2 images and 2 containers - 
one for the FastAPI application and one for the MongoDB database).

For starting the scraper, open up your browser and enter:

* http://127.0.0.1/

To view all the scraped pages, enter :

* http://127.0.0.1/list
