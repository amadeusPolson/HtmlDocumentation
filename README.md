Documentation
=============

High level overview
-------------------
This project is intended to make your life easier when creating client-facing walk-throughs.
These walkthroughs should consist of steps and screenshots, and can then be zipped up and
sent to clients - though ideally we would just host them on an internal server for them to
link to.  The project consists of the external template (called a sub module in git)
and then the example html file & images folder which all new documentation should start from.
The template holds the general styling and scripting required to generate the walkthrough
layout.  e.g. the pagination is done for you depending on how many steps exist in the html file.

Instructions
------------
This repo contains all the custom documentation per-project.  To add a file:

1) Copy the html file and images folder from ~/Example into your new directory.
2) Open a command prompt in your new directory and run: 
	git submodule add git@github.com:amadeusPolson/DocumentationTemplate.git.
	- This command will download the most up-to-date resources used for creating
	and rendering the html documentation.
3) Edit the html file to your liking.  Any custom javascript or css should be
	added on your own, _not_ to the DocumentationTemplate folder.

Note: If you want to update the template module in a given documentation project,
	navigate to the DocumentationTemplate directory of the given project and run:
	"git pull".  And if you want to update the template module in each documentation
	project, run: "git submodule foreach git pull".