# Pac-Nav

## Summary
Pac-Nav "swallows" up nav items to make them responsive at any viewport.

## Example
<a href="//ericconstantinides.github.io/pac-nav/">See a demo of pac-nav.</a>

## TODO:
- make pac-nav an Object
- Remove jQuery dependency
- Make pac-nav initiate like this in order to allow multiple pac-navs:
<pre>
$('.main-nav').pacNav({
  fewestHybridItems: 2,
  rightSideEl:       '.js-pac-nav__right',
  leftSideEl:        '.js-pac-nav__left',
  desktopNavEl:      '.js-pac-nav__desktop-nav',
  mobileNavEl:       '.js-pac-nav__mobile-nav',
  navToggleEl:       '.js-pac-nav__nav-toggle',
});
</pre>
-Make expanded clicks on hybrid and mobile modes expand with
<pre>
transitions by;
  hide it with opacity: 0;
  make it expand
  take its height
  make it retract
  show it with opacity: 1
  expand to that height with a transition
</pre>

## Usage
To run pac-nav, set this inside of of your main javascript:
<pre>new PacNav();</pre>