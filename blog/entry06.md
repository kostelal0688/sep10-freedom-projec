# Entry 6 (Completing MVP)
##### 5/1/24
## Context
In this part of our year long project we had to create an mvp of our website, which is having a working websites. First, we had to make two wideframe one for mobil view and another for computer view. Then we had to make a plan of what components, colors, fonts we were using and a timeline of when we are completing each thing. This helped me a lot while working on the mvp by having everything ready and knowing if I was behind or not. It helped me understand the importance of a plan. To make this websites I used a navbar, a carousel,containers/grids/ columns, and jQuery. 

While building the websites I encountered many challanges, for example I couldn't get the carousel to have text inside. I try many different ways but it couldn't work. Then, I found a carousel with text in W3Schools which helped me build mine. This the code I had to do for the carousel to work with text:

```
<div id="myCarousel" class="carousel slide" data-ride="carousel">
            <!-- Indicators -->
            <ol class="carousel-indicators">
              <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
              <li data-target="#myCarousel" data-slide-to="1"></li>
              <li data-target="#myCarousel" data-slide-to="2"></li>
            </ol>

            <!-- Wrapper for slides -->
            <div class="carousel-inner">
              <div class="item active">
                <img src="design.webp" alt="Los Angeles" style="width:100%; height: 700px;">
                <div class="carousel-caption">
                  <h1>Interior Design</h1>
                  <h4>Learn more about the future of interior design</h4>
                </div>
              </div>

              <div class="item">
                <img src="img.jpg" alt="Chicago" style="width:100%; height: 700px;">
                <div class="carousel-caption">
                  <h1>Interior Design</h1>
                  <h4>Learn more about the future of interior design</h4>
                </div>
              </div>

              <div class="item">
                <img src="img2.jpg" alt="New york" style="width:100%;  height: 700px;">
                <div class="carousel-caption">
                  <h1>Interior Design</h1>
                  <h4>Learn more about the future of interior design</h4>
                </div>
              </div>
            </div>

            <!-- Left and right controls -->
            <a class="left carousel-control" href="#myCarousel" data-slide="prev">
              <span class="glyphicon glyphicon-chevron-left"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="right carousel-control" href="#myCarousel" data-slide="next">
              <span class="glyphicon glyphicon-chevron-right"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
```

Another challenge I faced was getting two jQuery slides to work side by side. In the beginning it didn't work but I had to change the ids for it to work. This is the code I used in the head of the code:

```
 <script>
    $(document).ready(function(){
       $("#flip1").click(function(){
        $("#panel1").slideToggle("slow");
      });
      $("#flip2").click(function(){
         $("#panel2").slideToggle("slow");
       });
    });
    </script>
```

## Engineering Design Process
I am currently in step 5 of the engineering design process, where the goal is to create a prototype. This part was more about vreating the MVP of our project. The next step of the engineering design process is to improve as needed.

## Skills 
Some skills that I’ve learned from working on this blog are **debugging, problem decomposition,** and **time management**

### Debugging
A skill I learned was debugging since they were many errors while coding my MVP. For example, I couldn't get the jQuery slide to work and when I got the to work by changing their id, my CSS wasn't working. And I figured out that I had forgotten to change the id in the CSS too.

### Problem Decomposition 
Another skill I learned was problem decomposition because while trying to create a carousel I couldn't get the carousel to have text inside it. So I have to break down the problem and try different ways. However, I ended up finding how to make it work from W3Schools. 

### Time Management
One skill I learned is time management, I had to follow a timeline to complete my MVP in time. I had to follow the tiemline since during spring break I was away for vacation and couldn't work on it as much so I had to have most of it done before break. 

## Summery 
So far I am very excited with the restult of my MVP. Our next step is to go above the MVP by adding more components and fixing possible errors.


