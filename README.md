# tanaJs
Less code javascript library

tanaJs is a small library for building easy web sites for all kind of developers from beginners to seniors 
and for developing across all platforms.
Its purpose is to reduce javascript code and simplify coding.

# examples

### 1. Bind string 
```javascript
var myWorld = 'world';
```
```html
<div style="display:none" clientSource="myWorld">
    <div>           
     <span>Hello </span> {{myWorld}}
    </div> 
 </div>

```

### result

Hello world

sample in jsfiddle : http://jsfiddle.net/jbaLn3ko/

### 2. Bind object
```javascript
 var Person = {
            Id: 123456789,
            Name: "David King",
            Addres:"New York"
        }
```
```html
<div style="display:none" clientSource="Person">       
         <div>Id: {{Id}} </div>
         <div>Name: {{Name}}</div>  
         <div>Addres: {{Addres}}</div>  
   </div>

```
### result 
Id: 123456789

Name: David King

Addres: New York


### 3. Bind list objects
```javascript
 var Persons = [{
            Id: 123456789,
            Name: "David King",
            Addres:"New York"
        },
            {
                Id: 987654321,
                Name: "Jhon doe",
                Addres: "Tel Aviv"
            }
        ]
```
```html
<div style="display:none" clientSource="Persons">              
         <div style="padding-top:10px">
             <span>Id: {{Id}} </span>
             <span>Name: {{Name}}</span>    
             <span>Addres: {{Addres}}</span>       
         </div>
   </div>

```

### result 

Id: 123456789 Name: David King Addres: New York

Id: 987654321 Name: Jhon doe Addres: Tel Aviv


