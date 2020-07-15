# [`is-my-json-valid`](https://github.com/mafintosh/is-my-json-valid#readme) - test summary

# All validators fail this test

`some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part`

# [`is-my-json-valid`](https://github.com/mafintosh/is-my-json-valid#readme) failed tests

Some validators have deliberately chosen not to support parts of the spec. Go to the [`is-my-json-valid`](https://github.com/mafintosh/is-my-json-valid#readme) homepage to learn if
that is the case for these tests.

|test failed|reason
|-----------|------
`invalid definition, invalid definition schema`|Expected result: `false` but validator returned: `true`
`an array of schemas for items, JavaScript pseudo-array is valid`|Expected result: `true` but validator returned: `false`
`maxLength validation, two supplementary Unicode code points is long enough`|Expected result: `true` but validator returned: `false`
`minLength validation, one supplementary Unicode code point is not long enough`|Expected result: `false` but validator returned: `true`
`ECMA 262 regex non-compliance, ECMA 262 has no support for \Z anchor from .NET`|Expected result: `false` but validator returned: `true`
`validation of date-time strings, a invalid day in date-time string`|Expected result: `false` but validator returned: `true`
`validation of date-time strings, an invalid offset in date-time string`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, dot before local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, dot after local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, two subsequent dots inside local part are not valid`|Expected result: `false` but validator returned: `true`
`Proper UTF-16 surrogate pair handling: pattern, matches empty`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: pattern, matches two`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: patternProperties, doesn't match two`|Expected result: `false` but validator returned: `true`
`Does not see elements non existing on the object: 'length' as object, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid on numbers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid on numbers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid on numbers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid on numbers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid on numbers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on numbers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on arrays`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`ref overrides any sibling keywords, ref valid, maxItems ignored`|Expected result: `true` but validator returned: `false`
`remote ref, containing refs itself, remote ref invalid`|Expected result: `false` but validator returned: `true`
`Recursive references between schemas, invalid tree`|Expected result: `false` but validator returned: `true`
`Location-independent identifier with base URI change in subschema, mismatch`|Expected result: `false` but validator returned: `true`
`ref within remote ref, ref within ref invalid`|Expected result: `false` but validator returned: `true`
`base URI change, base URI change ref invalid`|Expected result: `false` but validator returned: `true`
`base URI change - change folder, string is invalid`|Expected result: `false` but validator returned: `true`
`base URI change - change folder in subschema, string is invalid`|Expected result: `false` but validator returned: `true`
`root ref in remote ref, object is invalid`|Expected result: `false` but validator returned: `true`
`uniqueItems validation, unique heterogeneous types are valid`|Expected result: `true` but validator returned: `false`
`uniqueItems validation, objects are non-unique despite key order`|Expected result: `false` but validator returned: `true`

**All other tests passed**.

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)