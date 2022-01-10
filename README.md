# AudioKnobs

Beautiful old style SVG audio knobs with mouse adn touch control (JS embedded within SVG) and dynamic shadows (CSS). <br>
Modelled from Moog synthesizer knobs using Inkscape. Check out [Interactive demo](https://megaemce.github.io/AudioKnobs/). <br>

Mouse over the knobs to control their angle. Double click on the knob to reset it to the default value.

<img src="knob_free.svg" width="50%"><img src="knob1.png" width="50%" alt="Original moog knoob. Courtesy of knobshop.com">
<img src="knob_limited.svg" width="50%"><img src="knob2.png" width="50%" alt="Original moog knoob. Courtesy of knobshop.com">

## How to use

Copy whole SVG object code and past it into your code. You are ready to go 🎉 <br>
Alternatively, you can reference the SVG as an `<object>` or `<iframe>` inside the HTML like so

```javascript
<object data="knob_free.svg" width="50px" height="50px"></object>
```

## Technology

Created for my other project like [mobbler](mobbler.js.org) and [Sound exercises](https://megaemce.github.io/Sound-exercises/).<br>

I would never create this solution without the help of these people:

-   [desandro](https://github.com/desandro) - mouse controlled [knob logic](https://github.com/desandro/demo/blob/master/2011/dial-knob.html)<br>
-   [aike](https://github.com/aike) - knobs look from great application [webaudiosynth](https://github.com/aike/webaudiosynth)
-   knobs photos courtesy of [knobshop.com](https://knobshop.com)

Thank you :wave:
