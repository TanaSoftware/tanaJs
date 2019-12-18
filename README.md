# tanaJs
Less code javascript library

tanaJs is a small library for building easy web sites for all kind of developers from beginners to seniors 
and for developing across all platforms.
Its purpose is to reduce javascript code and simplify coding.

# examples

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
## result 

Hello world

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
   </div>

```


