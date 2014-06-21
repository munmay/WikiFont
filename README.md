Current
----

![Image of Yaktocat](./Screenshot-current.png)

WikiFont is a project by the Wikimedia Foundation.
 * [MediaWiki page](https://www.mediawiki.org/wiki/Design/Wikifont) -- community's introduction
 * [Trello page](https://trello.com/c/rClBTMWE/26-wikifont-tracking) -- talks & todo
 * [Github page](https://github.com/munmay/WikiFont/) -- developement base, last code, & issues

Minimal HTML code
----
This minimal `demo.html` requires the font files and `font.css` of this repository.

````
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>WikiFont minimal code</title>
    <link rel="stylesheet" href="font.css">
    <style>
	  i { 
	    font-family: WikiFont-Regular; 
	    font-size: 3em;
	    font-style: normal;
	  }
	</style>
  </head>
	<body>
		<i class="WikiFont-puzzle"></i>
		<i class="WikiFont-bookmark"></i>
		<i class="WikiFont-wikitrail"></i>
		<i class="WikiFont-gear"></i>
		<i class="WikiFont-user-face-smile"></i>
		<i class="WikiFont-pencil"></i>
		<i class="WikiFont-image-add"></i>
		<i class="WikiFont-link"></i>
		<i class="WikiFont-quotes-add"></i>
		<i class="WikiFont-speech-bubbles"></i>
		and so on.
	</body>
</html>
````

Credit & License
----
Munmay (WMF), released under the Modified BSD License. See LICENSE.
