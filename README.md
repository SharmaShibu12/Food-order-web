# Food-order-web
Food order web using HTML,CSS and Java script.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Meal.com | make your day!</title>
    <style>
        #Full{
            display: flex;
            flex-wrap: wrap;
        }
        #navbar{
            display: flex;
            align-items: center;
            position: relative;
            
        }
        #navbar::before{
            content: "";
            background-color: black;
            position: absolute;
            height: 100%;
            width: 100%;
            z-index: -1;
            opacity: 0.5;
        }
        #logo{
            margin: 10px 34px;
        }
        #logo img{
            height: 100px;
            margin: 10px 10px;
        }
        ul{
            display: flex;

        }
        ul li{
            list-style: none;
            font-size: 1.3rem;
        }
        ul li a{
            display: block;
            margin:10px 10px ;
            padding: 20px 22px;
            border-radius: 20px;
            text-decoration: none;
            color: rgb(107, 57, 11);
        }
        #navbar::before{
            content: "";
            background-color: black;
            position: absolute;
            height: 100%;
            width: 100%;
            z-index: -1;
            opacity: 0;
        }
        ul li a:hover{
            color: darkred;
            background-color: wheat;
        }
        #Home{
            display: flex;
            flex-direction: column;
            padding: 3px 200px;
            justify-content: center;
            height: 500px;
            font-family: 'Bree serif, serif';
            text-align: center;

        }
        .Food::before{
            content: "";
            background: url(https://i.pinimg.com/originals/d3/6d/46/d36d462db827833805497d9ea78a1343.jpg)no-repeat center center/cover;
            position: absolute;
            height: 100%;
            width: 100%;
            z-index: -1;
            opacity: 0.60;
            }
        .h-primary{
            text-align: center;
            color: darkblue;
            font-size: 2.8rem;
            padding: 12px;
            text-align: center;
        }
        #btn{
           padding: 6px 20px;
           border: 2px solid white;
           background-color: brown;
           color: cyan;
           margin: 17px;
           font-size: 1.5rem;

        }
        /* Service Section */
        #Services{ 
            background :url(https://www.bombaybrasseriebirmingham.co.uk/wp-content/uploads/2014/05/indian-food-served-on-table.jpg)no-repeat center center/cover;
            position: relative;

        }
        #Messi{
            margin: 34px;
            display: flex;
        
        }
        .box{
            border: 2px solid brown;
            padding: 34px;
            margin: 3px 6px;
            border-radius: 28px;
            background-color: rgb(197, 137, 137);
        }
        .box img{
            height:156px;
            display: block;
            margin: auto;
        }
        

    </style>
</head>
<body>
    <div id="Full">
        <div class="Food">
            <nav id="navbar">
                <div id="logo">
                    <img src="https://cdn.pixabay.com/photo/2017/02/17/17/33/food-2074638_1280.png" style="width: 15%;" alt="Happy Meal.com">
                </div>
                <ul style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">
                    <li class="item"><a href="">Home</a></li>
                    <li class="item"><a href="">Services</a></li>
                    <li class="item"><a href="">About us</a></li>
                    <li class="item"><a href="">Today's Special</a></li>
                    <li class="item"><a href="">Contact us</a></li>
                </ul>
            </nav>
            <section id="Home">
                <h1 class="h-primary" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">
                    Welcome to <strong>HAPPY MEAL</strong></h1>
                    <p style="font-size: 25px;color:rgb(136, 60, 60); text-align: center;">
                        The Happy Meal contains a main item (a hamburger, cheeseburger or small serving of Chicken McNuggets),
                         a side item (French fries, apple slices, a Go-Gurt tube or a salad in some areas) 
                        and a drink (milk, juice or a soft drink)</p>
                    
                        <p style="font-size: 20px; color:rgb(131, 53, 53);text-align: center;">The Happy Meal did not introduce the practice of providing small toys to
                            children. When the Happy Meal was launched in 1979, the toys were a McDoodle stencil, a McWrist wallet, an ID bracelet, 
                            a puzzle lock, a spinning top or a McDonaldland character-shaped eraser.</p>
                            <button id="btn"> Order Now </button>
        
        </div>                   
            </section>
            <div class="Ronaldo">
                <section id="Services">
                    <h1 style="font-size: 50px; text-align: center; color:bisque; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; "> <strong>Our Services</strong></h1>
                    <div id="Messi">
                        <div class="box">
                            <img src="https://cdn.pixabay.com/photo/2017/12/09/08/18/pizza-3007395__340.jpg" alt="">
                            <h1 style="text-align: center;">Food Catring</h1>
                           
                            <p class="Center">It’s no secret – everybody loves a buffet. And when you include a buffet at your event,
                                 you can be sure that people will be dying to sample everything that you have to offer. Buffets make for an easy way for everybody to
                                 get exactly what they want without having to go through the hassle of organising a menu for each attendee.</p>
                        </div>
                        <div class="box">
                            <img src="https://www.cravingmeals.com/wp-content/uploads/2019/11/Pink-Advocacy-Portfolio-Website-1024x493.png" alt="">
                            <h1 style="text-align: center;">Bulk Ordering</h1>
                           
                            <p class="Center">Among those who are privileged enough to afford buying in volume, the pandemic has suddenly spawned a new population of bulk shoppers. </p>
                        </div>
                        <div class="box">
                            <img src="https://i.pinimg.com/236x/02/fd/5c/02fd5cc15841730936c0c5c555dae3a9.jpg" alt="">
                            <h1 style="text-align: center;">Food Ordering</h1>
                           
                            <p class="Center"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi cum quia, maiores odio 
                                voluptas repellat sapiente impedit ea rerum labore possimus,
                                 explicabo nostrum amet? Soluta amet ipsam inventore. Maiores, voluptatumkim</p>
                        </div>
                    </div>
                
                </section>
        
            </div>
            <div class="Ney">
                <section id="About us">
                    <h1 style="font-size: 50px;">About us : </h1>
                    
        
                </section>
            </div>  
    </div>
    
   
</body>
</html>
