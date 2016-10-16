Ng Emoji Picker
======================

Ng Emoji Picker is an angular directive for [Emoji Picker](https://github.com/OneSignal/emoji-picker), with the following modifications:

* **Removing wysiwyg editor Support**
* **Dynamic location for picker menu**
* **Moving Emoji images to /assets/images/ng-emoji-picker**


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
#### Copy Assets:
clone the img folder and place it in /assets/images/ng-emoji-picker

#### Basic Example:
```
<input emoji-picker type="text" ng-model="chat.message"/>
```

#### Full Example
```
<textarea emoji-picker ng-model="chat.message" emoji-attachment-location="bottom right" emoji-menu-location="top left" ng-keydown='handleKeyDown($event)'></textarea>
```
#### Style the emoji picker
Just add the following css 
```
 .emoji-picker-icon{
    font-size:20px;
    right: 86px;
    top: 17px;
  }
```

#### Options:
* **emoji-attachment-location**
* **emoji-menu-location**
* --check [Tether.js](http://tether.io/) to know all the aligment tricks


### Bugs and feature requests
If you found a bug or have an idea feel free [to open a new issue](https://github.com/kimooz/ng-emoji-picker/issues/new).

```
