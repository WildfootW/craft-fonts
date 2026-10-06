craft-fonts
===========

Reusable fonts for the Crafting Apps.

This library is meant to have the following:

1. Reusable font assets. These may be large files, and since we're using a separate repo for storing them,
   We're not afraid of potentially having to do a git reset to purge stale assets. It won't impact the other
   repos with core app and library functionality.

2. Additional cross-cutting Rust libraries for dealing with fonts. It's uncertain whether it's better to
   have code packages as individual repos as one classically does, or whether we should take a
   more "biology-inspired" approach of copying innovations between repos as a form of lateral code/information
   exchange.



