# News letter sign

## Install

```
npm init
npm install

```

## Run

```
nodemon app.js
```

## Create myAPIkeys.js

Add following data with own mailchimp API code [Go Mailchimp](https://mailchimp.com/) 

Add myAPIkeys.js file to under main root folder and following data with own API keys;

```
const mailchimp = "";
const mailchimpAudienceListID = "";
const mailchimpDC = "";
//myAPIkeys.js
module.exports = {
    exportMailchimpAPI: ()=> {
        return mailchimp;
    },
    exportMailchimpAudienceListID: ()=>{
        return mailchimpAudienceListID;
    },
    exportMailchimpDC: ()=>{
        return mailchimpDC;
    }
}
```