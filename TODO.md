# Scripts to write

Someone suggested using Ansible to do all this repeatable setup. I think it was
Ansible - uses yaml config to specify what is needed.

 - setup for Haskell development
   - ghc, ghci
   - cabal
   - updated cabal
   - haskell mode for text editors
   - haskell syntax highlighting for text editors
 - setup for Helm development
   - depend on Haskell development script
   - share this script with Helm project people

# Things I did manually

Some of these I could not figure out how to do with scripts, others I just did
not have time to do the scripting.

 - Install Firefox plugin "One Tab" (plugin that converts sets of tabs into a
   summary page).
 - VPN connection with openVPN. I think I wrote about this in a google doc.
   I want to try the cisco stuff anyway as I hear it is better. This seems
   impossible to script, software just does not support it. May be possible
   with a bunch of manual work.
 - RPM for BlueJeans conferencing software. This is needed before using
   the bluejeans website for video conferencing. I could probably script it
   pretty easily with a hard-coded version, but having it download the latest
   may be trickier. It seemed to add a yum reporitory that I need to disable
   so I can look at just adding that repository and see if that is sufficient
   without downloading a hard-coded RPM version.


# Personal starting point

Something I run that presents me with options for the things I usually
want to do. Something like:

 - set up Fedora (this would be installing and configuring my usual software)
 - development (section or category, since there are several types)
   - per-project option, which presents some things I would want to do
     such as opening a folder in sublime, opening terminals at places,
     running servers and other programs, opening folders in the file viewer.
   - generic starter options for types of development, like making a new
     arduino johnny-five project, or a helm project.
