# Learning-to-push-buttons
<h1>👋Pushing Buttons</h1>

<div id="div1" class="orangeback">
  Here is Div 1
</div>

<div id="div2" class="blueback">
     Here is div 2
     </div>
<p>
  <input type="button"
         value="Change Color"
         onclick="changeColor()" >
</p>
<p>
  <input type= "button"
         value="Change Text"
         onclick="changeText()">
</p>
Result Skip Results Iframe
$brandColor: #55ACEE;

body {
  font-family: system-ui;
  background: linear-gradient(to bottom,
    $brandColor,
    darken($brandColor, 15%)
  );
  color: white;
  height: 100vh;
  margin: 0;
  display: grid;
  place-items: center;
}
.orangeback {
  background-color: orange;
}
.blueback {
  background-color: blue;
}
