# diffuse

GitHub import of https://svn.code.sf.net/p/diffuse/code - the source to the
diffuse diff viewer, with official home page at
http://diffuse.sourceforge.net/.

Summary of changes against upstream:
* Added a `-M <rev>` option that can be used with git to view the diffs between the commit ref `<rev>` and staging.

To get started with our diffuse:
* Clone this repo,
* and add `src/usr/bin/diffuse` to PATH, e.g. by adding a symlink at `~/bin/diffuse`.
