# jquery_tutorials
A repository for jQuery tutorials
First of all you have to create HTML Document structure and the HTML Element which will be toggle and which will toggle in this example i have created a button which will toggle and a h1 element which will be toggled.
Then add jquery to your file you can download jquery from
https://jquery.com/download/
and you can also embed it to your file (like i did) form here
https://code.jquery.com/

Then create your own script tag at the end of file (just before ending body tag).
and in it create a document.ready function like that.

$(document).ready(function(){
 //here will be our  script
});


after that we have to target the element WHICH WILL TOGGLE. In my case it is a button so to target a button we have to create a function like that


$('ELEMENT NAME or if you want to target with id or class use # or . with id and class respectively. In our case it is a element so i will target it simply by element name button').click();


so we have targeted the element which will toggle and now we have to toggle the element so we will create a function which will be performed whenever the element will be clicked.
so use it like that


$('ELEMENT NAME or if you want to target with id or class use # or . with id and class respectively. In our case it is a element so i will target it simply by element name button').click(function(){

});


so  we can now perform different functions when a element is clicked !. we just want to hide and show a element whenever this is clicked so we will use jQuery's toggle function here like that


$('ELEMENT NAME or if you want to target with id or class use # or . with id and class respectively. In our case it is a element so i will target it simply by element name button').toggle('amount of time in milliseconds');


so our resulted document will be like that


$('ELEMENT NAME or if you want to target with id or class use # or . with id and class respectively. In our case it is a element so i will target it simply by element name button').click(function(){
  $('ELEMENT NAME or if you want to target with id or class use # or . with id and class respectively. In our case it is a element so i will target it simply by element name button').toggle('100000');
});
