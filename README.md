[![NPM](https://nodei.co/npm/morph.css.png?mini=true)](https://nodei.co/npm/morph.css/)
[![Build Status](https://travis-ci.org/internets-inc/morph.css.svg?branch=master)](https://travis-ci.org/internets-inc/morph.css)

# morph.css

> The Latest Greatest Reset CSS

## Our Goal is

- You can define default styles for whatever tags **whenever** you want. This morph.css do no harm for these.
- You can opt **in or out** of morph.css anytime. Even after you've included this reset css into your projects.
- We'll push our users to do code **more semantically**.

## Inspired by

- [nondestructive-reset.css](https://github.com/BYODKM/nondestructive-reset.css)

## Usage

### Basics:

You wrote `p` tag, but it looks like `div`.

```html
<p class="div"></p>
```

You wrote `a` tag, but it looks like `span`.

```html
<a href="#" class="span"></a>
```

### Components:

You can use semantic tags, but they looks like non-semantics.

```html
<div clas="your-component">
  <ul class="your-component__items div">
    <li class="your-component__item div">
      <a href="#" class="your-component__link span">

      </a>
    </li>
  </ul>
</div>
```

## Install morph.css

- Download [master.zip](https://github.com/internets-inc/morph.css/archive/master.zip)
- or `$ bower install morph.css`

## Test Results

- Level 1: [Against browsers' default styles](http://internets-inc.github.io/morph.css/test/level-1.html)
- Level 2: [Against authors' reset styles](http://internets-inc.github.io/morph.css/test/level-2.html)
- Level 3: [Against authors' scoped styles](http://internets-inc.github.io/morph.css/test/level-3.html) (Advanced)

Advanced test requires [Stylus](http://stylus-lang.com) support. Which is scoped import ability like this:

```stylus
.your-scope
  @import "path/to/morph.css/src/morph"
```

## Supported Browsers

- All browsers

## License

- MIT
