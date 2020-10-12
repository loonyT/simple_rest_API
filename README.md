<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Usage](#usage)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project : building a basic rest API

Representational state transfer (architectural programming convention ) application programming interface stands for REST API. A REST API is a way for two computer systems to communicate over HTTP in a similar way to web browsers and servers.

[Exemple of a restAPI](https://official-joke-api.appspot.com/jokes/programming/random)


What Does REST exactely means ? 

1. Client-Server. SystemA makes an HTTP request to a URL hosted by SystemB, which returns a response.

2. It’s identical to how a browser works. The application makes a request for a specific URL. The request is routed to a web server that returns an HTML page. That page may contain references to images, style sheets, and JavaScript, which incur further requests and responses.

3. Stateless. REST is stateless: the client request should contain all the information necessary to respond to a request. In other words, it should be possible to make two or more HTTP requests in any order and the same responses will be received.

4. Cacheable. A response should be defined as cacheable or not.

5. Layered. The requesting client need not know whether it’s communicating with the actual server, a proxy, or any other intermediary.

What does an API rest request contains ? 

1. An endpoint URL
2. The HTTP method (get, post, put, delete) 
3. The HTTP headers (authentications tokens, cookies, ...) 
4. Datas ( often in json) 


What is a REST API response ? 

1. Datas, files, status codes ( 201 , 404 , ) 

What about REST API security ? 

1. CORS correctly implemented
2. HTTP basic authentication 
3. API keys 
4. OAuth tokens
5. JSON web tokens
6. HTTPS 


[Good french definition of what exactely REST means](https://www.redhat.com/fr/topics/api/what-is-a-rest-api)



### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Bootstrap](https://getbootstrap.com)
* [NodeJS](https://nodejs.org/en/)
* [Express](https://expressjs.com/fr/starter/installing.html)
* [MongoDB](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_emea_belgium_search_brand_atlas_desktop&utm_term=mongodb%20download&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=1718986528&gclid=Cj0KCQjwk8b7BRCaARIsAARRTL7Lojhq2tb8h2R7-O5fol5NHUN4nDBq77OUQuw7SK0Z8oR__GrvcVkaAqTLEALw_wcB)


<!-- USAGE EXAMPLES -->
## Usage

Relevant tools to be used : 

1. [Swagger](https://swagger.io/)
2. [POSTMAN](https://www.postman.com/downloads/)


Relevant restAPI's to be used : 

1. [Google API explorer](https://developers.google.com/apis-explorer/)
2. [Any API](https://any-api.com/)
3. [API list](https://apilist.fun/)


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

1. [contributors-url](https://github.com/othneildrew/Best-README-Template/graphs/contributors)
2. [forks-url](https://github.com/othneildrew/Best-README-Template/network/members)
3. [license-url](https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt)
4. [linkedin-url](https://linkedin.com/in/othneildrew)
5. [Source](https://www.sitepoint.com/developers-rest-api/)


