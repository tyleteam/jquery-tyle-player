#Tyle Player - A free jQuery plugin

##What's this ?

Round slider (also can call as Circular slider, Radial slider) is a jQuery plugin that allows the user to select a value or range of values.

Not only a round slider, it supports the quarter, half and pie circle shapes also.

roundSlider - full slider, pie slider, half slider and quarter slider types

You can check the demos of various circle shapes here.

Different Theming and Appearances ?

By customizing the CSS styles we can make different appearances.

roundSlider - different theming and appearances

You can check the detailed demos here.

##Browser Support

IE 9+, Chrome, Firefox, Safari, Opera (including Mobile devices).

##Options

The roundSlider has several properties and events to interact with the control programmatically.

To know more about the Options, please check the documentation.

    $("#slider").roundSlider({
        min: 0,
        max: 100,
        step: 1,
        value: null,
        radius: 85,
        width: 16,
        handleSize: "+0",
        startAngle: 0,
        endAngle: "+360",
        animation: true,
        showTooltip: true,
        editableTooltip: true,
        readOnly: false,
        disabled: false,
        keyboardAction: true,
        mouseScrollAction: false,
        sliderType: "default",
        circleShape: "full",
        handleShape: "round",
        lineCap: "square",

        // events
        beforeCreate: null,
        create: null,
        start: null,
        drag: null,
        change: null,
        stop: null,
        tooltipFormat: null
    });
Some quick links

How to use ?
Customizations
Different Theming
Licence

Tyle Player is licensed under the terms of the MIT license.
