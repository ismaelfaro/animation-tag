# animation-tag
Polymer Web Component to apply simple and fast animation effects.

It is a wrapper of Animate.css. Check the animation examples in [Animate.css](http://daneden.me/animate).

Demo [http://ismaelfaro.github.io/animation-tag](http://ismaelfaro.github.io/animation-tag/components/animation-tag/demo/).

Aplication demo [http://polymer-prototype.firebaseapp.com] (http://polymer-prototype.firebaseapp.com).

## Usage

Create a simple animation: `lightSpeedOut`

```html
<animation-tag animation="lightSpeedOut">
    <element-to-animate></element-to-animate>
</animation-tag>
```

 Create animation but start in 2 seconds.

```html
<animation-tag animation="lightSpeedOut" start-time="2.0">
    <element-to-animate></element-to-animate>
</animation-tag>
```

With `start-time` set to time, in seconds, you can control when the animation start.

```html
<animation-tag animation="lightSpeedOut" stop>
    <element-to-animate></element-to-animate>
</animation-tag>
```

With `stop` set to true, you can stop the animation in the start and after you can animate it after.

```html
<animation-tag animation="pulse infinite">
    <element-to-animate></element-to-animate>
</animation-tag>
```

You can make "infinite" animation add this word into the animation attribute.

Note: if you change the "animation" attribute the animation fire automatically.


##TODO

The element trigger when the animation started or finished.
