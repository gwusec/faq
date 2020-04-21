# FAQ
Frequently Asked Questions


1. What should I name my repository?
 
  We have a suggested naming scheme for lab repositories. 
  ```
  YYYY-short-descriptor
  ```
  
  Where `YYYY` is replaced with the year the repository is created and `short-descriptor` is a few words, no more than 4 or so, that describes the project. You should use hyphens `-` for white space. Please no white space in repository names.
  
2. How should I organize my repository?

  There is an art to roganizing repositories, but inevitably, as the project goes on, they will become a mess. I suggest the following basic organization that has worked for me ... until it becomes a mess
  
  ```
  scripts/  : directory for short scripts that process data
  papers/   : directory of paper writing
  data/     : any relevant data to the project
  res/      : any results 
  web/      : any web developement for the project
  viz/      : any data visualization
  dev/      : any other development for the project.
  ```
  
3. Is there a policy on branching and pushing branches?

  Branch away, but there are two branch names that are reserved:
  * dev : should be used for any inprogress development that isn't ready for the master branch
  * production: should be used for any user/participant ready development that can be launched to a webpage
  
  As the branch names suggest. A `dev` branch should lead the `master` branch while the `production` should trail. 
  
4. Can I add items to this FAQ?

   Yes! Submit a pull request and they can be added in easily. 

  
