# Wysbb-Editor
New editor forumotion

## Usage
Include the WysiBB files in the <head> of your html
```html
<script src="https://cdn.rawgit.com/matran991/Wysbb-Editor/master/imgur.js"></script>
<script src="https://cdn.rawgit.com/matran991/Wysbb-Editor/master/wysibb.min.js"></script>
<link rel="stylesheet" href="https://cdn.rawgit.com/matran991/Wysbb-Editor/master/wysibb.css" />
```
Activate WysiBB on an existing textarea. Example: 

```html
<script>
$(document).ready(function() {
   $("#editor").wysibb({
    buttons: "bold,italic,underline,fontcolor,|,fontsize,|,fontfamily,|,table,img,video,link,upimg,|,justifyleft,justifycenter,justifyright,|,bullist,numlist,|,quote,code,spoiler,removeFormat",
    scroll:true,
    clientid:'cc86a8de340e7c459'
  });
})
</script>
<textarea id="editor" name="editor_name">My text</textarea>
```

## Option

    +------------+----------+-------------------+----------------------------------+
    | Parameters | Classify |      Default      |               Note               |
    +------------+----------+-------------------+----------------------------------+
    |   scroll   |  Boolean |       true        | Turn auto scroll toolbar editor  |
    +------------+----------+-------------------+----------------------------------+
    |  clientid  |  String  | cc86a8de340e7c459 |      Client ID app imgur.com     |
    +------------+----------+-------------------+----------------------------------+

## Credit

Copyright 2014 WysiBB (evo) and Author: Vadim Dobroskok
