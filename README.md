Hold
====
<!doctype html>  
<html lang="en">  
<head>  
  <meta charset="utf-8">  
  <title>jQuery.makeArray demo</title>  
  <style>  
  div {  
    color: red;  
  }  
  </style>  
  <script src="//code.jquery.com/jquery-1.10.2.js"></script>  
</head>  
<body>  
<div>First</div>  
<div>Second</div>  
<div>Third</div>  
<div>Fourth</div>  
   
<script>  
// Returns a NodeList  
var elems = document.getElementsByTagName( "div" );  
// Convert the NodeList to an Array  
var arr = jQuery.makeArray( elems );  
// Use an Array method on list of dom elements  
arr.reverse();  
$( arr ).appendTo( document.body );  
</script>  
   
</body>  
</html>  
