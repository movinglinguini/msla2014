# Changelog
## (2024-11-01)

### Ported IntuitionisticLogic.agda to Agda 2.8
* Renamed the `_,_` constructor for products to `⟨_,_⟩`.
* Did appropriate substitutions for the old products constructor to the new one.
* Swapped the arguments for Vector.lookup.
* Added a few comments and changed spacing on natural deduction rules.

### Ported LinearLogic.agda to Agda 2.8
* Imported map-++ rather than map-++-commute, which is now deprecated.
* Added a few comments and changed spacing on natural deduction rules.
* Added proof of transitivity of implication for fun.