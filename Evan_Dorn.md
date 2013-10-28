There's a big difference between tests and test-driven development:
  tests themselves are not a process,
  the process of doing tests properly yields many advantages.

Professionals work to a plan rather than taking a haphazard approach.
TDD is what differentiates an engineer from a hacker.

TDD Process Defined
  > Decide what the code wiil do
  > Write the test that will pass if the code does that thing
  > Run the test, see it fail
  > Write the code
  > Run the test, see it pass

Red light, green light, refactor.

Cyclometic complexity is measure of how many different paths there are through the code.  Conditional statements are bad for TDD.

If the test you're trying to write is too complicated, that's a code smell.  Try to brake things up into smaller more testable components.

TDD Benefits
  > Testable code is tight in appearance and construction
  > Takes less time!  Caveate: time saving comes through practice, the first time you work this way, it will be slow

TDD Pearls
  > Use judgment
    -- Some things are too hard to test
    -- Some tests are too trivial to be useful
    -- Overtesting is possible
    -- Exploratory coding without tests is okay

Resources
  - destroyallsoftware.com
