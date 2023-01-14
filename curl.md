# Curl

## Curl is a tool that you can use for HTTP requests from the command line. You can find more detailed information on curl's original webpage, Windows 11 ships with copy of curl application you can start using it with out installing anything

[Curl documentation](https://curl.se/)

- curl --location --request GET URL --header 'Content-Type: application/json'
  
- curl --location --request POST URL --header 'Content-Type: application/json' --data-raw '{""}'

- Example
- Open command line
  - GET REQUEST
    - curl --location --request GET https://www.google.com --header 'Content-Type: application/json'

  - POST
    - curl --location --request POST https://jsonplaceholder.typicode.com/posts --header 'Content-Type: application/json;charset=UTF-8'
