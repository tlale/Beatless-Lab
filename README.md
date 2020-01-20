






// Quiz to practice ,
var correct = 0;

//ask students questions
var answer1 = prompt("name a programming lunguage thats a stone gem");
if (answer1.toUpperCase=== "RUBY") {
  correct+= 1;
}
var answer2 = prompt('name a programing lunguage thats named a fter a snake');
if(answer2.toUpperCase==="PYTHON"){
  correct+= 1;
}
var answer3 = prompt("name a lunguage used to style web pages");
if (answer3.toUpperCase==="CSS"){
correct += 1;
}
var answer4 = prompt("name lunguage used to build structure of web page");
if(answer4.toUpperCase==="HTML")
{
  correct += 1;
}
var answer5 = prompt("name lunguage used to add interactivity of the web page");
if(answer5.toUpperCase==="JAVASCRIPT"){
  correct += 1;
}
//Output the quiz results
document.write ("<p> You got " + correct+ "out of 5 questions correct</p>");
/*Results rank based on correct answers got*/
if (correct===5){
  document.write("<p><strong>You earned yourself cold crown</strong></p>");

}
else if(correct>=3){
  document.write("<p><strong> You earned the silver crown </strong></p>");
}
else{
  document.write("<p><strong> no grown ypu need to put more practice.</strong></p>");
}
