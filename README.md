# AI Captcha

<br/>
<br/>
<br/>

### Main concept about the project was to deliver a *captcha tool*
<br/>
<br/>

  The practical usage of our solution would be appreciated by institutions <br/>
  or high class companies focused on integrate of Customer Experience.

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

> Both of the pairs are unrecognizable for computer bot, but it’s important to make sure<br/>                                             to create a pair in which the second picture is easily recognizable for a human.

<br/>
<br/>
<br/>
<br/>

## JS

<br/>
<br/>

In order to make the widget applicable to protect the web services it requires to develop an API key which is going to be added to the html of the given website. Development of the mentioned API is way more time consuming,hence it’s still in the creation phase.
 
<br/>
<br/>

For this purpose the model was prepared, according to which a simulation of the process when in-truders trie to hack usuing bot will be carried out. The program analyzes all the steps and actions of the user throughout the test,in the conclusion of which gives the result that the program determines this or that person.



<div align="center">
 <img src="https://github.com/dkliachkovski/AI_Captcha/blob/master/Images/Description/model.png" height="476px">







Here is the test ⭲ [Try it!](https://captcha-9bb226.webflow.io/)

</div>

<br/>
<br/>
<br/>

### Another test was also conducted, but already on a real bot.

<br/>
<br/>
<br/>

In this process, the user participates in a confrontation with a "software" opponent whose goal is to determine where the ```real``` or vice versa is located.

<br/>
<br/>

<div align="center">
<img src = 'https://github.com/dkliachkovski/AI_Captcha/blob/master/Images/Description/Bot%20competition.gif' height = '512px'>

</div>

The user executes the commands in a chaotic manner, which, like the opponent’s actions, are entered into the database.

<br/>

The technique of simple highlighting answers with color is used:
<br/>

* Red - error
 
* Green - correct

<br/>
<br/>

The image acquires a certain color depending on the selected bot photo.

<br/>
<br/>

*Ex.*
> if a photo turns red, it means that the bot took this photo as ```not real``` or vice versa.
























