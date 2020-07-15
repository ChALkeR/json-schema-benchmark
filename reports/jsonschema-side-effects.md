# [`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) side-effects in testrun

When running tests [`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) mutated either the original schema or the data being validated with the schema or both.


# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Does not see elements non existing on the object: 'toString' as number, Valid if not present`
## Schema
```js
{
	"properties": {
		"toString": {
			"type": "number"
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
{}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Does not see elements non existing on the object: 'toString' as object, Valid if not present`
## Schema
```js
{
	"properties": {
		"toString": {
			"type": "object"
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
{}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Does not see elements non existing on the object: 'constructor' as number, Valid if not present`
## Schema
```js
{
	"properties": {
		"constructor": {
			"type": "number"
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
{}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Does not see elements non existing on the object: 'constructor' as object, Valid if not present`
## Schema
```js
{
	"properties": {
		"constructor": {
			"type": "object"
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
{}
```

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)