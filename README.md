# venraaspt
A pt to forward VenRaaS
<pre><code>
(function() {
  
  
  var myVenraasCode = function() {

   // Here callback, do venraas log here
    
  
};
  
var venraas_script = document.createElement('script'); 
venraas_script.type = 'text/javascript'; 
venraas_script.src = 
  ('https:' == document.location.protocol ? 'https://' : 'http://') + 
  'lib.venraas.tw/js/venraaspt-xx.js';
venraas_script.async = true;
venraas_script.onreadystatechange = myVenraasCode;
venraas_script.onload = myVenraasCode;

var head = document.getElementsByTagName('head')[0];
head.appendChild(venraas_script);
  

 
 })();
</code></pre>
