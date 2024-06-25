# Andon Tchechmedjiev' academic page

This repository hosts the sources of my academic webpage. 
This is a custom adaptation of a static https://html5up.net/ template that has been heavily modified and stripped down. 

I have also developed scripts to extract publication records from HAL and to automatically generate a publications HTML page, 
as well as generating a directory structure for publication specific pages. 

The site itself it purely static HTML with minimal javascript. All the files from the site that are deployed are located in site_root.
The main css file is in src/ as the one that is deployed is minified first. 

To build the site, use `npm build` and to deploy `npm deploy`. The site is holted on the excellent https://xmit.co/ provider. 



