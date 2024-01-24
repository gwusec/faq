# FAQ
Frequently Asked Questions


## What should I name my repository?
 
  We have a suggested naming scheme for lab repositories. 
  ```
  YYYY-short-descriptor
  ```
  
  Where `YYYY` is replaced with the year the repository is created and `short-descriptor` is a few words, no more than 4 or so, that describes the project. You should use hyphens `-` for white space. Please no white space in repository names.
  
## How should I organize my repository?

  There is an art to organizing repositories, but inevitably, as the project goes on, they will become a mess. I suggest the following basic organization that has worked for me ... until it becomes a mess
  
  ```
  scripts/  : directory for short scripts that process data
  papers/   : directory of paper writing
  data/     : any relevant data to the project
  res/      : any results 
  web/      : any web developement for the project
  viz/      : any data visualization
  dev/      : any other development for the project.
  ```
  
## Do I need all those directories in every repository? 

No. You can start from less, or none, but once the repository gets big enough ... it might be useful to use the structure. 

## Is there a policy on branching and pushing branches?

  Branch away, but there are two branch names that are reserved:
  * dev : should be used for any inprogress development that isn't ready for the master branch
  * production: should be used for any user/participant ready development that can be launched to a webpage
  
  As the branch names suggest. A `dev` branch should lead the `master` branch while the `production` should trail. 
  
## Should repositories be public or private?

All repositories should be private, unless we are doing releases from the lab. 


## Should I add a .gitignore file?

Yes please! Adding a .gitignore file allows you to specify intentionally untracked files to ignore and helps to keep your repository free from clutter. For example, compiled code, operating system files, and IDE configuration files should not be committed to git repositories. 

The web site [https://www.gitignore.io](https://www.gitignore.io) is a useful for generating an extensive .gitignore file. 

An example of a good .gitignore file for a Java based web project would be:  <br />
[https://www.gitignore.io/api/vim,java,macos,emacs,windows,java-web,jetbrains+all,latex](https://www.gitignore.io/api/vim,java,macos,emacs,windows,java-web,jetbrains+all,latex)
  

## I want to be added to the gwusec lab page?

Great. Feel free to submit a pull request. 

## I want a VM of my own?

Check out the vmware-faq page. 

## I want to add a Google API sign-in to my survey application?

The [Google Sign-In Guide](https://developers.google.com/identity/sign-in/web/sign-in) is a good place to start.

**Important:**  [Disconnect and revoke scopes](https://developers.google.com/identity/sign-in/web/disconnect) when the survey participant has completed or withdrawn from the survey.

## Can I add items to this FAQ?

   Yes! Submit a pull request and they can be added in easily. 

  
