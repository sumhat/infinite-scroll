Infinite Scroll from Jetpack
===============

Standalone version of Infinite Scroll from Jetpack.

I need only this functionality from Jetpack, so I forked and maintain a copy
from Jetpack source.

This has also been uploaded as [a WordPress plugin](https://wordpress.org/plugins/infinite-scroll-from-jetpack/).

Command to fork a Jetpack module:

git clone https://github.com/Automattic/jetpack.git
cd jetpack/
git filter-branch --subdirectory-filter modules/infinite-scroll/
cd ..
git remote add -f jetpack jetpack/
git pull jetpack
git push
