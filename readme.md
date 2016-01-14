## Audio 

### Installation 
- Copy the folder audio to `ckeditor/plugins` folder
- Change `config.js` to add the plugin:
```
CKEDITOR.editorConfig = function( config )
{
	// Declare the additional plugin 
	config.extraPlugins = '**audio**';

	// Add the button to toolbar
	config.toolbar = [ 
	['Templates', 'Styles','Format','Font','FontSize','TextColor','BGColor','Maximize','Image'], 
	['Source'], 
	['Bold','Italic','Underline','Strike','-','Subscript','Superscript','-',**'Audio'**],
	['Table','HorizontalRule'], 
	['NumberedList','BulletedList','-','Outdent','Indent','Blockquote']
	] 
};
```

### About
This is only an adaptation of Video plugin for CKEditor created by Alfonso Mart�nez de Lizarrondo 
