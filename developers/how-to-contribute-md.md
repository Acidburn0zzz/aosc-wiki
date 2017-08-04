<!-- TITLE: How To Contribute to This Wiki -->
<!-- SUBTITLE: A quick guide on Wiki contribution -->

# Preparing Your Content

Using Wiki.js, the Community Wiki is written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## Sections

As currently planned, our Community Wiki is arranged across 5 sections:

- Developers: This section contains guidebooks for AOSC developers, as well as more technically-inclined content for developers using AOSC OS.
- Users: This section contains information useful for AOSC OS users with pages arranged by topics.
- Errata: This section contains known *unresolved* issues found in AOSC OS for developers' and users' reference.
- Knowledge Base: This section contains pages describing resolved issues and commonly asked questions in AOSC OS.
- AOSA: This section lists all current and historic AOSC OS Security Advisories.

Thus, do consider in advance where your page should go - when in doubt, ask in our IRC channel #aosc.

# Writing pages

## Section-Specific Requirements

Here are some requirements and expectations specific to each of the sections defined above.

### Developers

No specific requirement yet.

### Users

- Each page should be arranged specific to its own topic, say, configuration of APT by `apt-gen-list` should be arranged into `/Users/System Administration/APT`, then `apt-gen-list.md`.
- Each page should at least contain the following...
	- General summary of the topic.
	- Section generalising related operations/usages.
	- Section listing all KB (Knowledge Base) and Errata pages related to this topic.
	- References, if any were used.

### Errata and Knowledge Base

Errata and Knowledge Base are two concepts defined in this wiki, and Erratas are essentially the incomplete form of Knowledge Base - or in another way, an Errata is a knowledge that could be obtained by developers and users alike regarding currently identified issues within AOSC OS, however, no solution is available yet for this issue; down the line when such issue was addressed with a system update, or with a workaround found by developers and/or users, an Errata added with solution/workaround will be moved and listed as a Knowledge Base article.

We won't lie however, that these two concepts are inspired by Microsoft Support, and Microsoft Knowledge Base Articles ([here](https://support.microsoft.com/en-us/help/927295) for an example) - and these page could look somewhat similar to those available to be obtained from Microsoft.

Thus, an Errata page should contain (and in principle, no more than):

- Symptom Summary of an issue, this section should be written to suit the ease of reading and understanding by a *layman* (say, your grandma who touched your PC with AOSC OS for the first time, a lovely lady who's greatly confused with the issues).
- Technical Details of such issue, this section should contain as much technical details as possible - even as far as snippets of codes.
- Cause, if already identified - if not, you should at least include such a section, with a sentence or two to say that you haven't found it yet.
- References, cite your work.
- Additional Notes, if needed.

As aforementioned, when a solution is found...

- Resolution of the issue, inserted after the Symptom Summary. This section again, should contain only those literature suitable to a *layman*.
- Update Technical Details to include details on the resolution.
- Update Cause if you haven't done so.
- Update References, yeah?

### AOSA

As any good security advisory - those useful to system administrators - should contain...

- Topic generalising the security vulnerability, include a CVE number at end of topic if assigned.
- Detail section containing a... longer... version of the security vulnerability, you should be able to find it from their original `oss-security` mailing list post. If not, write your own.
- CVE listing section, if available.
- PoC section, if available. Note that AOSAs should only be posted *after* security fixes were made available to users, nothing to worry here.