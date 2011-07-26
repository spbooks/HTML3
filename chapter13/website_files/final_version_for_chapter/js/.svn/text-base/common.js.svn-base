$(document).ready(function(){
 //Enhancing the form with helper text
 $("#contactname").val("Please enter full name");
 $("#telephone").val("Incl local dialling code");
 $("#eventdate").val("Format DDMMYYYY");
 $("#details").val("The more you can enter here, the less we have to check with you :)");
 $("#search-box,#q").val("Enter search phrase");
 $("input, textarea").focus(function(){
  $(this).select();
 });
 //Making the gallery captions appear on hover
 $("figcaption").hide();
 $("figure").each(function(){
  $(this).hover(function(){
   $(this).find("figcaption").slideDown('medium');
  },function(){
   $(this).find("figcaption").slideUp('medium');
  }); 
 });
});