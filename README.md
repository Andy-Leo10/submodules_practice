# submodules_practice

After cloning your repo on your local PC, add the submodules with:

    git submodule add https://github.com/yourusername/myrepo.git

To update with the content all the submodules use inside root:

    git submodule init
    git submodule update

When changes were made to a submodule do this

    git checkout main
    git push origin main

---

Then for new updates use:

    git submodule update --remote

