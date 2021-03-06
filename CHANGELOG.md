# onkcop

## v0.46.0.1 (2017-01-07)

[full changelog](https://github.com/onk/onkcop/compare/v0.46.0.0...v0.46.0.1)

* Update to `rubocop-rspec` v1.9.1.
* Disable `RSpec/MessageExpectation` cop that is replaced with a new cop: `RSpec/MessageSpies`.
* Add CLI for setup `.rubocop.yml`.


## v0.46.0.0 (2016-11-30)

[full changelog](https://github.com/onk/onkcop/compare/v0.45.0.0...v0.46.0.0)

* Update to `rubocop` v0.46.0.
* Use new `Style/EmptyMethod` cop with `expanded` style.
* Use `Style/TernaryParentheses` cop `require_parentheses_when_complex` style.


## v0.45.0.0 (2016-11-02)
[full changelog](https://github.com/onk/onkcop/compare/v0.44.1.1...v0.45.0.0)

* Update to `rubocop` v0.45.0 and `rubocop-rspec` v1.8.0.
* Disable new `RSpec/ImplicitExpect` cop.
* Explicitly enable `Rspec/MessageExpectation` cop that is now disabled by default.
* Exclude Gemfile, Guardfile on `Metrics/BlockLength`.
* Disable `Style/TernaryParentheses` cop.
* Enable `Rails/HttpPositionalArguments` cop that fixes bug.
