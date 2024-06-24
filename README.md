# Request Header Parser Microservice

## Test Scenario :
- You should provide your own project, not the example URL.
- A request to ```/api/whoami``` should return a JSON object with your ```IP address``` in the __ipaddress__ key.
- A request to ```/api/whoami``` should return a JSON object with your preferred ```language``` in the __language__ key.
- A request to ```/api/whoami``` should return a JSON object with your ```software``` in the __software__ key.

## Sample Output: 
- __{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5",
"software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}__