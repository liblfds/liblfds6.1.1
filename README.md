## Moved Away From GitHub

As promised, I have now moved off of GitHub as it became MS.

I have implemented git hosting on `liblfds.org`.

Please replace your GitHub URLs with one of the following;

* git clone git://liblfds.org/[reponame]
* git clone https://liblfds.org/git/[reponame]

The list of reponames is;

* liblfds6.0.0 : liblfds6, but moved to the new namespace scheme
* liblfds6.1.0 : maintenance release
* liblfds6.1.1 : bug fix release, supersedes 6.1.0
* liblfds7.0.0 : new release
* liblfds : this is in fact all releases up to and including 7.1.0
* liblfds7.1.1 : bug fix release, supersedes 7.0.0 (this repo is 7.1.1 only)

The repos have been kept *exactly* as they are on GitHub, so that systems performing git operations need only change the URL they clone from.

Please note these repos are read-only. Actual development work is done in SVN.

The high-level repo organization is a complete and utter mess.

A new, single, repo will be produced for 7.2.0, which contains all releases, and that repo will have new versions added into it, so there will be only the one repo.
