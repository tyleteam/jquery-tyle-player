#Tyle Player - A free jQuery plugin

##What's this ?
Tyle Player is a javascript player for contents images like newscard, social graphics, and so on. It supports all of the major browsers.

![ScreenShot](./etc/tyle_player.gif)

You can check the detailed demos [here](https://tyle.io/cards) and 


##Browser Support

IE 9+, Chrome, Firefox, Safari, Opera (including Mobile devices).

##Usage
You can also see the example on [http://codepen.io/zidell/pen/MbErOE](http://codepen.io/zidell/pen/MbErOE)
```html
<head>
    <link href="https://d1s0awd0642fry.cloudfront.net/web/plugin/jquery-tyle-player-0.1.0/dist/jquery-tyle-player.min.css" rel="stylesheet" />
    <script src="https://d1s0awd0642fry.cloudfront.net/web/plugin/jquery-tyle-player-0.1.0/dist/jquery-tyle-player.min.js"></script>
</head>
<body>
    <div id="#container"></div>
    
    <script>
        $('#container').tylePlayer([
            'https://d1s0awd0642fry.cloudfront.net/cards.images/Bz/BzHbuJcmdH39dhtKa_cont.png',
            'https://d1s0awd0642fry.cloudfront.net/cards.images/eK/eK6faxWbRivP7y5zE_cont.png',
            'https://d1s0awd0642fry.cloudfront.net/cards.images/Ek/EkM3BqNtd8GPKiX7w_cont.png'
        ]);
    </script>
</body>
```


##Options

The Tyle Player has several properties and events to interact with the control programmatically.
```javascript
$(selector).tylePlayer([
    'https://....jpg',
    'https://....jpg',
    'https://....jpg'
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

##Licence
Tyle Player is licensed under the terms of the [MIT license](http://roundsliderui.com/licence.html).
