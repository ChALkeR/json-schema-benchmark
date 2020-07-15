# [`tv4`](https://github.com/geraintluff/tv4) - test summary

# All validators fail this test

`some languages do not distinguish between different types of numeric value, a float is not an integer even without fractional part`

# [`tv4`](https://github.com/geraintluff/tv4) failed tests

Some validators have deliberately chosen not to support parts of the spec. Go to the [`tv4`](https://github.com/geraintluff/tv4) homepage to learn if
that is the case for these tests.

|test failed|reason
|-----------|------
`additionalItems as schema, additional items match schema`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalItems as schema, additional items do not match schema`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`items is schema, no additionalItems, all items match schema`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`array of items with no additionalItems, empty array`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`array of items with no additionalItems, fewer number of items present (1)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`array of items with no additionalItems, fewer number of items present (2)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`array of items with no additionalItems, equal number of items present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`array of items with no additionalItems, additional items are not permitted`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalItems as false without items, items defaults to empty schema so everything is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalItems as false without items, ignores non-arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalItems are allowed by default, only the first item is validated`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalItems should not look in applicators, valid case, items defined in allOf are not examined`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalItems should not look in applicators, invalid case, items defined in allOf are not examined`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties being false does not allow other properties, no additional properties is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties being false does not allow other properties, an additional property is invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties being false does not allow other properties, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties being false does not allow other properties, ignores strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties being false does not allow other properties, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties being false does not allow other properties, patternProperties are not additional properties`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`non-ASCII pattern with additionalProperties, matching the pattern is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties allows a schema which should validate, no additional properties is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties allows a schema which should validate, an additional valid property is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties allows a schema which should validate, an additional invalid property is invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties can exist by itself, an additional valid property is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`additionalProperties are allowed by default, additional properties are allowed`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf, allOf`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf, mismatch first`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf, wrong type`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with base schema, valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with base schema, mismatch first allOf`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with base schema, mismatch second allOf`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with base schema, mismatch both`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf simple types, valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with one empty schema, any data is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with two empty schemas, any data is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with the first empty schema, number is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with the first empty schema, string is invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf with the last empty schema, number is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nested allOf, to check validation semantics, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf combined with anyOf, oneOf, allOf: true, anyOf: false, oneOf: false`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf combined with anyOf, oneOf, allOf: true, anyOf: false, oneOf: true`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf combined with anyOf, oneOf, allOf: true, anyOf: true, oneOf: false`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`allOf combined with anyOf, oneOf, allOf: true, anyOf: true, oneOf: true`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf, first anyOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf, second anyOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf, both anyOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf with base schema, one anyOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf complex types, first anyOf valid (complex)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf complex types, second anyOf valid (complex)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf complex types, both anyOf valid (complex)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf complex types, neither anyOf valid (complex)`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf with one empty schema, string is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`anyOf with one empty schema, number is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nested anyOf, to check validation semantics, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nested anyOf, to check validation semantics, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`invalid type for default, valid when property is specified`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`invalid type for default, still valid when the invalid default is used`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`invalid string value for default, valid when property is specified`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`invalid string value for default, still valid when the invalid default is used`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`invalid definition, invalid definition schema`|Expected result: `false` but validator returned: `true`
`dependencies, neither`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies, nondependant`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies, with dependency`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies, missing dependency`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies, ignores strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies, neither`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies, nondependants`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies, with dependencies`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies, missing other dependency`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, no dependency`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple dependencies subschema, wrong type other`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies with escaped characters, valid object 1`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies with escaped characters, valid object 2`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`dependencies with escaped characters, valid object 3`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`simple enum validation, one of the enum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`heterogeneous enum validation, one of the enum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`heterogeneous enum-with-null validation, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`heterogeneous enum-with-null validation, number is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enums in properties, both properties are valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enums in properties, wrong bar value`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enums in properties, missing optional property is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with escaped characters, member 1 is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with escaped characters, member 2 is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with false does not match 0, false is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with true does not match 1, true is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with 0 does not match false, integer zero is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with 0 does not match false, float zero is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with 1 does not match true, integer one is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`enum with 1 does not match true, float one is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nul characters in strings, match string with nul`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of e-mail addresses, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IP addresses, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of IPv6 addresses, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of hostnames, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of hostnames, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of hostnames, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of hostnames, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of hostnames, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of hostnames, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of date-time strings, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`validation of URIs, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`a schema given for items, valid items`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`a schema given for items, wrong type of items`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`a schema given for items, ignores non-arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`a schema given for items, JavaScript pseudo-array is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`an array of schemas for items, correct types`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`an array of schemas for items, incomplete array of items`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`an array of schemas for items, array with additional items`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`an array of schemas for items, empty array`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`an array of schemas for items, JavaScript pseudo-array is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`items and subitems, valid items`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`items and subitems, too many items`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`items and subitems, too many sub-items`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`items and subitems, wrong sub-item`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`items and subitems, fewer items is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nested items, valid nested array`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxItems validation, shorter is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxItems validation, exact length is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxItems validation, ignores non-arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxLength validation, shorter is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxLength validation, exact length is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxLength validation, ignores non-strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxLength validation, two supplementary Unicode code points is long enough`|Expected result: `true` but validator returned: `false`
`maxProperties validation, shorter is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxProperties validation, exact length is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxProperties validation, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxProperties validation, ignores strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxProperties validation, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maxProperties = 0 means the object is empty, no properties is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation, below the maximum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation, boundary point is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation, ignores non-numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation with unsigned integer, below the maximum is invalid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation with unsigned integer, boundary point integer is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation with unsigned integer, boundary point float is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation (explicit false exclusivity), below the maximum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation (explicit false exclusivity), boundary point is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`maximum validation (explicit false exclusivity), ignores non-numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`exclusiveMaximum validation, below the maximum is still valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minItems validation, longer is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minItems validation, exact length is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minItems validation, ignores non-arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minLength validation, longer is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minLength validation, exact length is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minLength validation, ignores non-strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minLength validation, one supplementary Unicode code point is not long enough`|Expected result: `false` but validator returned: `"func is not a function"`
`minProperties validation, longer is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minProperties validation, exact length is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minProperties validation, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minProperties validation, ignores strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minProperties validation, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation, above the minimum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation, boundary point is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation, ignores non-numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation (explicit false exclusivity), above the minimum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation (explicit false exclusivity), boundary point is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation (explicit false exclusivity), ignores non-numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`exclusiveMinimum validation, above the minimum is still valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation with signed integer, negative above the minimum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation with signed integer, positive above the minimum is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation with signed integer, boundary point is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation with signed integer, boundary point with float is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`minimum validation with signed integer, ignores non-numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`by int, int by int`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`by int, ignores non-numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`by number, zero is multiple of anything`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`by number, 4.5 is multiple of 1.5`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`by small number, 0.0075 is multiple of 0.0001`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not, allowed`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not, disallowed`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not multiple types, valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not multiple types, mismatch`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not multiple types, other mismatch`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not more complex schema, match`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not more complex schema, other match`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`not more complex schema, mismatch`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`forbidden property, property present`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`forbidden property, property absent`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf, first oneOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf, second oneOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf, both oneOf valid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with base schema, one oneOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with base schema, both oneOf valid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf complex types, first oneOf valid (complex)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf complex types, second oneOf valid (complex)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf complex types, both oneOf valid (complex)`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf complex types, neither oneOf valid (complex)`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with empty schema, one valid - valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with empty schema, both valid - invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with required, both invalid - invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with required, first valid - valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with required, second valid - valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with required, both valid - invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with missing optional property, first oneOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with missing optional property, second oneOf valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with missing optional property, both oneOf valid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`oneOf with missing optional property, neither oneOf valid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nested oneOf, to check validation semantics, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`integer, a bignum is an integer`|Expected result: `true` but validator returned: `"func is not a function"`
`number, a bignum is a number`|Expected result: `true` but validator returned: `"func is not a function"`
`integer, a negative bignum is an integer`|Expected result: `true` but validator returned: `"func is not a function"`
`number, a negative bignum is a number`|Expected result: `true` but validator returned: `"func is not a function"`
`integer comparison, comparison works for high numbers`|Expected result: `true` but validator returned: `"func is not a function"`
`integer comparison, comparison works for very negative numbers`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 regex non-compliance, ECMA 262 has no support for \Z anchor from .NET`|Expected result: `false` but validator returned: `"func is not a function"`
`ECMA 262 regex $ does not match trailing newline, should match`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 regex converts \t to horizontal tab, matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 regex escapes control codes with \c and upper letter, matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 regex escapes control codes with \c and lower letter, matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \d matches ascii digits only, ASCII zero matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \D matches everything but ascii digits, NKO DIGIT ZERO matches (unlike e.g. Python)`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \D matches everything but ascii digits, NKO DIGIT ZERO (as \u escape) matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \w matches ascii letters only, ASCII 'a' matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \W matches everything but ascii letters, latin-1 e-acute matches (unlike e.g. Python)`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, ASCII space matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, Character tabulation matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, Line tabulation matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, Form feed matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, latin-1 non-breaking-space matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, zero-width whitespace matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, line feed matches (line terminator)`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, paragraph separator matches (line terminator)`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \s matches whitespace, EM SPACE matches (Space_Separator)`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \S matches everything but whitespace, Non-whitespace control matches`|Expected result: `true` but validator returned: `"func is not a function"`
`ECMA 262 \S matches everything but whitespace, Non-whitespace matches`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of date-time strings, a valid date-time string`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of date-time strings, a valid date-time string without second fraction`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of date-time strings, a valid date-time string with plus offset`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of date-time strings, a valid date-time string with minus offset`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of date-time strings, a invalid day in date-time string`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of date-time strings, an invalid offset in date-time string`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of date-time strings, an invalid date-time string`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of date-time strings, case-insensitive T and Z`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of date-time strings, only RFC3339 not all of ISO 8601 are valid`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of e-mail addresses, a valid e-mail address`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of e-mail addresses, an invalid e-mail address`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of e-mail addresses, tilde in local part is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of e-mail addresses, tilde before local part is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of e-mail addresses, tilde after local part is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of e-mail addresses, dot before local part is not valid`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of e-mail addresses, dot after local part is not valid`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of e-mail addresses, two separated dots inside local part are valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of e-mail addresses, two subsequent dots inside local part are not valid`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, a valid host name`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of host names, a host name starting with an illegal character`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, a host name containing illegal characters`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, a host name with a component too long`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, starts with hyphen`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, ends with hyphen`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, starts with underscore`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, ends with underscore`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, contains underscore`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of host names, maximum label length`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of host names, exceeds maximum label length`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IP addresses, a valid IP address`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IP addresses, an IP address with too many components`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IP addresses, an IP address with out-of-range values`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IP addresses, an IP address without 4 components`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IP addresses, an IP address as an integer`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IP addresses, an IP address as an integer (decimal)`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, a valid IPv6 address`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, an IPv6 address with out-of-range values`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, an IPv6 address with too many components`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, an IPv6 address containing illegal characters`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, no digits is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, leading colons is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, trailing colons is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, two sets of double colons is invalid`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, mixed format with the ipv4 section as decimal octets`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, mixed format with double colons between the sections`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, mixed format with ipv4 section with octet out of range`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of IPv6 addresses, mixed format with ipv4 section with a hex octet`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL with anchor tag`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL with anchor tag and parantheses`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL with URL-encoded stuff`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid puny-coded URL `|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL with many special characters`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL based on IPv4`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL with ftp scheme`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL for a simple text file`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URL `|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid mailto URI`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid newsgroup URI`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid tel URI`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, a valid URN`|Expected result: `true` but validator returned: `"func is not a function"`
`validation of URIs, an invalid protocol-relative URI Reference`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of URIs, an invalid relative URI Reference`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of URIs, an invalid URI`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of URIs, an invalid URI though valid URI reference`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of URIs, an invalid URI with spaces`|Expected result: `false` but validator returned: `"func is not a function"`
`validation of URIs, an invalid URI with spaces and missing scheme`|Expected result: `false` but validator returned: `"func is not a function"`
`Proper UTF-16 surrogate pair handling: pattern, matches empty`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: pattern, matches single`|Expected result: `true` but validator returned: `"func is not a function"`
`Proper UTF-16 surrogate pair handling: pattern, matches two`|Expected result: `true` but validator returned: `false`
`Proper UTF-16 surrogate pair handling: patternProperties, matches empty`|Expected result: `true` but validator returned: `"func is not a function"`
`Proper UTF-16 surrogate pair handling: patternProperties, matches single`|Expected result: `true` but validator returned: `"func is not a function"`
`Proper UTF-16 surrogate pair handling: patternProperties, matches two`|Expected result: `true` but validator returned: `"func is not a function"`
`Proper UTF-16 surrogate pair handling: patternProperties, doesn't match two`|Expected result: `false` but validator returned: `"func is not a function"`
`pattern validation, a matching pattern is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern validation, ignores booleans`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern validation, ignores integers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern validation, ignores floats`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern validation, ignores objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern validation, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern validation, ignores null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`pattern is not anchored, matches a substring`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`patternProperties validates properties matching a regex, a single valid match is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`patternProperties validates properties matching a regex, multiple valid matches is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`patternProperties validates properties matching a regex, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`patternProperties validates properties matching a regex, ignores strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`patternProperties validates properties matching a regex, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple simultaneous patternProperties are validated, a single valid match is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple simultaneous patternProperties are validated, a simultaneous match is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple simultaneous patternProperties are validated, multiple matches is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple simultaneous patternProperties are validated, an invalid due to the other is invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`regexes are not anchored by default and are case sensitive, non recognized members are ignored`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`regexes are not anchored by default and are case sensitive, regexes are case sensitive`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`object properties validation, both properties present and valid is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`object properties validation, one property invalid is invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`object properties validation, doesn't invalidate other properties`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`object properties validation, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`object properties validation, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, property validates property`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, patternProperty invalidates property`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, patternProperty validates nonproperty`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, additionalProperty ignores property`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`properties, patternProperties, additionalProperties interaction, additionalProperty validates others`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`properties with escaped characters, object with all numbers is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as number, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' as object, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'x' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as number, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' as object, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'length' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as number, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' as object, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Invalid if not present`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'toString' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as number, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' as object, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Invalid if not present`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: 'constructor' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as number, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' as object, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see elements non existing on the object: '__proto__' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'foo' as number, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'foo' as object, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Invalid if not present`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if not present`|Expected result: `true` but validator returned: `false`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'foo' via required, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: 'length' as number, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: 'length' as object, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: 'length' via required, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value: '__proto__' as number, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Default value on a '__proto__' property: '__proto__' as object, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Invalid if not present`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (empty string)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (boolean true)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (boolean false)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (empty array)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (object)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (zero number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if present (number)`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on numbers`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid on arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if not present`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Does not see inexisting elements on new objects: '__proto__' via required, Valid if correct`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`root pointer ref, match`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`root pointer ref, recursive match`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`relative pointer ref to object, match`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`relative pointer ref to array, match array`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`relative pointer ref to array, mismatch array`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`escaped pointer ref, slash valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`escaped pointer ref, tilde valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`escaped pointer ref, percent valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`nested refs, nested ref valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`ref overrides any sibling keywords, ref valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`ref overrides any sibling keywords, ref valid, maxItems ignored`|Expected result: `true` but validator returned: `"func is not a function"`
`remote ref, containing refs itself, remote ref invalid`|Expected result: `false` but validator returned: `true`
`property named $ref that is not a reference, property named $ref valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`property named $ref, containing an actual $ref, property named $ref valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Recursive references between schemas, valid tree`|Expected result: `true` but validator returned: `"func is not a function"`
`Recursive references between schemas, invalid tree`|Expected result: `false` but validator returned: `"func is not a function"`
`refs with quote, object with numbers is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Location-independent identifier, match`|Expected result: `true` but validator returned: `"func is not a function"`
`Location-independent identifier with absolute URI, match`|Expected result: `true` but validator returned: `"func is not a function"`
`Location-independent identifier with absolute URI, mismatch`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`Location-independent identifier with base URI change in subschema, match`|Expected result: `true` but validator returned: `"func is not a function"`
`Location-independent identifier with base URI change in subschema, mismatch`|Expected result: `false` but validator returned: `"func is not a function"`
`remote ref, remote ref invalid`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`fragment within remote ref, remote fragment invalid`|Expected result: `false` but validator returned: `true`. **This excludes this validator from performance tests**
`ref within remote ref, ref within ref invalid`|Expected result: `false` but validator returned: `true`
`base URI change, base URI change ref valid`|Expected result: `true` but validator returned: `"func is not a function"`
`base URI change, base URI change ref invalid`|Expected result: `false` but validator returned: `"func is not a function"`
`base URI change - change folder, number is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`base URI change - change folder, string is invalid`|Expected result: `false` but validator returned: `"func is not a function"`
`base URI change - change folder in subschema, number is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`base URI change - change folder in subschema, string is invalid`|Expected result: `false` but validator returned: `"func is not a function"`
`root ref in remote ref, string is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`root ref in remote ref, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`root ref in remote ref, object is invalid`|Expected result: `false` but validator returned: `"func is not a function"`
`required validation, present required property is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`required validation, non-present required property is invalid`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`required validation, ignores arrays`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`required validation, ignores strings`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`required validation, ignores other non-objects`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`required default validation, not required by default`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`required with escaped characters, object with all properties present is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`integer type matches integers, an integer is an integer`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`number type matches numbers, an integer is a number`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`number type matches numbers, a float with zero fractional part is a number`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`number type matches numbers, a float is a number`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`string type matches strings, a string is a string`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`string type matches strings, a string is still a string, even if it looks like a number`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`string type matches strings, an empty string is still a string`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`object type matches objects, an object is an object`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`array type matches arrays, an array is an array`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`boolean type matches booleans, true is a boolean`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`boolean type matches booleans, false is a boolean`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`null type matches only the null object, null is null`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple types can be specified in an array, an integer is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`multiple types can be specified in an array, a string is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`type as array with one item, string is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`type: array or object, array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`type: array or object, object is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`type: array, object or null, array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`type: array, object or null, object is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`type: array, object or null, null is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems validation, unique array of integers is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, false is not equal to zero`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, true is not equal to one`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, unique array of objects is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, unique array of nested objects is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, unique array of arrays is valid`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, 1 and true are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, 0 and false are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, [1] and [true] are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, [0] and [false] are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, nested [1] and [true] are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, nested [0] and [false] are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, unique heterogeneous types are valid`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems validation, different objects are unique`|Expected result: `true` but validator returned: `"func is not a function"`
`uniqueItems with an array of items, [false, true] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems with an array of items, [true, false] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems with an array of items, unique array extended from [false, true] is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems with an array of items, unique array extended from [true, false] is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems with an array of items and additionalItems=false, [false, true] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems with an array of items and additionalItems=false, [true, false] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems with an array of items and additionalItems=false, extra items are invalid even if unique`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, unique array of integers is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, non-unique array of integers is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, numbers are unique if mathematically unequal`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, false is not equal to zero`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, true is not equal to one`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, unique array of objects is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, non-unique array of objects is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, unique array of nested objects is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, non-unique array of nested objects is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, unique array of arrays is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, non-unique array of arrays is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, 1 and true are unique`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, 0 and false are unique`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, unique heterogeneous types are valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false validation, non-unique heterogeneous types are valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, [false, true] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, [true, false] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, [false, false] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, [true, true] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, unique array extended from [false, true] is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, unique array extended from [true, false] is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, non-unique array extended from [false, true] is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items, non-unique array extended from [true, false] is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items and additionalItems=false, [false, true] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items and additionalItems=false, [true, false] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items and additionalItems=false, [false, false] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items and additionalItems=false, [true, true] from items array is valid`|Expected result: `true` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**
`uniqueItems=false with an array of items and additionalItems=false, extra items are invalid even if unique`|Expected result: `false` but validator returned: `"func is not a function"`. **This excludes this validator from performance tests**

**All other tests passed**.

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)