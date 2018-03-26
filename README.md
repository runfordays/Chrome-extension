# Chrome Extension

This is an extension that I would to have the basic needs in an extension.
Hopefully the extension will be able to change the background of your chrome
browser periodically, be able to have a timer, and a to do list.

#How to make one

To make an extension make a folder and name a file in it called manifest.json.
Once you made that file put this code in the file:

 {
	"manifest_version": 2,
	"name": "My Cool Extension",
	"version": "0.1",
	"content_scripts": [{
		"matches": [
			"<all_urls>"
		],
		"js": ["jquery-3.3.1.js", "content.js"]
	}]
}  
