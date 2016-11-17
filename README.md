# getbasis-drawer
This is a css module for the Basis.

## Basis
* Repository: https://github.com/getbasis/basis/
* Documents : http://getbasis.github.io/

## Get Started

### Install
```
$ npm install getbasis
$ npm install getbasis-drawer
```

### Stylus
```
@import 'node_modules/getbasis-drawer/src/stylus/basis';
@import 'node_modules/getbasis-drawer/src/stylus/object/component/drawer';
```

### Javascript
```
import $ from 'jquery';
import BasisDrawer from 'node_modules/getbasis-drawer/src/js/drawer.js';
new BasisDrawer();
```

### HTML
[data-c="drawer__body"] must be right under [data-c="drawer"]

```
<div class="_c-drawer" data-c="drawer">
  <nav id="drawer" class="_c-drawer__body" data-c="drawer__body" role="navigation" aria-hidden="true">
    <ul>
      <li class="_c-drawer__item"><a href="#">menu</a></li>
      <li class="_c-drawer__item"><a href="#">menu</a></li>
      <li class="_c-drawer__item">
        <a href="#">menu</a>
        <div class="_c-drawer__toggle" data-c="drawer__toggle" aria-expanded="false" aria-controls="drawer-submenu">&gt;</div>
        <ul id="drawer-submenu" class="_c-drawer__submenu" data-c="drawer__submenu" aria-hidden="true">
          <li class="_c-drawer__subitem"><a href="#">submenu</a></li>
          <li class="_c-drawer__subitem"><a href="#">submenu</a></li>
        </ul>
      </li>
    </ul>
  </nav>
</div>

<div class="_c-hamburger-btn" data-c="drawer-btn" aria-expanded="false" aria-controls="drawer"></div>
```

## Browser support
Modern Browser and IE10+

## License
MIT License
