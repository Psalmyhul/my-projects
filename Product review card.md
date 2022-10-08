# my-projects
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Preview Card</title>
    <link href="product preview card.css" rel="stylesheet" />
  </head>
  <body>
    <div class="section">
       <img src="images/perfume.jpg" alt="problem loading image" />
        <div class="text">
          <h3>PERFUME</h3>
          <br>
          <strong><p class="Gabrielle">Gabrielle Essence Eau De Parfum</p></strong>
          <p>
            A floral, solar and voluptuous interpretation composed by Olivier
            Poige, Perfumer-Creator for the House of CHANEL.
          </p>
          <br>
          <p class="price"><bold>$149.99 </bold><small><del>$169.99</del></small></p>  
          <br>
          <input type="submit" value="Add to cart"></input>
        </div>
    </div>
  </body>
</html>

/*CSS Codes*/
body{
    background-color: hsl(30, 38%, 92%)
}

.section{
    display:flex;
    justify-content: space-between;
    width:700px;
    height:450px;
    border:2px; 
    border-radius:12px; 
    background-color:  rgb(255,255,255) ;
    margin-top: 100px;
}
.section, img{
    height: 450px;
    margin-right: 10px;

    

}
.section, h3{
    margin:0;
}
.text{
    width:300px;
    margin-left: 0;
    padding-top: 20px;
    padding-right: 10px;
    padding-left: 1px;
    padding-bottom: 20px;
        
}
h3{color: grey;
font-family: sans-serif;}
img{
    width: 350px;
    border:2px; 
    border-top-left-radius:12px;
    border-bottom-left-radius:12px;
}
.price{
    color: green;
    font-size: 20px;
    

}
input{
    height: 50px;
    width: 250px;
    background-color: darkgreen;
    color: rgb(255,255,255);
    border:0px;
    border-radius:12px;
    padding:5px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.Gabrielle{
    font-size: 30px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: 700px;

}
input:hover {
    color: lightgreen;
}

input:visited{
    color: lightgreen;
}
del {
    color: black;
    font-size:12px;
}
