# Loading 
<details>
<summary> Ver1 </summary>
HTML

```html
<center>
 <div class="loading" >
  <span id="loadingcycle" ></span> 
  <span>L</span> <span>o</span> <span>a</span>
  <span>d</span> <span>i</span> <span>n</span>
  <span>g</span> <span>.</span> <span>.</span>
  <span>.</span>
  </div>
</center>
```
CSS

```css
@import url('https://fonts.googleapis.com/css2?family=Maitree:wght@200&display=swap');

body{
 background-color : var(--bs-dark);
 color : var(--bs-gray-400) ;
 padding : 2% ;
}

input[type="button"]{
 font-family: 'Maitree', serif;
 font-weight: 400 ;
}

.a , .b {
 user-select : none ;
 text-align : right ;
 width : 55px ;
}

.x{
 padding-left : 5px ;
 padding-right : 5px ;
}

.ans , .ans:focus {
 width : 100px ;
 height : 20px ;
 background-color : var(--bs-dark);
 color : var(--bs-gray-400) ;
}

.check_word{
 font-family: 'Maitree', serif;
 font-weight: 200 ;
}

@keyframes spin{
 to{transform : rotate(360deg) ;}
}

.loading{
 --innercolor : lightgreen ;
 --mcolor : darkgray ;
}

#loadingcycle{
 width : 15px ;
 height : 15px ;
 border : solid 2px var(--mcolor) ;
 border-top : solid 2px var(--innercolor)  ;
 border-radius : 50% ;
 animation : spin 1s infinite linear ;
}

```
</details>





