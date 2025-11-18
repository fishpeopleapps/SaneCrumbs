# SaneCase

## Description
This extension is a mirror of the SaneCase extension publically available from MediaWiki, written by Martin Tournoij. 
https://www.mediawiki.org/wiki/Extension:SaneCase
This mirror contains the necessary composer file needed to include it in the Space-Wiki. 

## Installation
1. Add via composer locally - updating your composer.json and composer.lock file
2. Add extension via a COPY statement in the Dockerfile
3. Enable extension in the LocalSettings.php file

## Usage
The SaneCase extension automatically corrects case mistakes. For example if the page Test exists, and someone goes to TEST, they will be automatically redirected to Test with a 301.

## Support/Roadmap
This extension is pretty cut and dry and will probably be used to house other misc. hooks and php files we want to implement into the wiki. 

## Project status
n/a

