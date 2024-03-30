# j-preview-upload
This is a jQuery drag and drop image upload plugin with a preview image feature. The plugin is fully customizable, very simple, and easy to use.

#### This provides a simple preview before and after you choose an image file.

![preview screenshot](https://github.com/waiyanhein/j-preview-upload/blob/master/preview_image.png)
### Note
```
The design is fully customizable, allowing you to set whatever image, color, or size you want for the preview.
It will automatically detect the png, jpg, jpeg, and gif extensions for the preview image.
```

### Usage
```
Download and include j-preview-upload.min.css file in your html.
Include jquery right after including the css file.
Download and include j-upload-preview.min.js and follow the instructions below.
```

### This is the example of HTML markup

```html

<div class="j-preview-upload" id="upload-container">
     <img src="path/to/preview_image" />
     <input type="file" />
</div>

```
### NOTE
```
In the above HTML, #upload-container is the preview container. You can customize the design by overriding the CSS.
You can also customize the styling in the JS code or using the options (described below).
Container must have the class 'j-preview-upload'
```

### Initialisation
```html
$(function(){
	$('#upload-container').jPreviewUpload()
})
```

### Options
##### 1. border_radius
##### 2. width
##### 3. height
##### 4. padding

###Example of using options
```html
$('#upload-container').jPreviewUpload({ width:"400px",height:"200px" })
```
