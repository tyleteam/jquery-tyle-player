#Tyle Player - A free jQuery plugin

##What's this ?

Round slider (also can call as Circular slider, Radial slider) is a jQuery plugin that allows the user to select a value or range of values.

Not only a round slider, it supports the quarter, half and pie circle shapes also.

roundSlider - full slider, pie slider, half slider and quarter slider types

You can check the demos of various circle shapes here.

Different Theming and Appearances ?

By customizing the CSS styles we can make different appearances.

roundSlider - different theming and appearances

You can check the detailed demos [here](https://tyle.io/cards).


##Browser Support

IE 9+, Chrome, Firefox, Safari, Opera (including Mobile devices).


##Options

The roundSlider has several properties and events to interact with the control programmatically.

To know more about the Options, please check the documentation.
```javascript
$(selectol).tylePlayer([
    'https://....jpg',
    'https://....jpg',
    'https://....jpg',
],
{
    width: 510,
    height: 510,
    background: '#000',
    enablePageIndicator : true,
    enableFullscreen : true,
    lastSlideLabel : 'AI Design Tool',
    lastSlideLink : 'https://tyle.io',
    onStart : function(){
        console.log("onStart");
    },
    onEnd : function(){
        console.log("onEnd");
    },
    onNext : function(slideNo){
        console.log("next slideNo", slideNo);
    },
    onPrev : function(slideNo){
        console.log("prev slideNo", slideNo);
    },
    onReplay : function(){
        console.log("replay");
    }
});
```

##Some quick links
How to use ?
Customizations
Different Theming


##Licence
Tyle Player is licensed under the terms of the [MIT license](http://roundsliderui.com/licence.html).
