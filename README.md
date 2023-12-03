# kursovai
*
{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Poppins' , sans-serif;
}
body
{
background: rgb(63, 204, 223);
min-height: 100vh;
}
#header
{
position: absolute;
top: 0;
left: 0;
width: 100%;
padding: 30px 100px;
display: flex;
justify-content: space-between;
align-items: center;
z-index: 10000;
}
#header .logo
{
    color: aliceblue;
    font-weight: 700;
    font-size: 2em;
    text-decoration: none;
}
#header ul
{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 40px;
}
#header ul li
{
list-style: none;

}
#header ul li a
{
text-decoration: none;
padding: 6px 15px;
color: aliceblue;
border-radius: 20px;
}
#header ul li a:hover
{
background: #112434;

}

section
{
position: relative;
width: 100%;
height: 100vh;
display: flex;
justify-content: center;
align-items: center;
}
section img
{
position: absolute;
bottom: 0;
left: 0;

pointer-events: none;
}

section img#s1
{
   z-index: 0; 
}
section img#s2
{
top: 0;
bottom: initial;
}
#txt
{
    position: absolute;
    left: -150px;
    color: #112434;
    z-index: 1;
    font-size: 8em;
    font-weight: 900;
    white-space: nowrap;
    text-transform: uppercase;
    -webkit-text-stroke: 4px white;
}
.sec
{
   position: relative;
   padding: 100px;
   background: pink; 
   box-shadow: 0 0 0 2px pink;
}
.sec h2
{
  font-size: 3em;
  color: #112434;
  margin-bottom: 10px;  
}
.sec p
{
font-size: 1em;
color: #112434;
}



.container
{
    position: relative;
    display: flex;
    justify-content: center;
    align-content: center;
    flex-wrap: wrap;
    gap: 100px 50px;
    padding: 100px 50px;
}
.container .card
{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    width: 350px;
    height: 300px;
    background: #fff;
    border-radius: 20px;
    box-shadow: 0 35px 80px rgba(0, 0, 0, 0,.15);
    transition: 0.5s;
}
.container .card:hover
{
    height: 400px;
}
.container .card .imgBx
{
position: absolute;
top: 20px;
width: 300px;
height: 220px;
background: #112434;
border-radius: 12px;
overflow: hidden;
transition: 0.5s;
}
.container .card:hover .imgBx
{
    top: -100px;
    scale: 0.75;
    box-shadow: 0 15px 45px rgba(0, 0, 0, 0,.2);
}

.container .card .imgBx img
{
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
object-fit: cover;
}
.container .card .content
{
position: absolute;
top: 252px;
width: 100%;
padding: 0 30px;
height: 35px;
overflow: hidden;
text-align: center;
transition: 0.5s;
}
.container .card:hover .content
{
    top: 130px; 
    height: 250px;
}
.container .card .content h2
{
    font-size: 1.5em;
    font-weight: 700;
    color: var(--clr);
}
.container .card .content p
{
    color: #112434;
}
.container .card .content a
{
    position: relative;
    top: 15px;
    display: inline-block;
    padding: 12px 25px;
    background: #112434;
    color: #fff ;
    font-weight: 500;
    text-decoration: none;
    border-radius: 8px;
}
