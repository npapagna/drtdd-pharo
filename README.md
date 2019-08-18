# Dr.TDD
https://vimeo.com/354461588

Dr. TDD is a real-time advisor that aims to give immediate feedback (in the same spirit as TDD) to students about how well they know and apply this technique together with recommendations to correct deviations from it.

## Installation

Note: this is a tech preview version. Dr.TDD is under heavy development/refactoring and will be available in 2020.

### Pharo 6.1
Using Monticello, load these packages in order:
* `SLICE-Issue-1-DrTDD-Fix-Nautilus-Plugins-Bounds-Computation-NPM.1`
* `SLICE-Issue-2-DrTDD-Fix-Reset-TestCase-History-When-Running-Tests-NPM.2`
* `SLICE-Issue-3-DrTDD-Fix-Unregister-Nautilus-Plugins-From-Annoucements-When-The-Browser-Is-Closed-NPM.1`
* latest `DrTDD-NPM` package.

## Configuration
Add Dr.TDD nautilus plugin:
* Open Nautilus Plugin Manager: `NautilusPluginManager new openInWorld`
* Look for DrTDDNautilusPlugin and `Add` it in the `top` position.

## Usage
Open a System Browser, select a package and click `Start Dr.TDD`.