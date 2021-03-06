# R package pedSimulate: Pedigree, genetic merit and phenotype simulation

## Version: 0.0.3

## Version: 0.0.4

* Applying mortality to each generation separately rather than on selection candidates, which may come from more than a single generation.

## Version: 0.1.1

* Added function `assortative` for assortative/disassortative mating.
* Added `"-P"` and `"-PA"` to arguments `fsel` and `msel` to select in opposite directions of `"P"` (phenotype) and `"PA"` (parent average).

## Version: 0.1.2

* Debugged the bug introduced in the previous version in the `simulatePed` function.

## Version: 1.0.0

* Major revision
* Functions `simulatePed` and `assortative` were combined into `simulatePed`, and arguments `fullsib` and `parentprogeny` were removed.
* Added function `appendPed` for simulating new generations from an existing pedigree and appending to it.
* Added function `fs_mate_finder` for finding fullsib matings in the pedigree.
* Added function `hs_mate_finder` for finding halfsib matings in the pedigree.
* Added function `pp_mate_finder` for finding parent-progeny matings in the pedigree.

## Version: 1.0.1

* Made a small debug.

## Version: 1.1.0

* Added agrumnts `f.order` and `m.order` to `simulatePed` and `appendPed` functions.