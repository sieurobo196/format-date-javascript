# format-date-javascript
1. Introduction

format-date.min.js is library convert date to formate string simple and fast.

2. Syntax

var formatString = formatDate(date,pattern);

- date : Date object
- pattern support: 

•	dd-MM-yyyy

•	dd/MM/yyyy

•	yyyy-MM-dd

•	dd-MM-yyyy

•	dd/MM/yyyy

•	dd-MM-yyyy HH:mm:ss

•	dd-MM-yyyy HH:mm

•	dd/MM/yyyy HH:mm:ss

•	dd/MM/yyyy HH:mm

•	yyyy-MM-dd HH:mm:ss

•	yyyy-MM-dd HH:mm

•	yyyy-MM-dd HH:mm:ss

•	yyyy/MM/dd HH:mm

3. Example

var formatString = formatDate(new Date(), "dd-MM-yyyy"); 

console.log(formatString);

--> 24-10-2018

More example view file demo.html

