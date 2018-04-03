<!DOCTYPE html>
<html lang="en">
<p>Click on the buttons inside the tabbed menu:</p>

<div class="tab">
  <button onmouseover="mouseOver('London')" onmouseout="mouseOut('London')">London</button>
  <button onmouseover="mouseOver('Paris')" onmouseout="mouseOut('Paris')">Paris</button>
  <button onmouseover="mouseOver('Tokyo')" onmouseout="mouseOut('Tokyo')">Tokyo</button>
</div>

<div id="London" class="tabcontent">
  <div>3</div>
  <div>2</div>
  <div>3</div>  
  <div>4</div>
  <div>5</div>
  <div>6</div>  
</div>

<div id="Paris" class="tabcontent">
  <div>3</div>
  <div>2</div>
  <div>3</div>  
</div>

<div id="Tokyo" class="tabcontent">
  <div>4</div>
  <div>5</div>
  <div>6</div>  
</div>
</html>
