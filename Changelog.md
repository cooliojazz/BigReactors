Big Reactors Changelog
======================

Next Release (Anticipated Version: 0.0.3)
-----------------------------------------
- Control rods now have an actual control rod to extend/retract, and it affects the radiation simulation
- Lots of internal refactoring. Tall fuel columns are now markedly more efficient in both messaging and rendering.
- Heat/Radiation simulation rewritten to be more comprehensible than the original. Fuel = radiation. Radiation = heat & more radiation. Most power comes from heat, but some from radiation in certain coolants (e.g. water).
- A basic cyanite reprocessor now exists. Cyanite + Water + Power = Blutonium. This is neither final nor balanced.
- Blutonium is now usable as reactor fuel. At the moment, it is identical to yellorium aside from the item's appearance.

- Nothing yet!

Current Release (0.0.2-playtest)
--------------------------------
- First-pass optimization of BeefCore. Truly large reactors (16x16x16 at least) are now possible.
- Access ports marked as outlets (blue arrows) now auto-emit waste if there are pipes attached

Older Releases
--------------

### Release 0.0.1-playtest
- Initial release