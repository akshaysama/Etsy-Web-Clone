# Etsy-Web-Clone
to export a json file to the javascript file we need to modularise the files and tell the index.html that it is a module
for that add type = "module" within the script tag
/////
also create a package.json file and within it in json format add "type":"module" in case you are importing a javascript array instead of a json
/////
use import statement to import the json data to your file also use assert{type:'json'} with the import since we need to sanction the content type or the brawser will log an error message
