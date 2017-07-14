Program Analysis and Compilation Group @MIT Website
====================================================
This site is built using Jekyll.

People
------
To add yourself, please put in pull request that modifies `_data/people.yml` with
the appropriate information. At a minimum, add your name and your personal website.

Publications
------------
To add a new publication, you should add the bibtex to `bib/pubs.bib`.

Deploying
---------
To see changes reflected on the website, you should call `make` and then commit changes
to git and push to github.

You may need to install the python dependencies needed to put together the publications. If so,
you can just run `./instally_python_deps.sh` to install them. This assumes you have `pip` installed.
