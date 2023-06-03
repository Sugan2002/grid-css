# EXPERIMENT-07
# <p align="center"> GRID-BOX </P>

## AIM: 
To create a web layout using grid-box
     
## ALGORITHM:

### STEP 1:
Create an HTML container element where you want to place the gridbox. For example, you can use a <div> element with a unique ID.
### STEP 2:
In CSS file or style block, target the container element using its ID and define it as a grid container.
### STEP 3:
Define the number and size of the rows and columns in the grid. You can use various units such as pixels (px), percentages (%), or the fractional unit (fr) to specify their sizes. For example, to create a 3x3 gridbox
### STEP 4:
Customize the gridbox by adding additional CSS properties. For example, you can specify the size of grid items, add gaps between rows and columns, or set the alignment of the grid items. 
### STEP 5:
In HTML file, create the grid items inside the container element. For example, you can create nine <div> elements as grid items.

## PROGRAM:

### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Css_Grid</title>
<link href="assets/css/style.css" rel="stylesheet">
</head>
<body>
<div class="container">
<div class="i1">
<div class="nav">
<li>The Book</li>
<li>Author</li>
<li>Press</li>
<li>Events</li>
<li>Shop</li>
<li>Contact</li>
</div>
</div>
<div class="i2"><img src="assets/img/image2.png" style="height: 100%; width: 100%;"></div>
<div class="i3">
<p><u>Upcoming Podcasts</u></p><br><br>
<h3>Deborah Bibby</h3>
</div>
<div class="i4">
<p><u>The Book</u></p><br>
<img src="assets/img/book.png" style="width:20%">
</div>
<div class="i5">
<img class="img5" src="assets/img/image3.png" style="height:100%; width: 100%;">
</div>
<div class="i6">
<p><u>Synopsis</u></p><br>
<h3>Applying design<br>principles to your<br>life.</h3>
</div>
<div class="i7">
<p><u>Author</u></p>
<h3>Vince Frost*</h3>
</div>
 
<div class="i8">
<img src="assets/img/icons.png" style="height: 100%; width: 100%;">
</div>
<div class="i9">
<br>
<h3>Shop</h3>
</div>
<div class="i10">
<p>Designing Wellbeing with Kerry Hill Architects</p>
</div>
<div class="i11">
<h3>View the latest events</h3>
</div>
</div>

</body>
</html>

```

### style.css
```css


*{
margin: 2;

/* background-color: white; */
}

img{
width: 120%;
}
.container { display: grid;
grid-template-columns: auto auto auto; gap: 10px;
background-color: rgb(21, 20, 20); padding: 10px;
padding-bottom: 70px; color: black;
}

.container > div {
background-color: #F4EFDE; text-align: center;
padding: 0; font-size: 30px;
}
 
.i1 {
grid-row-start: 1;
grid-row-end: 1;
grid-column-start: 1; grid-column-end:10;
}

li{
list-style-type: none; padding-right: 20px;
}
.nav{
display: flex;
flex-direction: row;
}
.i2 {
grid-row-start: 2;
grid-row-end: 4;
grid-column-start: 1;
grid-column-end: 1;
}


.i3 {
text-align: center; grid-row-start: 2;
grid-row-end: 4;
grid-column-start: 2;
grid-column-end: 2;
}

.i3 p{
font-size: 20px;
}

.i4 {
text-align: center; grid-row-start: 2;
grid-row-end: 6;
grid-column-start: 3;
grid-column-end: 10;
}

.i4 p{
font-size: 20px;
}
 
.i5 {
grid-row-start: 4;
grid-row-end: 9;
grid-column-start: 1;
grid-column-end: 3; background-color: black;
}
.i6 {
grid-row-start: 6;
grid-row-end: 9;
grid-column-start: 3;
grid-column-end: 4;
}

.i7 {
grid-row-start: 6;
grid-row-end: 8;
grid-column-start: 4;
grid-column-end: 10;
}
.i8 {
grid-row-start: 8;
grid-row-end: 9;
grid-column-start: 4;
grid-column-end: 7;
}
.i9 {
grid-row-start: 8;
grid-row-end: 9;
grid-column-start: 7;
grid-column-end: 10;
}

.i10{
grid-row-start: 9;
grid-row-end: 10;
grid-column-start: 1;
grid-column-end: 3;
}

.i11{
grid-row-start: 9;
grid-row-end: 10;
grid-column-start: 3;
grid-column-end: 10;
}
``` 
  
## OUTPUT:

![image](https://github.com/Sugan2002/grid-css/assets/77089743/0d4ddce8-ca8a-4239-a75f-c4b2a4a3989a)

## RESULT:

   Thus, the weblayout using grid-box is developed successfully using HTML & CSS.
