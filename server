var express = require('express');
var app= express(); 

var CustomerControl=function (req,res)
{
console.log("invoking rest apis for customer ac info");
var Customer=[ 
{ac id:1 , ac name: "mr. abc " ac balance: 90000 ac holder  address : "abc villa"}
{ac id:1 , ac name: "mr. abc2 " ac balance: 40000 ac holder  address : "abc34 villa"}
{ac id:1 , ac name: "mr. abc3 " ac balance: 540000 ac holder  address : "abc344 villa"}
{ac id:1 , ac name: "mr. abc4 " ac balance: 6890000 ac holder  address : "abc45 villa"}

];
res.send(Customer)

};

app.get('/Customer', CustomerControl);

var server = app.listen(8087, function () {
  console.log("Example app listening at http://localhost:8087")
})

