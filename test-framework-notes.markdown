# Test framwork notes

# Testing frameworks
- Qunit (http://qunitjs.com/)
- Mocha (http://visionmedia.github.com/mocha/)
- Tutti (http://tuttijs.com)
- TestSwarm (http://swarm.jquery.org/)
- JsTestDriver (http://code.google.com/p/js-test-driver/)
- jsUnity (http://jsunity.com), 
- Jasmine (http://pivotal.github.com/jasmine/)

## Comparison articles
- Jasmine VS Mocha (http://lostechies.com/derickbailey/2012/11/01/javascript-unit-tests-jasmine-vs-mocha/)
- Async unit tests with mocha, promises and winjs - (http://lostechies.com/derickbailey/2012/08/17/asynchronous-unit-tests-with-mocha-promises-and-winjs/)

## Testing framework evaluation focus
- Testing syncronous code
- Testing asyncronous code and promises
- Mocking framework components
- Test syntax
- User base (number of people, popularity)

## Related articles
- Making Jasmine async tests suck less - http://lostechies.com/derickbailey/2012/08/18/jasmine-async-making-asynchronous-testing-with-jasmine-suck-less/
-- Jasmine.Async - https://github.com/derickbailey/jasmine.async

# Assertion libraries
- Jasmine (Built in)
- Chai - http://chaijs.com/ (Often used by Mocha users)
- assert.js - https://github.com/Jxck/assert (port of node assert functions)
- jShould - https://github.com/eliperelman/jShould (QUnit extension)
- should.js - https://github.com/visionmedia/should.js (node library)
- expect.js - https://github.com/LearnBoost/expect.js (based on should.js, standalone)
- YUIPort - https://github.com/gso/YUIPort (YUI libs but standalone)
- chai - https://github.com/logicalparadox/chai (node and browser, plugins inc. for JQuery)

# Spy frameworks (spies, stubs and mocks)
- Jasmine (Built in)
- SinonJS (http://sinonjs.org/ - Often used with Mocha)

# Test runners
- Karma (http://karma-runner.github.io/)
- Chutzpah (http://chutzpah.codeplex.com/)
- VenusJS (http://www.venusjs.org/)

# Benefits of Require.js

- when migrating from one version of a lib to another (jquery for example) you can continue using the old version as you migrate specific areas to the new version
QA time and cost is more easily managed by being able to spread the load over a period of time

- You only have to request the files you're interested in and all dependencies are automatically handled. No need to manually keep adding JS files to fix each break.
This improves workflow and developer sanity.

- Testing is made easier because you can specify which js files you're interested in for the given test suite. This is in contrast to loading everything for all tests each time.