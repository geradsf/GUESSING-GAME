# GUESSING-GAME
Random number guess game
<script>
  var number = Math.floor (Math.random () *10);
  var guess = prompt("guess a number between 1 and 10");
 
  console.log(number);

  if (guess == number){
    alert("Great you guessed the right number");
  } else {
    alert("That was a bad guess");
  }

</script>
