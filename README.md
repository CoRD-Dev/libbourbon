[![Bourbon](http://bourbon.io/images/shared/bourbon-logo.png)](http://bourbon.io)

Bourbon is a comprehensive library of sass mixins that are designed to be simple and easy to use. 
No configuration required.  

The mixins aim to be as vanilla as possible, meaning they should be as close to the original CSS syntax as possible.

The mixins contain vendor specific prefixes for all CSS3 properties for support amongst modern browsers. 
The prefixes also ensure graceful degradation for older browsers that support only CSS3 prefixed properties. 
Bourbon uses SCSS syntax.


##Requirements
- SASS 3.2+

##Installation
Install [SASS](http://sass-lang.com/).

`cd` to your projects local repository and run:

```bash
git submodule add https://github.com/CoRD-Dev/libbourbon.git sass/bourbon
```
(`sass/bourbon` should be the directory your sass/scss files are kept +/bourbon.)

The generated folder will contain all Bourbons files.

Import Bourbon at the beginning of your stylesheet. 
All additional imports should be below Bourbon:

```scss
@import "bourbon/bourbon";

// All other imports
```

(Optional) Install [Neat](https://github.com/CoRD-Dev/libneat) and [Bitters](https://github.com/CoRD-Dev/libbitters).


##Credits
![thoughtbot](http://thoughtbot.com/images/tm/logo.png)

Bourbon is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/). Follow [@thoughtbot](http://twitter.com/thoughtbot) on Twitter.

libbourbon is maintained by [CoRD](http://cord-dev.github.io/) and [The_Catman](http://catmanix.github.io/).

##License
Bourbon is Copyright © 2011-2013 thoughtbot. It is free software, and may be redistributed under the terms specified in the LICENSE file.
