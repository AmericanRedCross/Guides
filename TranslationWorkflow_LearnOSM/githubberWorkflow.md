Workflow for GitHubber Team Member
==================================

You want to help translate the information on LearnOSM into an additional language? That's awesome! You are helping make a great resource accessible to a much wider audience. You will be coordinating with Translator team members who will do most of the translation work. Your technical skills will allow them to contribute. Feel free to also help with translating! 

Getting Ready
-------------

- Create a GitHub account if you don't have one
- Review GitHub
	- Read through the [introductory documentation](https://help.github.com/categories/54/articles)
	- ** coming soon: brief explaination of relevant github concepts with links instead of just the one link to the bootcamp help article **
- Download a text editor for code if you don't have one
	- One of many options is [Sublime Text](http://www.sublimetext.com/)
- Review Markdown
	- The chapters of content on LearnOSM are formatted using Markdown
    - Wikipedia has an [entry](http://en.wikipedia.org/wiki/Markdown) on Markdown
    - [http://markdown.pioul.fr/](http://markdown.pioul.fr/) shows a side-by-side comparison of what you're typing and how it is interpreted for display on a website
- Review the translator workflow
	- You should understand their role and activities
    - You may need to provide technical assistance
    
Preparing the Folders and Files
---------------------------------

- [Fork](https://help.github.com/articles/fork-a-repo) the Learn OSM repository at [https://github.com/hotosm/learnosm](https://github.com/hotosm/learnosm)
- Make a copy of the 'learnosm/_posts/en' folder
	- The '_posts' folder contains the files for the various pages of content
- Rename the copy of the 'en' folder using the ISO 639-1 Code for the target language
    - If the target lanuage only has an alpha-3/ISO 639-2 Code, use it instead
    - List of [language codes](http://www.loc.gov/standards/iso639-2/php/code_list.php)
- ** coming soon: explaination of .md files and chapters **
- Edit the metadata for each chapter
	- Open the file in a text editor
    - The metadata will be at the top
    - Change 'en' in permalink and lang to the code for the target language

Helping the Translator Get Started
----------------------------------

- Assist translator in creating a GitHub account
- Add the translator as a collaborator on the forked repository after they have created an account
	- Login to the GitHub website and open the page for your repository
    - Open 'Settings' and then go to 'Collaborators'
    - Add the translator's account
- Assign the translator a chapter
	- Give them the file name
    - Their workflow explains how to navigate to the file and make edits
- Answer any technical questions the translator may have
- If they encounter a problem with prose.io they may need your help to create a new issue on the (Prose GitHub issue page)[https://github.com/prose/prose/issues] 

Review and Quality Control
--------------------------
- Update the title in the metadata
	- The title should be at the top of the chapter text and should have been translated
    - Copy and paste it into the metadata
- Check links and images
- Check the markdown syntax and make sure the page is displaying correctly

** coming soon: details on links and images **

Updating Images
---------------

You may have noticed that some of the images have English text included. Editing these will require the use of an image editing software. You might need to take new screen shots, etc. 

** coming soon: more details about editing images, coordinating with translators, properly renaming the files, saving to the right location ** 

Adding the Translation to LearnOSM
----------------------------------

- Issue a [pull request](https://help.github.com/articles/using-pull-requests) to incorporate the work done on your forked repository into the main LearnOSM repository
- [LearnOSM](http://learnosm.org/) is hosted using [GitHub Pages](http://pages.github.com/) and once your pull request is accepted the changes to the learnosm gh-pages branch automatically update the site within minutes
- It is a good idea to review the pages again once uploaded to the main site
	- Check for formatting errors, images that don't load, and broken links

** coming soon: overview of pull requests specific to this scenario ** 

	