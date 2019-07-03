# mocha-tutorial
Following a tutorial on basic Mocha testing by Brandon Morelli.  https://codeburst.io/how-to-test-javascript-with-mocha-the-basics-80132324752e

When writing a test, there are two basic function calls to be aware of:  `describe()` and `it()`.

<ul>
  <li>`describe()` is simply a way to group tests in Mocha.  Tests can be nested in groups as deep as it necessary.  `describe()` takes two arguments, the name of the test group and a callback function.</li>

  <pre>
    describe('string name', function() {
      // can keep nesting describes or simply add tests!
    })
  </pre>

  <li>`it()` is used for an individual test case.  `it()` should be written as if being said out loud: "It should equal zero," "It should log the user in," etc...  `it()` takes two arguments: a string explaining what the test should do and a callback which contains the actual test.</li>

  <pre>
    it('should do this awesome thing', function() {
      // Test goes here!
    })
  </pre>
</ul>
