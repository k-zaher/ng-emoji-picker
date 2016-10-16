NG Emoji Picker
======================

NG Emoji Picker is an angular directive for [Emoji Picker](https://github.com/OneSignal/emoji-picker), with some modifications in the original library.

Installation
------------

### Bower
using [Bower](http://bower.io/).

```bash
bower install ng-emoji-picker --save
```

This will install the latest release.


Usage
-----
```javascript
angular.module('myApp', ['ngEmojiPicker']);
```
#### Basic Example:
```
<input emoji-picker type="text" ng-model="chat.message"/>
```

#### Full Example
```
<textarea emoji-picker ng-model="chat.message" emoji-attachment-location="bottom right" emoji-menu-location="top left" ng-keydown='handleKeyDown($event)'></textarea>
```

#### Options:
* **emoji-attachment-location**
* **emoji-menu-location**
* --check [Tether.js](http://tether.io/) to know all the aligment tricks


### Bugs and feature requests
If you found a bug or have an idea feel free [to open a new issue](https://github.com/kimooz/ng-emoji-picker/issues/new).

```