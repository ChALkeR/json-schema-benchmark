# [`ajv`](https://github.com/ajv-validator/ajv) - test summary

# All validators fail this test

`some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part`

# [`ajv`](https://github.com/ajv-validator/ajv) failed tests

Some validators have deliberately chosen not to support parts of the spec. Go to the [`ajv`](https://github.com/ajv-validator/ajv) homepage to learn if
that is the case for these tests.

|test failed|reason
|-----------|------
`validation of e-mail addresses, dot before local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, dot after local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, two subsequent dots inside local part are not valid`|Expected result: `false` but validator returned: `true`
`Proper UTF-16 surrogate pair handling: pattern, matches empty`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: pattern, matches two`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: patternProperties, doesn't match two`|Expected result: `false` but validator returned: `true`
`Does not see elements non existing on the object: 'toString' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (empty string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (boolean true)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (boolean false)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (empty array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Invalid if incorrect (object)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (empty string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (boolean true)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (boolean false)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (empty array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (zero number)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Invalid if incorrect (number)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (empty string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (boolean true)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (boolean false)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (empty array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (object)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (empty string)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (boolean true)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (boolean false)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (empty array)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (zero number)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if incorrect (number)`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Location-independent identifier, match`|The schema failed to load(`schema is invalid: data.definitions['A'].id should match format "uri"`)
`Location-independent identifier, mismatch`|The schema failed to load(`schema is invalid: data.definitions['A'].id should match format "uri"`)
`Location-independent identifier with base URI change in subschema, match`|The schema failed to load(`schema is invalid: data.definitions['A'].id should match format "uri"`)
`Location-independent identifier with base URI change in subschema, mismatch`|The schema failed to load(`schema is invalid: data.definitions['A'].id should match format "uri"`)
`base URI change, base URI change ref valid`|The schema failed to load(`schema is invalid: data.items.id should match format "uri", data.items should be array, data.items should match some schema in anyOf`)
`base URI change, base URI change ref invalid`|The schema failed to load(`schema is invalid: data.items.id should match format "uri", data.items should be array, data.items should match some schema in anyOf`)
`base URI change - change folder, number is valid`|The schema failed to load(`schema is invalid: data.definitions['baz'].id should match format "uri"`)
`base URI change - change folder, string is invalid`|The schema failed to load(`schema is invalid: data.definitions['baz'].id should match format "uri"`)
`base URI change - change folder in subschema, number is valid`|The schema failed to load(`schema is invalid: data.definitions['baz'].id should match format "uri"`)
`base URI change - change folder in subschema, string is invalid`|The schema failed to load(`schema is invalid: data.definitions['baz'].id should match format "uri"`)

**All other tests passed**.

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)