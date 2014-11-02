GHC 7.8.3 Haiku Binary Distribution
-----------------------------------

This is a pre-built binary distribution of GHC 7.8.3 for
x86 Haiku builds (should work with both gcc2h and gcc4 builds).

Building GHC requires a pre-existing GHC, so this installation
can be used for bootstrapping a new GHC build.

Patches
-------

- network.patch is a patch for the cabal package `network`
- haiku-fixes.patch contains a number of Haiku specific fixes,
  as well as some customisation to install paths to be more
  inline with the standard Haiku folder layout

Some of these fixes need to be reworked to be more maintainable,
so that they can be upstreamed to GHC proper.
