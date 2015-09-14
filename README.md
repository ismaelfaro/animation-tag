# animation-tag
Polymer Web Component to apply simple and fast animation effects.

It is a wrapper of Animate.css. Check the animation examples in [Animate.css] (http://daneden.me/animate)

Demo [http://ismaelfaro.github.io/animation-tag](http://ismaelfaro.github.io/animation-tag/demo/)

Aplication demo [http://polymer-prototype.firebaseapp.com] (http://polymer-prototype.firebaseapp.com)

## Usage

create a simple animation: lightSpeedOut

  <animation-tag animation="lightSpeedOut">
      <element-to-anim></element-to-anim>
  </animation-tag>

  <animation-tag animation="lightSpeedOut" start-time="2.0">
      <element-to-anim></element-to-anim>
  </animation-tag>

With start-time set to time, in seconds, you can controll when the animation start.

 <animation-tag animation="lightSpeedOut" stop>
    <element-to-anim></element-to-anim>
</animation-tag>

With Stop set to true, you can stop the animation in the start and after you can animate it after.

<animation-tag animation="pulse infinite">
    <element-to-anim></element-to-anim>
</animation-tag>

You can make "infinite" animation add this word into the animation attribute.

Note: if you change the "animation" attribute the animation fire automatically.


##TODO

 the element trigger when the animation started or finished.
