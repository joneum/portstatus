# portstatus

Issue tracker for [portstatus.bsdproject.de](https://portstatus.bsdproject.de),
the CVE and update status of the FreeBSD ports tree.

This repository holds no source code. The site is developed elsewhere; this
is where you report problems with it.

## What belongs here

- **Wrong or missing data**: a CVE matched to the wrong port, a CVE that is
  missing, a fixed version that is wrong, an outdated status.
- **Problems with the site**: broken pages, wrong links, display issues.
- **Ideas** for the site.

The quickest way is the **Report** link on the page in question: it fills in
the port, the CVE and the address for you.

## What does not belong here

- **Problems with a port itself** (build failures, a missing update, a port
  that needs a fix): FreeBSD Bugzilla, <https://bugs.freebsd.org/>.
- **Missing or wrong VuXML entries**: the FreeBSD ports security team,
  <ports-secteam@FreeBSD.org>.
- **Security problems of the site itself**: please report them privately,
  see [SECURITY.md](SECURITY.md).

## Where the data comes from

The FreeBSD ports tree and package indexes, VuXML, the NVD, the CVE List
(cvelistV5), Repology and FreeBSD Bugzilla. The
[About page](https://portstatus.bsdproject.de/about) explains how ports and
CVEs are matched and what each status means.
