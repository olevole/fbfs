fbfs
====

FreeBSD BFS scheduler

Based on "gsoc 2011 - porting BFS to FreeBSD": http://rudot.blog.com/latest-patch-available/

Please note:

- The current version has nothing to do with the Linux version of the BFS
- Current maintainer for this patch ( not for original gsoc 2011 version ): Ivan Klymenko ( fidaj at ukr dot net )
- Thread dedicated to this patch (russian): http://www.bsdportal.ru/viewtopic.php?f=7&t=24660

Applying patch:

        cp fbfs_10.0-STABLE.patch /usr/src
        cd /usr/src
        patch -p1 < fbfs_10.0-STABLE.patch

