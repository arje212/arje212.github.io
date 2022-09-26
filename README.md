*
{
    padding: 1000;
    margin: 1000;
    box-sizing: border-box;

}
body
{
background-image: url(image1.jpg);
background-size: cover;
background-attachment:fixed;
font-family: 'Roboto' ,sans-serif;
color: black;
}
.tabi {
    position: absolute;
    display: inline-block;
    bottom: 0;
    margin-left: 1px;

    

    
}
.bula {
    position: absolute;
    display: inline-block;
    bottom: 0;
    margin-left: 3000px;
    

    

    
}


.menu-bar
{
    background: blue;
    text-align: center;
    
}
.menu-bar ul
{
     display: -webkit-inline-flex;
     list-style: none;
     color: mintcream;
}
.menu-bar ul li
{
    width: 400px;
    margin: 15px;
    padding: 15px;

}
.menu-bar ul li a
{
    text-decoration: none;
    color: aliceblue;

}
.active, .menu-bar ul li :hover
{
 background:#2ba ;
 border-radius: 5px;
 

}
.menu-bar .fa
{
    margin-right: 10px;
    font-size: xx-large;
}
.sub-menu-1
{
    display: none;
}
.menu-bar ul li:hover .sub-menu-1
{
    display: block;
    position: absolute;
    background: black;
    margin-top: 15px;
    margin-left: -15px;
}
.menu-bar ul li:hover .sub-menu-1 ul
{
    display: block;
    margin: 10px;
}
.menu-bar ul li:hover .sub-menu-1 ul li
{
    width: 300px;
    padding: 10px;
    border-bottom: 1px dotted #2ba;
    background: transparent;
    border-radius: 9px;
    text-align: left;
}
.menu-bar ul li:hover .sub-menu-1 ul li:last-child
{
    border-bottom: none;
}
.menu-bar ul li:hover .sub-menu-1 ul li a:hover
{
color: #2ba;

}
.fa-angle-right
{
   float: right; 
}
.sub-menu-2
{
    display: none;
}
.hover-me:hover .sub-menu-2
{
    position: absolute;
    display: block;
    margin-top: -40px;
    margin-left: 140px;
    background: black;
    

}

.sub-menu-3
{
    display: none;
}
.menu-bar ul li:hover .sub-menu-3
{
    display: block;
    position: absolute;
    background: black;
    margin-left: 15px;

}
.menu-bar ul li:hover .sub-menu-3 ul
{
    display: block;
    
}
.menu-bar ul li:hover .sub-menu-3 ul li
{
    width: 250px;
            padding: 10px;
            border-bottom: 1px dotted white;
            background: transparent;
            border-radius: 9px;
            text-align: left;
}
.sub-menu-3 .fa
{
    margin-right: 10px;
    font-size: medium;
}
.sub-menu-4
{
    display: none;
}
.menu-bar ul li:hover .sub-menu-4
{
    display: block;
    position: absolute;
    background: black;
    margin-left: 15px;

}
.menu-bar ul li:hover .sub-menu-4 ul
{
    display: block;
    
}
.menu-bar ul li:hover .sub-menu-4 ul li
{
    width: 250px;
            padding: 10px;
            border-bottom: 1px dotted white;
            background: transparent;
            border-radius: 9px;
            text-align: left;
}






