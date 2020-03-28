Npm shadowizard
==============
2020-03-28


This is just a test for npm package publishing, following the tutorial: https://www.youtube.com/watch?v=4zzbNac6f6Q.



Get perfect shadows every time for the non-designer.



# Installation

`npm i -D npm-shadowizard`


Then...

```
import {shadowizard} from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
});


```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* - _string_ (hard/soft) = soft
* *padding* - _bool_ = false
