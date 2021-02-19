---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Intro N5 Parsons Puzzles
---
# Parsons Practice MH

## Parsons 1 - Adding Two Numbers
Re-arrange the blocks below so they will add two numbers and then print out the answer.

<div id="N5Python1-sortableTrash" class="sortable-code"></div>
<div id="N5Python1-sortable" class="sortable-code"></div>
<div style="clear:both;"></div>
<p>
    <input id="N5Python1-feedbackLink" value="Get Feedback" type="button" />
    <input id="N5Python1-newInstanceLink" value="Reset Problem" type="button" />
</p>
<script type="text/javascript">
(function(){
  var initial = "myFirstNum = int(input(&quot;Enter number 1: &quot;))\n" +
    "mySecondNum = int(input(&quot;Enter number 2: &quot;))\n" +
    "answer = myFirstNum + mySecondNum\n" +
    "print(&quot;The answer is &quot;,answer)\n" +
    "myFirstNum = input(&quot;Enter number 1: &quot;) #distractor\n" +
    "mySecondNum = input(&quot;Enter number 2: &quot;) #distractor\n" +
    "print(&quot;The answer is &quot;,&quot;answer&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "N5Python1-sortable",
    "max_wrong_lines": 2,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "trashId": "N5Python1-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#N5Python1-newInstanceLink").click(function(event){
      event.preventDefault();
      parsonsPuzzle.shuffleLines();
  });
  $("#N5Python1-feedbackLink").click(function(event){
      event.preventDefault();
      parsonsPuzzle.getFeedback();
  });
})();
</script>
<style>
#sortableTrash { width: 58%; }
#sortable { width: 76%; }
</style>

## Parsons 2 - Dividing Two Numbers
Re-arrange the blocks below so they will add two numbers and then print out the answer. E.g. Number 1 = 10 Number2 = 5 Answer = 2

<div id="N5Python2-sortableTrash" class="sortable-code"></div>
<div id="N5Python2-sortable" class="sortable-code"></div>
<div style="clear:both;"></div>
<p>
    <input id="N5Python2-feedbackLink" value="Get Feedback" type="button" />
    <input id="N5Python2-newInstanceLink" value="Reset Problem" type="button" />
</p>
<script type="text/javascript">
(function(){
  var initial = "myFirstNum = int(input(&quot;Enter number 1: &quot;))\n" +
    "mySecondNum = int(input(&quot;Enter number 2: &quot;))\n" +
    "answer = myFirstNum / mySecondNum\n" +
    "print(myFirstNum,&quot;/&quot;,mySecondNum,&quot;=&quot;,answer)\n" +
    "myFirstNum = input(&quot;Enter the first number: &quot;) #distractor\n" +
    "mySecondNum = input(&quot;Enter the second number: &quot;) #distractor\n" +
    "print(myFirstNum,&quot;/&quot;,&quot;mySecondNum&quot;,&quot;=&quot;,answer) #distractor\n" +
    "answer = mySecondNum / myFirstNum #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "N5Python2-sortable",
    "max_wrong_lines": 2,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": false,
    "x_indent": 50,
    "lang": "en",
    "trashId": "N5Python2-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#N5Python2-newInstanceLink").click(function(event){
      event.preventDefault();
      parsonsPuzzle.shuffleLines();
  });
  $("#N5Python2-feedbackLink").click(function(event){
      event.preventDefault();
      parsonsPuzzle.getFeedback();
  });
})();
</script>


## Parsons 3 - Basic If Statements
Re-arrange the blocks below so that if the age is over 18 it will display you can vote. You can indent the code by dragging the code to the right.
<div id="N5Python3-sortableTrash" class="sortable-code"></div>
<div id="N5Python3-sortable" class="sortable-code"></div>
<div style="clear:both;"></div>
<p>
    <input id="N5Python3-feedbackLink" value="Get Feedback" type="button" />
    <input id="N5Python3-newInstanceLink" value="Reset Problem" type="button" />
</p>
<script type="text/javascript">
(function(){
  var initial = "age = int(input(&quot;Enter your age &quot;))\n" +
    "if age &gt;= 18:\n" +
    "	print(&quot;You can vote&quot;)\n" +
    "else:\n" +
    "	print(&quot;Sorry you can&#039;t vote&quot;)\n" +
    "if age &gt; 18: #distractor\n" +
    "if age &gt; 18 #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "N5Python3-sortable",
    "max_wrong_lines": 2,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "trashId": "N5Python3-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#N5Python3-newInstanceLink").click(function(event){
      event.preventDefault();
      parsonsPuzzle.shuffleLines();
  });
  $("#N5Python3-feedbackLink").click(function(event){
      event.preventDefault();
      parsonsPuzzle.getFeedback();
  });
})();
</script>



### Example Next Link
[Next](./parsons/example1.html)
