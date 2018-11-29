```js
var RevealMenu = window.RevealMenu || (function(){
	var config = Reveal.getConfig();
	var options = config.menu || {};
	options.path = options.path || scriptPath() || 'plugin/menu/';
	if (!options.path.endsWith('/')) {
		options.path += '/';
	}
	var loadIcons = options.loadIcons;
	if (typeof loadIcons === "undefined") loadIcons = true;
	var initialised = false;
	
 }
 ```

footnote : "<a style='text-decoration: none; color: white;' href='#/12'>Learn More</a>"


