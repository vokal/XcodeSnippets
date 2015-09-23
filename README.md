iOS_SharedSnippets
==================

This is a repository for code snippets that members of the iOS team have found useful.  

###Configuration
Below is our recommended setup:

1. Create your own fork of this repository. Don't create a local clone, the plugin will do this automatically. 
2. Open [Alcatraz](http://alcatraz.io/), or install it if you haven't already, and install the plugin [ACCodeSnippetRepositoryPlugin](https://github.com/acoomans/ACCodeSnippetRepositoryPlugin).
3. Once installed there should be a "Plug-ins" menu bar item, select "configure snippets repository."
![ScreenShots](Screenshots/screenshot01.png)
4. Update the "remote repository" field to be your fork of iOS_SharedSnippets.  Then click on "Fork" to clone this repository locally and pull down all of the vokal snippets. (its a [known issue](https://github.com/acoomans/ACCodeSnippetRepositoryPlugin/issues/8) that this should be "clone".)
![ScreenShots](Screenshots/screenshot02.png)
5. Click on "Show in Finder". This is the local git repository the plugin created to commit all the changes made to your snippets in Xcode.  It will also push these changes up to the fork that you entered.  If you want to make any changes to your branch do it here – including the cleaning the git history and removing snippets before making a Pull Request.
6. *Optional* Click on "Import" to commit any custom snippets that you have to your repository. (NOTE: This currently imports all of the system snippets as well so if you don't want those saved in your repository you'll need to remove them manually.) 


If you have any other Snippets that you would like to share make a Pull Request!