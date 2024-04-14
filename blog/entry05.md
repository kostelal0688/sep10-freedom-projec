# Entry 5 (Learning jQuery)
##### 4/8/24
## Context 
In this part of our year-long project, we had to tinker with the tool we previous choose so that we know what to use it for our project. The tool that I learned was jQuery. The purpose of jQuery is to make it much easier to use JavaScript on your website. jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code. jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers.

I used many turtorials, videos, and tried to make something with jQuery. [W3School](https://www.w3schools.com/jquERy/default.asp) tutorials were very helpful for me to learn jQuery. I did most of the tutorials and did the examples. [jQuery Examples](https://www.quackit.com/jquery/examples/) this website also helped me a lt becuase it has many examples of code for jQuery.

The code below is an example of what I made, it an animation using jQuery where the texts gets bigger when you click "start animation" and when you click "stop animation" it stops.

```<!DOCTYPE html>
<title>My Example</title>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script>
  $( function() {
    $( "#start" ).click( function() {
      $( "#animation" ).animate({
        fontSize: "+=1.5em",
        letterSpacing: "+=0.3em"
      }, 4000 );   
    });
    $("#stop").click(function(){
      $("#animation").stop();
    });    
  });
</script>

<button id="start">Start Animation!</button>
<button id="stop">Stop Animation!</button>

<div id="animation">High School of Telecomunications Arts and Technology</div>

```
## Skills 

## Summary 

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
