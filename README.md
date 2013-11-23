# Social Buttons for Twitter Bootstrap by [@mapb_1990][0] (v1.0.0)

**Clean (unofficial) social media buttons for Bootstrap 3 using Font Awesome.**

Social Buttons for Twitter Bootstrap is a plugin/mixin for Twitter Bootstrap that provides great looking (unofficial) themes for various social media buttons.

![Buttons Preview](https://github.com/mapb1990/bootstrap-social-buttons/raw/master/images/left-icons.png)

-----

## Requirements

* Twitter Bootstrap 3.0.0
* Font Awesome 3.2

-----

## Installation

### Using CSS file:

1. Include Bootstrap and Font Awesome in your app (see [this guide](http://www.bootstrapcdn.com/#tab_fontawesome))
2. Include social-buttons.min.css in your app
3. Start using buttons!

### Using LESS then:

1. Ensure Font Awesome is imported into your app (as CSS or LESS)
2. Build less file
  1. Build inside bootstrap 
    1. Import social-buttons.less into bootstrap.less
    2. Build Bootstrap
  2. Or build outside bootstrap 
    1. Import variable.less and mixins.less from bootstrap
    2. Build social-buttons.less
3. Start using buttons.

-----

## How to use

### Icons on left

![Icons on left](https://github.com/mapb1990/bootstrap-social-buttons/raw/master/images/facebook-1.png)

```html
    <div class="btn-group btn-group-social btn-group-facebook">
        <span class="btn btn-social"></span>
        <a href="#" class="btn btn-social">Sign-in with facebook</a>
    </div>
```

### Icons on right
![Icons on right](https://github.com/mapb1990/bootstrap-social-buttons/raw/master/images/facebook-2.png)
```html
    <div class="btn-group btn-group-social btn-group-facebook">
        <a href="#" class="btn btn-social">Sign-in with facebook</a>
        <span class="btn btn-social"></span>
    </div>
```

-----

## Social networks supportted

* bitbucket
* dribbble
* dropbox
* facebook
* flickr
* foursquare
* github
* google-plus
* instagram
* linkedin
* pinterest
* renren
* skype
* stack-exchange (required font-awesome 4.0)
* stack-overflow
* trello
* tumblr
* twitter
* vk
* weibo
* xing
* youtube 
* windows
* vimeo (required font-awesome 4.0)

-----

## Authors

[Miguel Borges][1]

<sub>**Note:** This is a fork of Adam Neumann's [original code](https://github.com/noizwaves/bootstrap-social-buttons); thanks go to him for getting this thing started!</sub>

-----

### LICENSE

> Version 1, December 2009

> Copyright (C) 2009 Philip Sturgeon <email@philsturgeon.co.uk>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

> DON'T BE A DICK PUBLIC LICENSE
> TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

 1. Do whatever you like with the original work, just don't be a dick.

     Being a dick includes - but is not limited to - the following instances:

	 1a. Outright copyright infringement - Don't just copy this and change the name.
	 1b. Selling the unmodified original with no work done what-so-ever, that's REALLY being a dick.
	 1c. Modifying the original work to contain hidden harmful content. That would make you a PROPER dick.

 2. If you become rich through modifications, related works/services, or supporting the original work,
 share the love. Only a dick would make loads off this work and not buy the original works
 creator(s) a pint.

 3. Code is provided with no warranty. Using somebody else's code and bitching when it goes wrong makes
 you a DONKEY dick. Fix the problem yourself. A non-dick would submit the fix back.

 [0]: http://twitter.com/mapb_1990
 [1]: https://github.com/mapb1990
