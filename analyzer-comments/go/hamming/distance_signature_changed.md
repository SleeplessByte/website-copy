# distance signature changed

The signature of the `Distance` function should be `Distance(a, b string) (int, error)`.
Exercism is built on the TDD ([Test Driven Development](http://testfirst.org/about#tdd)) principle.
The tests already exist and define the outward facing interface, as well as the behaviour of the code to be implemented.
Changing the signature breaks the tests.
