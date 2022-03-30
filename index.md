
<html>
  
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Increment count when button is clicked</title>
</head>
  
<body style="text-align: center;">
    <h1 style="color: green;">
        Pripoj sa do ochrancov panenstva
    </h1>
  
    <h4>
      Kdo sa pripojí ??  
      
    </h4>
  
    <button id="btn">Klikni ty !</button>
  
    <p>
        Button Clicked <span 
        id="display">0</span> Times
    </p>
  
    <script type="text/javascript">
        var count = 0;
        var btn = document.getElementById("btn");
        var disp = document.getElementById("display");
  
        btn.onclick = function () {
            count++;
            disp.innerHTML = count;
        }
    </script>
</body>
  
</html>






<div>
  <h1>WOLLEE</h1>
</div><br />
<div class="dropdown">
  <form>
    <select name="list" id="list" accesskey="target" onchange="showOptions(this); buttonClicked(this)">
      <option value="none">Vyber si BROO</option>
      <option value="GAY">GAY</option>
    </select>
    <input type=button id="but" value="Select" onclick="showOptions(); buttonClicked()" />
    <div><mark id="coutner"></mark></div>
  </form>

</div>
<div id="div"></div>
