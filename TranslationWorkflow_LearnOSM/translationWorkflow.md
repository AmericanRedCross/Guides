
Translation Workflow for LearnOSM.org
=====================================
[LearnOSM](http://learnosm.org/) provides easy to understand, step-by-step guides for you to get started with contributing to OpenStreetMap and using OpenStreetMap and using OpenStreetMap data. Although the site was originally written in English, volunteers have translated the various pages into several languages. These include [Bahasa Indonesia](http://learnosm.org/bi/), [Japanese](httP://learnosm.org/jp/), and others. This document is meant to provide an overview of the process for translating the pages into a new language.  

Participant Roles
-----------------

1. __Githubber__
    - Requirements:
        - a moderate level of technical ability (e.g. using text editors to create/modify website content) or a serious desire and committment to learn
	    - learn how to use [GitHub](https://github.com/) and learn basic Git theory
	    - ability to troubleshoot and/or ask for help since even detailed documentation cannot cover every possible issue    
    - Responsibilities:
    	- initial setup of the new pages
	    - overseeing the work of the the translator and assisting with problems 
        - modifying some of the hidden elements of the translated pages for proper intergration into the main site
        - quality control and review
        - submit pull requests when ready to go live with translation updates        
2. __Translator__
    - Requirements:
	    - learn the basic syntax of Markdown, for composing readable plain text that can be formatted for the web by a program 
        - firm grasp of English and the target language
    	- learn the user-friendly interface of [Prose.io](http://prose.io)
    	- _note: it is easy for multiple people to work as translators because the content of LearnOSM is divided among numerous different pages_
	- Responsibilities:
		- communicate with Githubber
    	- translate the English LearnOSM pages into target language

GitHubber Workflow
------------------
- Create a GitHub account if you don't have one
- Fork the Learn OSM repository at [https://github.com/hotosm/learnosm](https://github.com/hotosm/learnosm)
- Make a copy of the 'learnosm/_posts/en' folder
- Rename the 'en' folder using the ISO 639-1 Code for the target language
    - if the target lanuage only has an alpha-3/ISO 639-2 Code, use it instead
    - [list of language codes](http://www.loc.gov/standards/iso639-2/php/code_list.php)
- Assist translator in creating a GitHub account
- Add translator as a collaborator on the forked repository after they have created an account
	- login to the GitHub website and open the page for your repository
    - open 'Settings' and then go to 'Collaborators'
    - add the translator account
- Assign translator a task by    

Translator Workflow
-------------------
- Create a GitHub account if you don't have one
- Tell your username to the GitHubber so they can add you as a Collaborator
- Learn the basics of Markdown    
    - read the 'Syntax examples' in the [wikipedia entry](http://en.wikipedia.org/wiki/Markdown)
    - practice creating headings, paragraphs, lists, and emphasized text using [http://markdown.pioul.fr/](http://markdown.pioul.fr/) (the site will show you a side-by-side comparison of what you're typing and how it is interpreted for display on a website)
    - understand what external links and images look like (the GitHubber will edit links and images as necessary but you shouldn't delete these parts of the pages while translating)
- Learn the Prose interface
- Receive an assignment from the GitHubber and translate the content of the assigned page
- If you encounter a problem with prose.io either create a new issue on the [prose GitHub page](https://github.com/prose/prose/issues) or communicate the problem to the GitHubber so that they can report the isue
- 
    
    		




