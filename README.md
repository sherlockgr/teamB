# teamB
CSCI 1210 Semester Project


here is the CSS for the universal navbar for all pages

.nav-img {   
    display: block;  
    width: 100px;         
    margin-left: auto; 
    margin-right: auto;
}

nav {
    background-color: #ffffff;    
    color: rgb(0, 0, 0);          
    width: 100%;            
    margin: 0;                  
    text-align: center;
    font-family:Verdana, Tahoma, sans-serif;
}

nav a {
    display: inline-block; 
    width: 75px;    
    color: rgb(0, 0, 0);    
    margin: 25px;
}

nav a:hover, nav a:active, .current {
    color: #000000;                 
    border-bottom: 2px solid #333;  
}

nav a:link, nav a:visited {      
    border-radius: 5px;     
    text-align: center;     
    text-decoration: none;  
    position: relative;     
    left: 50px;             
    top: -25px;    
    padding: 5px;         
}

and this is the html

<nav>
		<img class="nav-img" src="images/icon2.png" alt="Lighthouse Quilting Company">
		<a href='#'>Home</a>
		<a href='#'>About Us</a>
		<a href='#'>Support</a>
		<a href='#'>Shop</a>
</nav>

IF YOU CAN FIGURE OUT HOW TO CENTER THE NAVBAR UNDER THE LOGO THEN PLEASE DO IT
