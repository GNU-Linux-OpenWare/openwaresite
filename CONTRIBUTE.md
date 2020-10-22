## CONTRIBUTION GUIDE

#### The Workflow
Fork the repository and then clone from your end using:-
 
```git clone https://github.com/yourusername/openwaresite.git```

Work on your local repo then push to your remote repo using:-

``git push -u orign main``

Finally submit a Pull Request to the ``slave`` branch and await review. 

The maintainers should then review the commits of the PR on the ``slave`` branch and merge the commits to the ``main`` branch only if the following conditions are met:-
- The PR has no pending changes that had been requested
- It is up-to-date and has no conflict with the current `main` branch
- It is a valid fix/feature/addition 

After the PR has been reviewed and merged, each team member should pull the new changes to their local repo and push them back to their remote repo using:-

``git pull https://github.com/GNU-Linux-OpenWare/openwaresite.git``

``git push origin main``

**NOTE** 
- All PRs must be submitted to the ``slave`` branch and NOT the ``main`` branch.
- Commit messages should be concise and describe each change i.e each commit should make a change to just one aspect of the project.