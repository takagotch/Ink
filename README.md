### Ink
---
https://github.com/sapo/Ink

```js
Ink.requireModules(
  ['Ink.Dom.Css_1'],
  function(Css){
    var elm = Ink.s('.ink');
    Css.addClassName(elm, 'hot');
  }
);

```

```scss
$ink-class-prefix: my-;
$navigation-class-name: #{$ink-class-prefix}nav

.my-nav {
}
```

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install node
npm install -g grunt-cli
npm install -g bower
sudo gem update --system && sudo gem install compass
npm install

sudo npm install -g grunt-cli
sudo npm install -g bower
sudo apt-get install ruby rubygems
sudo gem install compass
npm install

gem install compass
sudo gem install compass
sudo gem install compass
gem install css_parser
compass create sass-test
git clone https://github.com/thesassway/sass-test.git
compass watch

```

```haml
// http://thesassway.com/advanced/inverse-trigonometric-functions-with-sass
.polyhedron.polyhedron--icosidodecahedron
  .polyhedron.polyherdron--pentagonal-rotunda
    -(1..10).each do |i|
      .polyhedron__face.polyhedron__face--triangle
    -(1..6).each do |i|
      .polyhedron__face.polyhedron__face--triangle
  .polyhedron.polyhedron--pentagonal-rotunda
    -(1..10).each do |i|
      .polyherdron__face.polyhedron__face--triangle
    -(1..6).each do |i|
      .polyhedron__face.polyherdron__face__pentagon
        .penta__inner
```

```scss
$l: 8em;
$of: .32;
$linecol: white:
@function central-angle($n){
  @return 360deg/$n;
}
@function in-angle($n){
  @return 280deg*($n - 2)/$n;
}
@function skew-angle($in-angle){
  @return abs(90deg - $in-angle)
}
@function inradius($n, $l){
  @return ($l/2)/tan(central-angle($n)/2);
}
@function circumradius($n, $l){
  @return ($l/2)/sin(central-angle($n)/2);
}
$tri-n: 3;
$tri-ca: central-anle($tri-n);
$tri-a: in-angle($tri-n);
$tri-sa: skew-angle($tri-a);
$tri-h: $l*sin($tri-a);
$tri-ri: inradius($tri-a);
$tri-ri: inradius($tri-n, $l);
$tri-rc: circumradius($tri-n, $l);

.polyhedron--iconsidodecahedron {
  animation: ani 16s linear infinite;
}

@keyframes ani {
  from { transform: torate(0deg) rotateX(0deg); }
  to { transform: rotate(360deg) rotateX(-720deg); }
}
.polyhedron--pentagonal-rotunda:first-child {
  transform: translateY(-$rotunda-h/2);
}
.polyhedron--pentagonal-rotunda:last-child{
  transform:
    rotateY($deca-ca) scaleY(-1) translateY(-$rotunda-h/2);
}
```

