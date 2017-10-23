## 1. Why jQuery?

	$('.login-button').on('click', () => {
		$('.login-form').toggle();
	});

## 2. jQuery Methods

	Read The Stuff
	Click Next to Continue.!	

## 3. jQuery Library

	Read the whole explaination
	Click Next to Continue. !	

## 4. Adding jQuery
   Open index.html before the closing of the body tag but before this script tag
   ```
    <script src='js/main.js'></script> 
   ```
 Add this
   ```    
	<script src="https://code.jquery.com/jquery-3.2.1.min.js" integrity="sha256-hwg4gsxgFZhOsEEamdOYGBf13FyQuiTwlAQgxVSNgt4="crossorigin="anonymous"></script>
   ```	

## 5. .ready()

	$(document).ready(() => {

	});   

## 6. Targeting by Class

	$(document).ready(() => {
	  	$('.product-photo').show()
	});

## 7. Targeting by id
	
	$(document).ready(() => {
		$('#nav-dropdown').hide();
	});

## 8. jQuery Objects

	$(document).ready(() => {
		let	$navDropdown = $('#nav-dropdown');  		$navDropdown.hide();
	}); 

## 9. Event Handlers

	$(document).ready(() => {
	  	const $menuButton = $('.menu-button'); 
	    const $navDropdown = $('#nav-dropdown');  	  	$menuButton.on('click', () => {
		    $navDropdown.show();
		});
	});

## 10. Review: jQuery Introduction

	Read the review and Click on UpNext
	Now you are good to go to the Lesson.

