# exchange_api
A simple endpoint to fetch exchange rates. Base curreny is EUR.


Endpoint: http://exchange.kanju.dev/v1/latest


How to use it:

Send a simple GET request to: http://exchange.kanju.dev/v1/latest

Example response:



    "result": "success",

    "base_code": "EUR",

    "rates": {

        "EUR": 1,

        "USD": 1.0887802286220725,

        "EUR_TO_USD": 0.918459,

        "CNY": 7.837292682634717,

        "EMP_EUR": 0.5597448101378504,

        "EMP_USD": 0.6142808

    }
