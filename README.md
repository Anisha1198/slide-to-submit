## slide-to-submit
A captcha alternative for preventing spam on forms, while maintaining an easy interface for humans.

Simply slide it to the right to submit the form, similar to unlocking an iOS device.

###Usage
Slide To Submit requires jQuery. Add the plugin after jQuery, and initialize it. You may also call options here.

```
<script src="js/jquery.js"></script>
<script src="js/slide-to-submit.js"></script>
<script>
	$('.slide-submit').slideToSubmit({
		submitDelay: 500, //Delays form submission so successText can be seen
		successText: 'Sent!', //Text replacing "slide to send" upon success
		graceZone: 100 //Amount of pixels near the left that is accepted as a full slide.
	});
</script>
```

Add the CSS to the header, or include with your other styles:

```
<link rel="stylesheet" href="css/slide-to-submit.css">
```

Add the slide-submit element at the end of your form:

```
<form>
  <div class="slide-submit">
  	<div class="slide-submit-text">Slide To Submit</div>
  	<div class="slide-submit-thumb">»</div>
  </div>
</form>
```

###Versions
0.1.0 - Launch
