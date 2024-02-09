# submodules_practice

After cloning your repo on your local PC, add the submodules with:

    git submodule add https://github.com/yourusername/myrepo.git

To update with the content all the submodules use inside root:

    git submodule init
    git submodule update

When changes were made to a submodule do this setup first:

    git checkout main

Then inside any Repo use it as usual

---

Then for new updates use:

    git submodule update --remote


For manual push use:

    git push origin main