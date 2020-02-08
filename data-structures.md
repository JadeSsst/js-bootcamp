### The Coding Train - What is an array?
Array is een verzameling van meerdere dingen  
voorbeeld: var grades = [1, 2, 3, 4, 5]  
De volgorde van array is belangrijk, ze hebben een index. er wordt geteld vanaf 0 ipv 1

.length kan je de lengte van je array ophalen

### The Coding Train - JavaScript Objects
Objecten gebruik je bijvoobeeld als meerdere variablen samen horen. je kan ze dan soort van groeperen

voorbeeld  
var circle {  
   x: 0;  
   y: 100;  
   diameter: 50;  
}  
(dit zijn dus eigenlijk 3 variablen, maar ze het objecten)    
Object {  
  [key]: value  
}  

je pakt iets uit de var circle door te doen: circle.x

### Eloquent JavaScript - Data
dit hoofdstuk gaat over objects and arrays.  
Je kunt een array in ee ojbect hebben.  
- .push --> voegt dingen toe als laatste element van de array: students.push({name: "piet"}), dan heb je piet toegevoegd aan de array  
- .shift --> de eerste weghalen  
- .unshift --> weer iets toevoegen als eerste element van de array

indexOf --> dit is een methode die in de array de gevraagde waarde gaat opzoeken en dan gruggeeft op welke plaats in de array deze waarde staat  
lastIndexOf --> start vanaf het einde ipv het begin

Math object wordt gebruikt om dingen uit te rekenen. math.random() bijv, math.floor() --> pakt een heel getal

JSON = JavaScript Object Notatione, it is widely used as a data storage and communication format on the Web

