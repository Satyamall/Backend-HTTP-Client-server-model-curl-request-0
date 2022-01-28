
### Curl Command for Curl request-0

-curl google.com

-curl -I google.com (-I represent header)

-curl -o google1.txt -I google.com (Print the header of google.com)

-curl https://www.google.com 

-curl -I https://www.google.com 

-curl -o google2.txt -I https://www.google.com  (Print the header)

-curl -L masaischool.com (make a curl request with redirect enabled for masaischool.com)

-curl -L -I masaischool.com (make a curl request with redirect enabled for masaischool.com for header)

-curl -o masaischool.txt -L -I masaischool.com (make a curl request with redirect enabled for masaischool.com and print headers)