# News letter sign

## Install

'''
npm init
npm i express nodemon body-parser request

'''

## Install

'''
nodemon app.js
'''

## Create myAPIkeys.js

Add following data with own mailchimp API code https://mailchimp.com/
'''
const mailchimp = "";

//myAPIkeys.js
module.exports = {
    exportMailchimpAPI: ()=> {
        return mailchimp;
    }
}
'''