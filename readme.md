
### Curl Command for Curl request-0
```js
curl google.com
```
```js
curl -I google.com (-I represent header)
```
```js
curl -o google1.txt -I google.com (Print the header of google.com)
```
```js
curl https://www.google.com 
```
```js
curl -I https://www.google.com 
```
```js
curl -o google2.txt -I https://www.google.com  (Print the header)
```
```js
curl -L masaischool.com (make a curl request with redirect enabled for masaischool.com)
```
```js
curl -L -I masaischool.com (make a curl request with redirect enabled for masaischool.com for header)
```
```js
curl -o masaischool.txt -L -I masaischool.com (make a curl request with redirect enabled for masaischool.com and print headers)
```
