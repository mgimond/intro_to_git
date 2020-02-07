## Installing git

For **Windows**, download and install git from https://gitforwindows.org/. Go with the default settings. 

For **Macs**, install Git from  http://git-scm.com/downloads. Go with the default settings. 

## Configuring git

You only need to follow this step once on your machine. This step adds your contact information that will be used when uploading your R and Rmd scripts to Github.

Bring up the git shell (this may appear as the **Git Bash** application). You can also access the shell from inside RStudio by clicking on the Terminal tab in the lower left-hand pane.

```{r}
git config --global user.name 'Jane Doe'
git config --global user.email 'jdoe@colby.edu'
```

To check your settings, type:

```{r}
git config --global --list
```