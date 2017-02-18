
# Accordion Jquery

Simple Accordion in jquery

**jquery**

```javascript
$('h4').next().hide();
$('h4').click(function(){
	$(this).next().slideToggle();
	$('h4').not(this).next().stop(true,true).slideUp();
});
```

**html**

```html
<h4>#Title</h4> <!-- title -->
<div>
	Lorem Ipsum is simply dummy text of the printing and
    typesetting industry. Lorem Ipsum has been the industry's...					
</div> <!-- container hide text -->		
```

**css**

```css
.container{
	width: 70%;
	margin: 0 auto;
}
h4{
	background: purple;
	color: #fff;
	padding: 10px 0 10px 10px;
	margin-bottom: 3px;
	text-align: left;
	cursor: pointer;
}
.container div{
	background: #eaeaea	;
	text-align: left;
	padding: 20px;
	margin-bottom: 10px;
}	
```

See the demo [here](http://dircebologna.esy.es/tutoriais/accordion/) 







