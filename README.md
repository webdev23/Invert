# Invert
<h3>Say hi to CSS3 filter in Firefox! Basic demo for invert any webpage, like a negative effect.</h3>
<h5>Firefox 35 public release (17 January 2015) is going to fully support CSS3 filters</h5>

<h4>Bookmarklet for invert any webpage:</h4>
javascript:void(document.body.style.filter="invert(100%)");

<h4>For add an Invert button to your page or website:</h4>
<h5>Script:</h5>
	
	function invert() {
       var invrt = document.body;
       if(invrt.style.filter == '' || invrt.style.filter == 'invert(100%)')
          invrt.style.filter = 'invert(0%)';
       else
         invrt.style.filter = 'invert(100%)'};

<h5>Button html:</h5>
     <button onclick="invert()">Invert</button>
     

<h4>Yes! That's all!</h4>






