# [`@cfworker/json-schema`](https://github.com/cfworker/cfworker/tree/master/packages/json-schema/README.md) - test summary

# All validators fail this test

`some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part`

# [`@cfworker/json-schema`](https://github.com/cfworker/cfworker/tree/master/packages/json-schema/README.md) failed tests

Some validators have deliberately chosen not to support parts of the spec. Go to the [`@cfworker/json-schema`](https://github.com/cfworker/cfworker/tree/master/packages/json-schema/README.md) homepage to learn if
that is the case for these tests.

|test failed|reason
|-----------|------
`validation of e-mail addresses, dot before local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, dot after local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, two subsequent dots inside local part are not valid`|Expected result: `false` but validator returned: `true`
`Proper UTF-16 surrogate pair handling: pattern, matches empty`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: pattern, matches two`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: patternProperties, doesn't match two`|Expected result: `false` but validator returned: `true`
`Does not see elements non existing on the object: 'toString' as number, Valid if not present`|Expected result: `true` but validator returned: `"Instances of \"function\" type are not supported."`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid if not present`|Expected result: `true` but validator returned: `"Instances of \"function\" type are not supported."`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid if not present`|Expected result: `true` but validator returned: `"Instances of \"function\" type are not supported."`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid if not present`|Expected result: `true` but validator returned: `"Instances of \"function\" type are not supported."`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**

**All other tests passed**.

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)