<!DOCTYPE html>
    <html>
    <body>
    
    <p>Click the button to check your password. If it is correct a link will appear.</p>
    
    Password: 
    <input type='text' value='' id='myInput'><br><br>
    <input type='checkbox' onclick='myFunction()'>Show results
    
<a href="index.html" id='demo' style='display:none; color: black;'>link text</a>

  <script>
    function myFunction() {
      var x = document.getElementById('myInput');
      var y = document.getElementById('demo');
      if (x.value === '45') {
        y.style.display = 'block';
      } else {
        y.style.display = 'none';
      }
    }
    </script>
   </body>

    </html>