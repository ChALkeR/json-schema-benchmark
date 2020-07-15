# [`json-gate`](https://github.com/oferei/json-gate#readme) side-effects in testrun

When running tests [`json-gate`](https://github.com/oferei/json-gate#readme) mutated either the original schema or the data being validated with the schema or both.


# Side-effect on data
[`json-gate`](https://github.com/oferei/json-gate#readme) had a side-effect on (altered the original) data in the test `Default value: 'foo' as number, Valid if not present`
## Schema
```js
{
	"properties": {
		"foo": {
			"default": "foo"
		}
	}
}
```
## Original data
```js
{}
```
## Data after validating with schema
```js
{
	"foo": "foo"
}
```

# Side-effect on data
[`json-gate`](https://github.com/oferei/json-gate#readme) had a side-effect on (altered the original) data in the test `root pointer ref, mismatch`
## Schema
```js
{
	"properties": {
		"foo": {
			"$ref": "#"
		}
	},
	"additionalProperties": false
}
```
## Original data
```js
{
	"bar": false
}
```
## Data after validating with schema
```js
{
	"bar": false,
	"foo": "foo"
}
```

# Side-effect on data
[`json-gate`](https://github.com/oferei/json-gate#readme) had a side-effect on (altered the original) data in the test `required default validation, not required by default`
## Schema
```js
{
	"properties": {
		"foo": {}
	}
}
```
## Original data
```js
{}
```
## Data after validating with schema
```js
{
	"foo": "foo"
}
```

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)