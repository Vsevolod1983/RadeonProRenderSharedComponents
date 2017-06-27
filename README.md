# RadeonProRender Shared Components

This repository contains code that can shared among various RPR integration plugins.  RPR plugins
are implemented in a number of programming languages so the directory structure distinguishes
the code type being used.

To pull this repository, do the following:

1. Change to the top level of the plugin repository
2. mkdir FireRender.Components  # if directory does not exist
3. git subtree pull --prefix FireRender.Components https://github.com/Radeon-Pro/RadeonProRenderSharedComponents.git --squash
4. git commit --amend  # To change "Merge commit (SHA-1 hash)" to a more descriptive commit such as:
	"git subtree pull latest FireRender.Components shared code"
5. Save and close the commit text file to register the change

