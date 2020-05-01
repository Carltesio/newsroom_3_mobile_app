### Authors
[Emma-Maria Thalen](https://github.com/emtalen)  
[Philip Gaunitz](https://github.com/pgauntiz)  
[Carlos Delgado](https://github.com/Carltesio)  
[Janko Radakovic](https://github.com/MadFarmer101)  
[Lautaro Parra](https://github.com/dernathul) 

## Built with
**Front End:**  Ionic v.0.0.1 | CSS    


## The code   
This mobile app is part of our newsroom challenge and is also our first experience with mobile application.
The functionality provided by the App are a user friendly UI that fetches articles from the same backend as the webpage.The restriction functionality to premium users is also present as well as a snippet to all the articles.
The articles have been created and published from our Admin interface and are stored in our API.  
The master repository for the admin interface, mobile app and API can be found here:
* [API](https://github.com/CraftAcademy/newsroom_3_api.git)
* [Admin](https://github.com/CraftAcademy/newsroom_3_client_admin.git)
* [Mobile](https://github.com/CraftAcademy/newsroom_3_mobile_app.git)

## Getting started
### Dependencies  
* Yarn
* React
* Cypress
* Axios
* Semantic-ui-react / Semantic-ui-css
* React-images-uploading
* React-redux
* Redux
* Redux-thunk
* J-tockauth
* React-i18next
* React-stripe-elements

### Setup   
To test this application, fork the repo to your own GitHub account and clone it to your local workspace. </br>
*Note:**Note:*All our clients are running on our deployed API, even when they are being used on a local server. </br>
Install Ionic command and all of the dependencies to run the project locally:    
```
$ yarn add global @ionic/cli
```  
```
$ yarn install
``` 
Start the React application and run it on your local host:
```
$ ionic serve
```

### Login credentials
- Regular user: email: user@mail.com password: password
- Subscriber: email: subscriber@mail.com password: password

## Updates/Improvements   
- Sign up functionality
- Purchase of a premium account 
- Private profile section 
- Create functionality to comment and rate on articles

## License  
[MIT-license](https://en.wikipedia.org/wiki/MIT_License)

### Acknowledgement  
- Material provided by [Craft Academy](https://craftacademy.se)
- [Oliver Ochman](https://github.com/oliverochman/) for helping us understanding how to send credentials with the headers for request to the API.
- [Faraz Naeem](https://github.com/faraznaeem) for wlaking us to the usage of Ionic in a simple and comprehensive way.
- Big thanks to the others students in our cohort at Craft Academy. We have been stealing some of your code shamelessly, you have been great rubber ducks and our team internal competition in highest coverage has really helped us implement better skills in RSpec. 
