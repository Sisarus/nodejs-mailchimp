# News letter sign

## Install

```
npm init
npm install

```

## Install

```
nodemon app.js
```

## Create myAPIkeys.js

Add following data with own mailchimp API code [Go Mailchimp](https://mailchimp.com/) 

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