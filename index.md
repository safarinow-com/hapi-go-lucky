# Welcome to HAPI

## API Docs (Swagger)
[Swagger API](http://20.54.181.220/index.html)
or
[Redoc API](http://20.54.181.220/api-docs/index.html)

## First time users
Use the API to register a new user and generate an Auth Token. This will need to be used on all subsequent requests Authorization Header eg.
```js
{ Authorization : "Bearer [yourtokengoeshere]" }
```
Note: Tokens expiration period.

After registering a new user, our administrator will manually activate your account. If its taking too long, email us at: fa3df594.safarinow.com@emea.teams.ms

You try it out now:

### Try it with Postman here

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/a3d6df08d905d6972688?action=collection%2Fimport#?env%5BStaging%5D=W3sia2V5IjoiaG9zdCIsInZhbHVlIjoiaHR0cHM6Ly9zdGFnaW5nLnNhZmFyaW5vdy5jb20vIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJoYXBpaG9zdCIsInZhbHVlIjoiaHR0cDovLzIwLjU0LjE4MS4yMjAiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6InN0ZHVzZXJ0b2tlbiIsInZhbHVlIjoiZXlKaGJHY2lPaUpJVXpJMU5pSXNJblI1Y0NJNklrcFhWQ0o5LmV5SjFibWx4ZFdWZmJtRnRaU0k2SWpWbU9ERXdPVFEyTFRKbU5qQXRORFU1WlMwNVptTTBMV0U1WldRM01qVmlOR05pT1NJc0ltNWlaaUk2TVRZeE5qYzJOekl3T1N3aVpYaHdJam94TmpFM01URXlPREE1TENKcFlYUWlPakUyTVRZM05qY3lNRGw5Llh3VDUxTXRJRmR5TXZuSmJjSGhBaTNhN2dxek1LOHdqM0pMMFhpcDZaa2MiLCJlbmFibGVkIjp0cnVlfV0=)


## Overview

HAPI provides an accommodation API with three simple end points Search, Book and Cancel.

## Testing Phase: 
All end point products are as close to live data as possible but don't worry they are in staging mode and no live bookings are made.


## Data Providers
* [X] Safarinow.com
* [X] Booking.com
* [X] Expedia.com
* [X] Hotelbeds.com

# Coming Soon:
* [ ] Nightsbridge
* [ ] Siteminder
* [ ] RoomRacoon
* [ ] Eres
* [ ] HConnect


# Support
Any queries about the API, strange responses, pricing or content can be sent to one of the following channels
Email: fa3df594.safarinow.com@emea.teams.ms
Find us on TS Slack: #hapi-to-help
