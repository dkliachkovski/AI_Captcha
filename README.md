# AI Captcha

<br/>
<br/>
<br/>

### Main concept about the project was to deliver a *captcha tool*.
<br/>
<br/>

  The practical usage of our solution would be very much appreciated by institutions <br/>
  such as museums or high class companies focused on integrate of Customer Experience

<br/>
<br/>
<br/>

*Ex.*    
<br/>
 > Art galery which is selling online entrance tickets would like to attract their clients from the very begging. A way to deliver unique feeling in a digital environment would be even by accepting the captcha regulation that is very much more convenient than choosing if on the picture there is a car or there is not - just like Google learnt us to do.

<br/>
<br/>
<br/>
<br/>

#### We can differentiate project into 2 parts:

<br/>
<br/>

1.	*Neural style transfer*

<br/>

2.	*Captcha implementation based on JS*

<br/>
<br/>  
<br/>
<br/> 

> Library of the shown photos is displaying both  original <br/> 
  works of art and fake ones made by neural style transfer. 

<br/>
<br/>

### NST

<br/>

* Input images - photos of ex. animals
* Style images - photos of ex. art
* Model - pertained VGG-19

<br/>
<br/>

Loss function - is meant to generate 2 style matrixes.<br/>
The root mean square differ-ence between the two style matrices is defining the style loss.

<br/>
<br/>
<br/>

## <div align="center"> Here we can easily tell which of the art is the original one and which is not

<br>

<div align="center">
 <img src="https://github.com/dkliachkovski/AI_Captcha/blob/master/Images/Style/Starry%20Night.jpg" height="476px">
 <img src="https://github.com/dkliachkovski/AI_Captcha/blob/master/Images/Style/style_transfer_result_eagle6.png" height="223px">
 <img src="https://github.com/dkliachkovski/AI_Captcha/blob/master/Images/Style/style_transfer_result_bridge.jpg" height="223px">
</div>



## <div align="center"> Instead of this pair ⇪

<br/>
<br/>
<br/>

Both of the pairs are unrecognizable for computer bot, but it’s important to make sure<br/>                                             to create a pair in which the second picture is easily recognizable for a human.

<br/>
<br/>
<br/>
<br/>

## JS

<br/>
<br/>

In order to make the widget applicable to protect the web services<br/>
it requires to develop an API key which is going to be added to the html of the given website.

<br/>

Development of the mentioned API is way more time consuming,<br/>
hence it’s still in the creation phase. Here is the mvp version ⭬  [Play quick train of the system](https://captcha-9bb226.webflow.io/)


















