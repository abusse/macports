# My Private Portfile Collection

This repository collects all my Portfiles that are not available in the official repository. To use it, put it in your sources directory, e.g., `${prefix}/var/macports/sources/github.com`. If you want to fetch the latest changes of the repository with the automatic update of Macports use SVN for it:

`sudo svn co https://github.com/abusse/macports/trunk ${prefix}/var/macports/sources/github.com`

Finally, add the following line to your `${prefix}/etc/macports/sources.conf`:

`file:///opt/local/var/macports/sources/github.com`