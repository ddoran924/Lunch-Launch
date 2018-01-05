# Lunch-Launch
Create a page where users can vote on lunch options 
git remote add origin https://github.com/ddoran924/Lunch-Launch.git
git push -u origin master
<!Docutype html>
<html lang='en'>
  <head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="LLCSS.CSS">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src='LLJS.JS'></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
  <link href="http://fonts.googleapis.com/css?family=Corben:bold" rel="stylesheet" type="text/css">
  <link href="http://fonts.googleapis.com/css?family=Nobile" rel="stylesheet" type="text/css">
  </head>
  
  <script>
  /* hides the submit button upon clicking*/
$(document).ready(function(){
    $("#submit").click(function(){
        $(this).hide();
        $("form").hide();
    });
});
/*Hides the food options when submit button is clicked*/
</script>
  <body>
  <div class="container">
    <h1 id="title">Welcome to Lunch Launch you indecisive cretens!</h1>
    <br>
    <!--description paragraph-->
    <p class='bred'>
    Below we have some options of where we can go for lunch. 
    <br>
    Please select one option.This is anonomous so no one will know where you would like to go. 
    <br>
    No feelings will be hurt. Speak your mind freely here.
    </p>
    <!--Radio selector buttons should include user inputs from LLJS.JS... Currently does not-->
    <div class="row">
    <form>
    <button class='option' name='choice' id='userInput1'>Sylvia's</button>
    <button class='option' name='choice' id='userInput2'>Buddy's</button>
    <button class='option' name='choice' id='userInput3'>Qdoba</button>
    </form>
    </div>
    <!--Submit Button -->
    <div class='btnholder'>
    <button id='submit' onclick='myfunction()'>Submit Answer</button>
    </div>
    <p id='appear'></p>
    <br>
    <!--Blockquote for entertainment value-->
    <blockquote>
      Many women have eaten. Not many have chosen what to eat.
      -Dillon Doran, 1993
    </blockquote>
    </div>
  </body>
  </html>
