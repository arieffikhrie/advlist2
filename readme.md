## add custom class to tinymce advlist


Add this script after tinymce.js
`<script src="advlist2.tinymce.js"></script>`

Init tinymce
```js
tinymce.init({
	plugins: ['advlist2'],
	toolbar: 'bullist numlist',
	advlist_bullet_styles: 'disc | square | c:bullet-orange',
});

```
