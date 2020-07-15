## Read: 10 - JS Debugging
- what is debagging?
**Debugging** is the process of finding errors. It involves a process of deduction. 
- what are the 7 different types of errors?
![7-Types of error](Images\errorsType.png)
- you can use TRY, CATCH, FINALLY:
```
response= ' {"deals" : [{"title" : "Farrow and Ball", . . . 'II JSON data
if (response) {
try{
var dealOata = JSON . parse(response);
showContent (dealData);
}cat ch(e) {
var errorMessage = e.name + ' ' + e .me ssage;
console . log(errorMessage);
feed.innerHTML = '<em>Sorry, cou l d not l oad
finally {
II Try to parse JSON
II Show J SON dat a
II Crea t e error msg
II Show devs msg
dea ls' <lem>; II Users msg
var l i nk= document . creat eEl ement('a'); II Add r efresh l i nk
l ink. i nnerHTML = ' <a href="tr y-catch-fi nally.html">rel oad<la>';
f eed.appendChi l d{link); 
}
}
```

**Dibbuging Tips:**
![Dibbuging Tips](Images\DEBUGGINGTIPS.png)