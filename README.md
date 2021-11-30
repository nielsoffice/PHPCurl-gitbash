# PHPCurl-gitbash
PHPCurl on gitbush

REST API Using CURL

Run git bash

curl + URL then hit enter

ex. 
curl https://jsonplaceholder.typicode.com/posts

curl -i + URL display the content type such as 

> content-type: application/json; charset=utf-8
> content-length: 278

ex. 
curl -i https://jsonplaceholder.typicode.com/posts/8

OR

curl --head https://jsonplaceholder.typicode.com/posts/8

OR
 
curl -I https://jsonplaceholder.typicode.com/posts/8

Create file with current REST URL
Go to directory project

Then

curl -o filename.filetype + URL then hit enter

ex

curl -o text.txt https://jsonplaceholder.typicode.com/posts/

Read file on commandline run bash
Go to directory project

cat text.txt

Download file with current REST URL
Go to directory project

Then

curl -O filename.filetype + URL then hit enter (capital O to -O)


curl -O https://jsonplaceholder.typicode.com/posts/
curl -O https://jsonplaceholder.typicode.com/mockend.svg


CURL Update REST API Using PUT

curl -X PUT title="Hello" + URL/id

ex.
curl -X PUT title="Hello" https://jsonplaceholder.typicode.com/posts/8

curl -X DELETE https://jsonplaceholder.typicode.com/posts/8


Secure route Authetication: 

curl -u username:password + URL
ex.

curl -u niel:123 https://jsonplaceholder.typicode.com/posts/8
curl -u niel:123 -O https://jsonplaceholder.typicode.com/mockend.svg
curl -u niel:123 --head https://jsonplaceholder.typicode.com/posts/8
