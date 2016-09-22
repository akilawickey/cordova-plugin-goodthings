var exec = require('cordova/exec');

function goodthings() { 
 console.log("goodthings.js: is created");
}

goodthings.prototype.showToast = function(aString){
 console.log("goodthings.js: showToast");

 exec(function(result){
     /*alert("OK" + reply);*/
   },
  function(result){
    /*alert("Error" + reply);*/
   },"goodthings",aString,[]);
}

 var goodthings = new goodthings();
 module.exports = goodthings;

