# [`json-schema-library`](https://github.com/sagold/json-schema-library) - test summary

# All validators fail this test

`some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part`

# [`json-schema-library`](https://github.com/sagold/json-schema-library) failed tests

Some validators have deliberately chosen not to support parts of the spec. Go to the [`json-schema-library`](https://github.com/sagold/json-schema-library) homepage to learn if
that is the case for these tests.

|test failed|reason
|-----------|------
`allOf, mismatch first`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`allOf with base schema, mismatch first allOf`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`invalid type for default, still valid when the invalid default is used`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`dependencies, nondependant`|Expected result: `true` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`dependencies, with dependency`|Expected result: `true` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`dependencies, missing dependency`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`multiple dependencies, nondependants`|Expected result: `true` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies, with dependencies`|Expected result: `true` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies, missing dependency`|Expected result: `false` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies, missing other dependency`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`multiple dependencies subschema, valid`|Expected result: `true` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, no dependency`|Expected result: `true` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, wrong type`|Expected result: `false` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, wrong type other`|Expected result: `false` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, wrong type both`|Expected result: `false` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`dependencies with escaped characters, invalid object 1`|Expected result: `false` but validator returned: `"Invalid dependency definition for #/foo. Must be list or schema"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores integers`|Expected result: `true` but validator returned: `"value.includes is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores floats`|Expected result: `true` but validator returned: `"value.includes is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores objects`|Expected result: `true` but validator returned: `"value.includes is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores null`|Expected result: `true` but validator returned: `"Cannot read property 'includes' of null"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores integers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores floats`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores objects`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores integers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores floats`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores objects`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of hostnames, ignores integers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of hostnames, ignores objects`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of hostnames, ignores null`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores integers`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores floats`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores objects`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores null`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of URIs, ignores integers`|Expected result: `true` but validator returned: `"uri.match is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores floats`|Expected result: `true` but validator returned: `"uri.match is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores objects`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`validation of URIs, ignores null`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`items and subitems, wrong sub-item`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`forbidden property, property absent`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`oneOf complex types, first oneOf valid (complex)`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`oneOf with required, both invalid - invalid`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`oneOf with missing optional property, first oneOf valid`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`oneOf with missing optional property, neither oneOf valid`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`validation of e-mail addresses, dot before local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, dot after local part is not valid`|Expected result: `false` but validator returned: `true`
`validation of e-mail addresses, two subsequent dots inside local part are not valid`|Expected result: `false` but validator returned: `true`
`validation of host names, exceeds maximum label length`|Expected result: `false` but validator returned: `true`
`Proper UTF-16 surrogate pair handling: pattern, matches empty`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: pattern, matches two`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: patternProperties, doesn't match two`|Expected result: `false` but validator returned: `true`
`object properties validation, doesn't invalidate other properties`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, patternProperty validates nonproperty`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, additionalProperty ignores property`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, additionalProperty validates others`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`relative pointer ref to object, match`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`required validation, non-present required property is invalid`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`uniqueItems validation, objects are non-unique despite key order`|Expected result: `false` but validator returned: `true`

**All other tests passed**.

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)