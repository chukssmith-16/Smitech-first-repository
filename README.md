# Smitech-first-repository
My first project 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>Styled To-Do List</title>
    <link rel="stylesheet" href="styles.css"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <style>
    .list {
font-size: 16px;
border: 0.5px solid black;
text-align: auto;
width:270px ;
margin: 90px;
padding: 70px;
  border-radius: 20px;
}
a {
  text-decoration: none;
}
a:hover {
  color: red;
}
a:active {
  color: green;
}
a:focus {
  border: 2px solid orange;
}
a:visited {
  color: purple;
}
div {
  border: 2px solid plum;
  background-color: plum;
  margin-bottom: 25px;
  box-shadow: 5px 5px blur-radius spread-radius;
  width: 250px;
  border-radius: 10px;
}
.list {
  box-shadow: 5px 10px  blur-radius spread-radius;
  background: linear-gradient(45deg, blue,yellow,purple);
  height: 55vh;
}
body {
  font-family: serif;
  width: 60px;
  display: inline;
  padding-bottom: 20px;
    background: linear-gradient(45deg, purple,pink,magenta);
}
h1 {font-family: cursive;
  font-size: 40px}
  </style>
</head>

<body>
<fieldset class="list">
    <ul class="todo-list">
        <h1>TODO List</h1>
        <div class="html">
        <li><input id="html" type="checkbox"/><label for="html">Learn HTML</label><ul class="sub-item"><li><a href="https://youtube.com/embed/salY_Sm6mv4?si=JYhC6AzrUWdeNcL6" target="_blank" class="sub-item-link">watch video here</a></li></ul></li></div>

<div class="css">
        <li><input id="css" type="checkbox"/><label for="css">Learn CSS</label><ul class="sub-item"><li><a href="https://youtube.com/embed/OEV8gMkCHXQ?si=6XY2dRwkMDbWDgHk" target="_blank" class="sub-item-link">learn CSS here</a></li></ul></li></div>

<div class="javascript">
        <li><input id="javascript" type="checkbox"/><label for="javascript">Learn JavaScript</label><ul class="sub-item"><li><a href="https://youtube.com/embed/upDLs1sn7g4?si=4FwSy2eqiG_D6ydz" target="_blank" class="sub-item-link">click here to watch</a></li></ul></li></div>

<div class="python">
        <li><input id="python" type="checkbox"/><label for="python">Learn Python</label><ul class="sub-item"><li><a href="https://youtube.com/embed/x7X9w_GIm1s?si=BXlDKNEReV-WiqPJ" target="_blank" class="sub-item-link">Watch here</a></li></ul></li></div>
    </ul>
    </fieldset>
</body>

</html>
