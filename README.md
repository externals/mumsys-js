# mumsys-js
MUMSYS Javascript Library

Currently only DTO/DAO objects available.

Server request require jQuery.ajax()

Build files in dist/Mumsys.min.js (without comments, minified version) or
dist/Mumsys.js for a single file including comments/ documentation.

Development goes in single files at src/.

Also have a look at the html files in tests/ folder to run tests or to get into it in
detail.

For distribution/ builds you can use composer:

    composer require flobee/mumsys-js

For own builds (requires php 5.6+, 7.* cli version):

    composer require flobee/mumsys-js
    cd vendor/flobee/mumsys-js
    composer install

to the get dependencies for builds.




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



