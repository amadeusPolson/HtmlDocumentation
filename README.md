Documentation
=============

This repo contains all the custom documentation per-project.  To add a file:

1) Copy the html and images folder from ~/Example into your new directory.
2) Open a command prompt in your new directory and run: 
	git submodule add git@github.com:amadeusPolson/DocumentationTemplate.git.
	- This command will download the most up-to-date resources used for creating
	and rendering the html documentation.
3) Edit the html file to your liking.  Any custom javascript or css should be
	added on your own, _not_ to the DocumentationTemplate folder.

Note: If you want to update the template module in a given documentation project,
	navigate to the DocumentationTemplate directory of the given project and run:
	git pull