# EasyEmbed
> 1.0.2

EasyEmbed is a small and fast jQuery plugin which allows you to embed Youtube videos with standard definition thumbnail fallback into your web page. All the parameters can be passed via Html5 data attributes without the need to write any javascript.

### Features
  - YouTube video embedding
  - Standard definition thumbnail fallback

### Installation
######Bower
```
bower install easyembed --save
```

### Initialization
Initialization can be done in two ways, either by a html data tag, or by JavaScript
######HTML
```
<div data-easy-embed></div>
```

######JavaScript
```
<div id="easy-embed"></div>
$('#easy-embed').easyEmbed();
```

### Overlay
Making a custom overlay has never been easier. Just create your elements inside the EasyEmbed element and style away.
```
<div data-easy-embed>
    <div class="overlay">PLAY</div>
</div>
```

### Options
Options can be applied in the same two ways as the initialization, by html data tags, or by JavaScript
######HTML
```
<div data-id="VIDEO_ID" data-easy-embed></div>
```

######JavaScript
```
$('#easy-embed').easyEmbed({
    id: 'VIDEO_ID'
});
```
Option | Type | Default | Description
------ | ---- | ------- | -----------
id | string | ScMzIvxBSi4 | ID of the wanted video
controls | boolean | false | Show player controls
info | boolean | false | Show video title and player actions
thumbnail | string | auto | Image path to override automatic thumbnail


### Todo's
* Better documentation

Don't hesitate to request missing features