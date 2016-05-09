# j-preview-upload
This is the jquery drop and drop image upload with preview image. This plugin is fully customizable, very simple and easy to use.

####This is the simple preview before and after you choose image file

![preview screenshot](https://github.com/waiyanhein/j-preview-upload/blob/master/preview_image.png)
###Note
>Design is fully customizable. So you can set whatever image or color or size you want for preview.

###Usage
```
Download and include j-preview-upload.min.css file in your html.
Include jquery after css file.
Download and include j-upload-preview.min.js and follow the instructions below.
```
###Validation for client side
```
You need to be done it yourseif in client side cause I want this plugin fully customizable. But in the future, I will add it.
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
