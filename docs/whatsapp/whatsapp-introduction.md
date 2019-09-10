---
title: "Introduction"
excerpt: "WhatsApp for Bussiness messaging"
---

The Sinch WhatsApp Business Messaging API provides a rich, enterprise grade messaging solution for clients who wish to communicate with their customers via WhatsApp.

With over 1.5bn users globally using WhatsApp regularly to communicate with friends and family, it really does represent the digital extension of the users living room. It’s the inner circle of your customer’s communication so bringing your trusted brand communications to that inner circle has huge potential.

Integrating the Sinch WhatsApp Business Messaging API with your own backend systems enables Rich, High fidelity, contextual conversations to be established via the WhatsApp channel.

This API specification covers the range of features available.

> **Note**
>
> Try out the WhatsApp API live in our new tutorial here [WhatsApp Tutorial](doc:whatsapp-message#send-a-whatsapp-message).

## Authentication
The Sinch WhatsApp API securely authenticates via a bot identifier and bearer token pair. During the initial client on boarding process, these will be provided by your account manager.

To be able to authenticate the access token needs to be passed. For all WhatsApp end-points it is required to set the [bearer token](https://oauth.net/2/bearer-tokens/) in the authorization HTTP header like: `Authorization: Bearer AbCdEf123456`. Where the string `"AbCdEf123456"` is the bearer authorization token.

## BearerAuth

|---|---|
|Security scheme type:|HTTP|
|HTTP Authorization Scheme|bearer|

## Base URL

> **Note**
>
> We recently added support for a EU server. We are currently working to add a production server in Asia, so stay tuned!

The following WhatsApp URLs can be used by the WhatsApp API. We have servers in the US and EU.


| Server        |  URL                                   |
|---------------|----------------------------------------|
| US Production | https://us1\.whatsapp\.api\.sinch\.com |
| EU Production | https://eu1\.whatsapp\.api\.sinch\.com |