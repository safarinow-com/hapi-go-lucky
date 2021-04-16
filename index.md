# Welcome to HAPI

## API Docs (Swagger)
[Swagger API](http://20.54.181.220/index.html)
or
[Redoc API](http://20.54.181.220/api-docs/index.html)

## Try it with Postman here

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/a3d6df08d905d6972688?action=collection%2Fimport#?env%5BStaging%5D=W3sia2V5IjoiaG9zdCIsInZhbHVlIjoiaHR0cHM6Ly9zdGFnaW5nLnNhZmFyaW5vdy5jb20vIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJoYXBpaG9zdCIsInZhbHVlIjoiaHR0cDovLzIwLjU0LjE4MS4yMjAiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6InN0ZHVzZXJ0b2tlbiIsInZhbHVlIjoiZXlKaGJHY2lPaUpJVXpJMU5pSXNJblI1Y0NJNklrcFhWQ0o5LmV5SjFibWx4ZFdWZmJtRnRaU0k2SWpWbU9ERXdPVFEyTFRKbU5qQXRORFU1WlMwNVptTTBMV0U1WldRM01qVmlOR05pT1NJc0ltNWlaaUk2TVRZeE5qYzJOekl3T1N3aVpYaHdJam94TmpFM01URXlPREE1TENKcFlYUWlPakUyTVRZM05qY3lNRGw5Llh3VDUxTXRJRmR5TXZuSmJjSGhBaTNhN2dxek1LOHdqM0pMMFhpcDZaa2MiLCJlbmFibGVkIjp0cnVlfV0=)

Register a new user first and generate an Auth Token. Apply this as an Authorization Header:
```js
{ Authorization : "Bearer [yourtokengoeshere]" }
```

## Overview

HAPI provides an accommodation API with three simple end points Search, Book and Cancel.

## Testing Phase: 
All end point produce as close to live data as we can but don't worry they are in staging mode and no live bookings are made.


## Data Providers
- Safarinow.com
- Booking.com
- Expedia.com
- Hotelbeds.com

# Coming Soon:
* [ ] Nightsbridge
* [ ] Siteminder
* [ ] RoomRacoon
* [ ] Eres
* [ ] HConnect


## Build Status
![Docker](https://github.com/safarinow-com/HAPI/workflows/Docker/badge.svg?branch=main)
![Unit Tests (UCs)](https://github.com/safarinow-com/HAPI/workflows/RunUseCaseTestsWF/badge.svg)
[![Build Status](https://dev.azure.com/SafariNowCollection/SafariNow/_apis/build/status/HAPI%20Tag%20n%20Deploy%20-%20STAGE?branchName=main)](https://dev.azure.com/SafariNowCollection/SafariNow/_build/latest?definitionId=162&branchName=main)
