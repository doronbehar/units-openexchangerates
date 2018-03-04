# A [GNU Units][gnu-units] compatible exchange rates currencies updater

If you have ever used [GNU units][gnu-units], you may have enjoyed it's very smooth user interface and command line arguments interpretation. `units` also provides exchange rates currency conversions. It does so by reading the file `currency.units` (usually located in `/usr/share/units/` in most distributions). The `units` program usually is distributed with a python script `units_cur` which updates the file `currency.units` with data from [https://finance.yahoo.com/](https://finance.yahoo.com/)'s free API.

The purpose of this script is to provide an alternative yet compatible currency units updater for GNU units using [https://openexchangerates.org](https://openexchangerates.org) (also free with registration) API. The advantages in using this script over the original `units_cur` are:

- More currencies including digital currencies as well: [https://docs.openexchangerates.org/docs/supported-currencies](https://docs.openexchangerates.org/docs/supported-currencies)
- Faster and more accurate exchange rates using base currencies according to [your choice](https://docs.openexchangerates.org/docs/set-base-currency#default-base-currency).

[gnu-units]: https://gnu.org/software/units
