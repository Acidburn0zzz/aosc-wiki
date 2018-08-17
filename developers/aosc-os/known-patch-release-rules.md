<!-- TITLE: Known Patch Release Rules -->
<!-- SUBTITLE: Useful list of release rules that defines packages that could be updated in the Stable channel -->

# Description

The AOSC OS "Stable" channel under the new *TODO: SEASONAL UPDATE MODEL* requires that only packages with *known* patch-level release rules could be updated in this channel, for example, when GNOME Terminal (`gnome-terminal`) is to be update from `3.30.0` to `3.30.1`, this is permitted, as we know that this is a patch release as [dictated](https://developer.gnome.org/programming-guidelines/stable/versioning.html.en#stable-unstable-versions) by GNOME - on the contrary, an update from `3.30.0` to `3.31.0` (stable to unstable) or even from `3.30.0` to `3.32.0` (stable to next-stable) are not acceptable.

Presented below is a table that defines all known patch release rules for upstream projects, if it isn't found here, do not push any updates to the "stable" channel - or these updates will be reverted.

# Table of Known Update Rules

| Project or Package Name | Rule Description |
| -------------------------------------------- | ----------------------------- |