vanilla
=======

A starting point for front end development projects

The Components
--------------
[SASS](http://sass-lang.com), [Compass](http://compass-style.org), [Inuit.css](http://inuitcss.com) via [compass-inuit](https://github.com/stephenway/compass-inuit), [Susy](http://susy.oddbird.net)


Why
---
In a number of projects I've found myself cobbling together a few different projects to build a UI stack I feel comfortable with. I felt it was time to just have a kit I could clone and get moving

At the core I'm using SASS and Compass. SASS because for my dollar it's the best preprocessor. Compass more so for the extensions and the set of CSS3 mixins.

I've chosen inuit.css for nearly all my development because I feel it does just the right amount of configuration for my needs and base module needs without being intrusive or to heavy handed. As well it handles class naming better than other libraries I've come across. For simplicity purposes I use the compass-inuit extension as it makes customization and integration easy.

I'm very picky about choosing a grid system. I feel grids should just work and they should be flexible based on the needs of the project. This for me is where Susy wins, as instead of forcing a certain size or method to grid production it allows you to build your own grid from the ground up for each project and for different sections in the same project. with at first it can be a little overwhelming due to the number of variables it's power that I've seen can't be matched.

Make it work
------------
Getting from clone to go is pretty simple but it does require a little setup. You'll need sass, compass, compass-inuit and susy installed. but a few commands can make that happen.

    // this will bring SASS with it
    $ gem install compass
    
    $ gem install compass-inuit
    
    $ gem install susy

And now your off to the races.