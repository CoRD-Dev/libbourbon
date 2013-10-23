[![Bourbon](http://bourbon.io/images/shared/bourbon-logo.png)](http://bourbon.io)

Bourbon is a comprehensive library of sass mixins that are designed to be simple and easy to use. 
No configuration required.  

The mixins aim to be as vanilla as possible, meaning they should be as close to the original CSS syntax as possible.

The mixins contain vendor specific prefixes for all CSS3 properties for support amongst modern browsers. 
The prefixes also ensure graceful degradation for older browsers that support only CSS3 prefixed properties. 
Bourbon uses SCSS syntax.


## Requirements
- Sass 3.2+

## Install Instructions

Install [SASS](http://sass-lang.com/).

`cd` to your projects local repository and run:

```bash
git submodule add https://github.com/CoRD-Dev/libbourbon.git sass/bourbon
```
(`sass/bourbon` should be the directory your sass/scss files are kept +/bourbon.)

The generated folder will contain all Bourbons files.

Import Bourbon at the beginning of your stylesheet(s). All additional imports should be below Bourbon:

```scss
@import "bourbon/bourbon";

// All other imports
```

(Optional) Install [Neat](https://github.com/CoRD-Dev/libneat#install-instructions) and [Bitters](https://github.com/CoRD-Dev/libbitters#install-instructions).


#### Other Commands
Visit the [Command line tools wiki](https://github.com/thoughtbot/bourbon/wiki/Command-Line-Tools) for a complete list

    bourbon help
    bourbon update
    
##### [Bourbon v2.x install instructions](https://github.com/thoughtbot/bourbon/wiki/Bourbon-v2.x-or-Rails-2.3-Install)

-------
# [Changelog](https://github.com/thoughtbot/bourbon/wiki)

# [Browser support](https://github.com/thoughtbot/bourbon/wiki/Browser-Support)
-------

Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)

Bourbon is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community)

The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Got questions? Need help? Tweet at [@phillapier](http://twitter.com/phillapier).

License
-------

Bourbon is Copyright © 2011-2013 thoughtbot. It is free software, and may be redistributed under the terms specified in the LICENSE file.
