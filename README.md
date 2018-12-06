git-nb

A jupyter notebook for cloning, pulling, adding and pushing git repositories to and from github using the %%bash cell magic.

The idea is to reduce the burden for my students so they don't have to have a separate application or terminal open to manage their repositories.

I'm imagining them having this file in the parent directory for the local copy of their project repository.  They edit the github url and repository name, then clone the repo and cd into it.  Then they open the newly created folder in the jupyter lab file browser and work on project files there -- this allows them to have the git controls and the project work running in the same browser tab, in different tabs of the jupyter lab instance.

When they have completed some work, they go back to the git-nb tab, add the changes to the repo, commit them with a message, then push to github.

This process assumes that they have already established ssh keys and use the ssh clone url from github as the origin, and probably assumes that we never work with different branches.
