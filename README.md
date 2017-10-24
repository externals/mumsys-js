# mumsys-js

this is a repo to hold different versions of mumsys-js you may need.

This master repo only hold this readme to upgrade the branches


# mumsys-js ready to run files
Downloaded from https://github.com/flobee/mumsys-js and set to the "packages" branch to have
the versions an application may need.
If you want several versions of mumsys-js this will be your primary branch to choose
    # git checkout packages

If you just need a special version then checkout the branch you need or create
a new branch including the version you want.
If you need several versions? Then merge it to the packages branch an switch
back to the packages branch.



# Examples/ Howto add new versions

## branch master
    ./README.(txt|md) (copy of this readme)


## branch of vA-B-C

    ./vA.B.C/Mumsys.js
    ...
    ./vA.B.C/README.(txt|md) (README of mumsys-js vA.B.C, Or History etc)
    ./README.(txt|md) (copy of this readme)

If a new version exists and you need it globaly/ in packages branch:
Don't drop other versions! Add your version to the packages branch or create
and checkout your version.

Eg: You need version 2.0.1 system wide:
checkout the master branch and create a new branch: "v2-0-1" (branches needs - NOT dots!)
create a folder: mkdir v2.0.1/
Download the file *.js/*.css to v2.0.1/
commit & push the new version branch

Then checkout the "packages" branch and merge your version into it. result:
Packages branch
    ./vA.B.C/Mumsys.js
    ./vA.B.C/README.(txt|md)
    ./v2.0.1/Mumsys.js
    ./v2.0.1/README.(txt|md)
    ./README.(txt|md) (copy of this readme on creation time)



# Changelog

    2017-10
        Adds Version v3.1.0



