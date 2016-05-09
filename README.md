# j-preview-upload
This is the jquery drop and drop image upload with preview image. This plugin is fully customizable, very simple and easy to use.

####This is the simple preview before and after you choose image file

![preview screenshot](https://github.com/waiyanhein/j-preview-upload/blob/master/preview_image.png)
###Note
```
Design is fully customizable. So you can set whatever image or color or size you want for preview.
It will automatically check for the png,jpg,jpeg and gif extension for preview image.
```

###Usage
```
Download and include j-preview-upload.min.css file in your html.
Include jquery after css file.
Download and include j-upload-preview.min.js and follow the instructions below.
```

###This is the example of HTML markup

```html

<div class="j-preview-upload" id="upload-container">
     <img src="path/to/preview_image" />
     <input type="file" class="upload-file" />
</div>

```
###NOTE
```
In the above HTML, #upload-container is the preview container. You can customize the design by overriding the CSS.
You can customize in the JS code as well using the options(Described below)
Container must have the class name 'j-preview-upload'
```

###This is how to initialze it in JS
```html
$(function(){
	$('#upload-container').jPreviewUpload()
})
```

###Options
#####1. border_radius
#####2. width
#####3. height
#####4. padding

###Example of using options
```html
$('#upload-container').jPreviewUpload({ width:"400px",height:"200px" })
```
