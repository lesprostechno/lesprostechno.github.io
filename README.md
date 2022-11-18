# lesprostechno.github.io
<DOCTYPE html>
<html>
    <head>
        
      <style>
        * {
/* Here i made the margin and padding  0 */
  margin: 0; 
  
    padding: 0;
}
  
.navbar {
    display: flex;
  
/* This is used to make the navbar sticky, So that the
    navbar stays at the top part even if we scroll */
    position: sticky; 
    align-items: center;
    justify-content: center;
    top: 0px;
  
/*it specifies the mouse cursor to be displayed
    when it is pointed over the element */
    cursor: pointer;
}
  
.nav-list {
    width: 50%;
    display: flex;
}
  
.nav-list li {
    list-style: none;
    padding: 26px 30px;
}
  
.nav-list li a {
    text-decoration: none;
    color: white;
}
  
.nav-list li a:hover {
    color: black;
}
  
.rightNav {
    width: 50%;
    text-align: right;
}
  
#search {
    padding: 5px;
    font-size: 17px;
    border: 2px solid grey;
    border-radius: 9px;
}
  
.background {
    background:blue;
    background-blend-mode: darken;
    background-size: cover;
}
  
      </style>
    </head>
    <body>
        <!-- here in nav tag i have used two classes 
             that is navbar and background-->
        <!-- each class declared in nav tag will be 
             used to design the form using CSS-->
        <nav class="navbar background">
            <!-- we have used list tag that is ul 
                 to list the items-->
            <ul class="nav-list">
                <li><a href="file:///Users/raphaelhebert/Desktop/siteweb/accueil.html">Accueil</a></li>
                <li><a href="file:///Users/raphaelhebert/Desktop/siteweb/nous-chosir.html">Nous Choisir</a></li>
            </ul>
            <!-- we have used rightnav in order to design
                 the seachbar properly by using CSS-->
            <div class="rightNav">
          <!-- the value that search bar will take is text -->
                <input type="text" name="search" id="search" />
                <button class="btn btn-sm">Search</button>
            </div>
        </nav>
    </body>

        <meta charset="utf-8"  /> <br>
        <title>Les Pros De La Techno</title>
        <h1>Les Pros De La Techno</h1> <br>
    <head>
    <body>
        <h2>Nos services informatiques</h2>
        <body>C'est ici que vous pouvez découvrir nos services offerts.</body> <p>
        <body>Service de TI Informatique,</body> <body>Support informatique,</body> <body>Création de Cloud computing,</body> <body>Services Cloud,</body> 
        <body>Solutions de mise en réseau</body> <body>et Assistance technique</body> <br>
    <body> <br>
    <h2>Essayez notre service. 100% Gratuit!</h2>
</body>
</html>      


