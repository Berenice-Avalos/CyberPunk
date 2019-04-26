
  <html lang="en">
       <head>
           <meta charset="utf-8">
           <title>Welcome, Berenice Avalos's website, CSP2</title>
       </head>
       <body>
           <h1>
               YAY!
          </h1>
         <img src="https://tse4.mm.bing.net/th?id=OIP.3QTALpGhLUNzHDpMUGVFUgHaKe&pid=Api" alt="cyber rain">
      </body> 
  </html>

<html>
<body background="https://cdnb.artstation.com/p/assets/images/images/002/648/641/large/roger-matallana-exterior-cyberpunk-final2.jpg?1464096465">
</body>
</html>

<p><font color="#E227E5"><strong>I HAD TO DO IT AGAIN
   <p><strong>I MADE MY SECOND SECOND WEBSITE
        <p><strong> *INSERT EVIL LAUGH"!!!!!
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}

/* Style the close button */
.topright {
  float: right;
  cursor: pointer;
  font-size: 28px;
}

.topright:hover {color: red;}
</style>
</head>
<body>

<h2>Tabs</h2>
<p>Click on the x button in the top right corner to close the current tab:</p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Computer Science Project 1')" id="defaultOpen">Computer Science Project 1</button>
  <button class="tablinks" onclick="openCity(event, 'Computer Science Project 2')">Computer Science Project 2</button>
</div>

<div id="Computer Science Project 1" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3>Computer Science Project 1</h3>
  <p> <a href="https://raw.githubusercontent.com/Berenice-Avalos/ARTSY-AGAIN/a574ed88168ebfd8d444011b6deb054c7635ffa1/Written%20Questions%2C%20Section%202.pdf" target ="_blank">Written Response</a></p>
   <p> <a href="https://raw.githubusercontent.com/Berenice-Avalos/ARTSY-AGAIN/a574ed88168ebfd8d444011b6deb054c7635ffa1/Program%20Code%2C%20Section%203.pdf" target ="_blank">Program Code</a></p>
</div>

<div id="Computer Science Project 2" class="tabcontent">
  <span onclick="this.parentElement.style.display='none'" class="topright">x</span>
  <h3>Computer Science Project 2</h3>
  <p> <a href="https://raw.githubusercontent.com/Berenice-Avalos/ARTSY-AGAIN/93830e4167a11483f252ab52a282d52dbe92109b/Spider%20Man%20%20(1).pdf" target ="_blank">Google Drawing Artifact</a> </p>
  <p> <a href="https://raw.githubusercontent.com/Berenice-Avalos/ARTSY-AGAIN/f4223026c4acd3607994c54a56d870ccf9786e6b/Spider-Verse%20PDF%20(1).pdf" target ="_blank">Artifact Written Response</a> </p>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
