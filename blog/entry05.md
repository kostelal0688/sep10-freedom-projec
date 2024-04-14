# Entry 5 (Learning my tool)
##### 4/8/24
## Context 
In this part of our year-long project, we had to tinker with the tool we previous choose so that we know what to use it for our project. The tool that I learned was jQuery I used many turtorials, videos, and tried to make something with jQuery 

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

<div id="animation">Animation</div> ```
## Skills 

## Summary 

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
