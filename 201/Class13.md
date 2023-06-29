# Introduction to Persistence with Local Storage

## Readings
[Local Storage](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)   
[Past present and future of LS](http://diveinto.html5doctor.com/storage.html)

## Q&A
1. Why would a developer use local storage for a web application?
> Can be used to Cach data and can be used to store something most current state. eg User selected Dark/Light mode when last on the site to the apply when they come back
2. What information should not be stored in local storage?
> anything that needs to be secure. eg Passwords, Names, Addresses, phonenumbers etc
3. Local storage can store what type of data? How would you convert it to that type before storing?
> LS saves ALL data as Strings. in a .js file you will need to use JSON.parse() to convert the string data back to something useable. you also need to covert data TO a string before it can be saved with JSON.stringify()

## Useful links
[API localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
[JSON Intro](https://www.w3schools.com/js/js_json_intro.asp)
