<!-- # CSS-GRID3
Spanning of rows and columns in css grid -->
<html>
    <style>
        .container{
            display: grid;
            grid-template-columns: repeat(5,2fr);
            grid-template-rows: repeat(5,1fr);
            /*grid-row-gap: 1rem;*/
            /*grid-column-gap: 2rem;*/
            grid-gap: 1rem;
            
           
        }
        .box{
            padding: 12px;
            background-color: pink;
            border: 2px solid black;
            
        }
        .box:first-child{
            /*grid-column-start: 1;*/
            /*grid-column-end: 4;*/
            /*grid-row-start: 2;*/
            /*grid-row-end: 4;*/
            
            /*shorthand*/
            grid-column: 1/span 3;
            grid-row: 1/span 3;
        }
    </style>
<body>
<div class="container">
    <div class="box"> box1</div>
    <div class="box"> box2</div>
    <div class="box"> box3</div>
    <div class="box"> box4</div>
    <div class="box"> box5</div>
    <div class="box"> box6</div>
    <div class="box"> box7</div>
    <div class="box"> box8</div>
    <div class="box"> box9</div>
    <div class="box"> box6</div>
    <div class="box"> box7</div>
    <div class="box"> box8</div>
    <div class="box"> box9</div>
    <div class="box"> box6</div>
    <div class="box"> box7</div>
    <div class="box"> box8</div>
    <div class="box"> box9</div>
    <div class="box"> box10</div>
    <div class="box"> box11</div>
    
</div>
</body>
</html>
