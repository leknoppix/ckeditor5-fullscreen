Fullscreen for CKEditor 5 classic editor build


```
npm i -D @ckeditor/ckeditor5-core
npm i -D @ckeditor/ckeditor5-ui
```



Include in your ckeditor.js

```
import FullScreen from './FullScreen';
```

Include in the plugin List
ClassicEditor.builtinPlugins = [
	....
	FullScreen,
];
```

And include it in your toolbar
```
ClassicEditor.defaultConfig = {
	toolbar: {
		items: [
			.....,
			'fullScreen'
		]
	},
```
