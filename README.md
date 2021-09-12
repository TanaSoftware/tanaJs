# tanaJs
Less code javascript library

tanaJs is a small library for building easy web sites for all kind of developers from beginners to seniors 
and for developing across all platforms.
Its purpose is to reduce javascript code and simplify coding.

# 1. Bind data from javascript objects:

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

sample in jsfiddle : http://jsfiddle.net/brk4pe0y/

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


sample in jsfiddle : http://jsfiddle.net/c8akermh/

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

sample in jsfiddle : http://jsfiddle.net/7Lmrbyeg/

# 2. Bind data from server side:

```html
<div style="display:none" source="user/GetCities">
   <ul>           
     <li>{{Id}} {{Name}}</li>
   </ul> 
</div>
```
### result 

1 New york

2 Tel aviv

sample in website : http://tana.somee.com/Rest.html  (click right mouse to see page source)
