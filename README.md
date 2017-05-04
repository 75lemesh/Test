<!doctype html>
<html>
    <head>
	  <meta charset="utf-8">
	   <script>
	   
	     		 
	     var a = "the largest ecosystem of open source libraries";
		 
		 alert ("Есть текст" + " " + a); 
		 
		 var str = "";
		  
		 var m = a.length;
		 
		 var b = prompt ("Введите позицию для замены регистра если 0 это первый символ" + "" + "а" + " " + m + " " + "последний" );
		 
		 for  (var i=0; i<a.length; i++) { 
               if (i==b ){
			  	   str += a[i].toUpperCase();
		                 } else {
				                 str += a[i];
						        }
		    }
		 
		 alert (str);
		 
		 console.log (str)
		 
		
	   </script> 
    </head>
    <body>
	</body>
</html>
