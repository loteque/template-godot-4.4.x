### what??
This is a repository where I keep all the common files 
needed to start a Godot 4.4 project.

### recomended usage!
- clone this into a template directory within you home 
directory
- copy the files over to your project repo
- run project.sh 
- update the godot link to point to your 
version of godot
- add whatever files you need to ignore to the .gitignore
- edit readme.md to describe your project and remove this info


### why?
I started this repo because I found I was hunting around projects
to copy basically the same files over and over again at the start
of each new project. This is a simple solution to this problem 
and I hope it helps others too.


The reason that we don't start a project from a clone of 
this template is because these things only really need to 
be done once to init a project correctly, meaning that we
don't need to keep pulling this template from github. We 
only need to pull the template when starting a new project 
to get the updated version of the template.
Likewise if we have already started a project and want to 
add these features to the project we can just update the 
template files seperately and copy them over negating the 
need for complexities like git submodules or git subtrees.


### contribute:
If you would like to contribute please fork and then follow the 
above steps, contributing back through pull requests from
your fork, thanks.


### what's in here?
- a `readme.md` file with instructions on how to use the template
- a `.gitignore` file that ignores all files that are not needed in vcs
- a `project.sh` script that sets up a project:
    - at the project level, sets git to update submodules on `pull`