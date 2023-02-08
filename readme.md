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
https://support.exitbee.com/email-marketing-crm-integrations/how-to-find-your-mailchimp-list-id
'''
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
'''