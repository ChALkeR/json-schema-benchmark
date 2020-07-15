# [`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) side-effects in testrun

When running tests [`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) mutated either the original schema or the data being validated with the schema or both.


# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `invalid type for default, still valid when the invalid default is used`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "integer",
			"default": []
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
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `enums in properties, missing optional property is valid`
## Schema
```js
{
	"type": "object",
	"properties": {
		"foo": {
			"enum": [
				"foo"
			]
		},
		"bar": {
			"enum": [
				"bar"
			]
		}
	},
	"required": [
		"bar"
	]
}
```
## Original data
```js
{
	"bar": "bar"
}
```
## Data after validating with schema
```js
{
	"bar": "bar"
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `enums in properties, missing all properties is invalid`
## Schema
```js
{
	"type": "object",
	"properties": {
		"foo": {
			"enum": [
				"foo"
			]
		},
		"bar": {
			"enum": [
				"bar"
			]
		}
	},
	"required": [
		"bar"
	]
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
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `forbidden property, property absent`
## Schema
```js
{
	"properties": {
		"foo": {
			"not": {}
		}
	}
}
```
## Original data
```js
{
	"bar": 1,
	"baz": 2
}
```
## Data after validating with schema
```js
{
	"bar": 1,
	"baz": 2
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `object properties validation, doesn't invalidate other properties`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "integer"
		},
		"bar": {
			"type": "string"
		}
	}
}
```
## Original data
```js
{
	"quux": []
}
```
## Data after validating with schema
```js
{
	"quux": []
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `properties, patternProperties, additionalProperties interaction, patternProperty validates nonproperty`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "array",
			"maxItems": 3
		},
		"bar": {
			"type": "array"
		}
	},
	"patternProperties": {
		"f.o": {
			"minItems": 2
		}
	},
	"additionalProperties": {
		"type": "integer"
	}
}
```
## Original data
```js
{
	"fxo": [
		1,
		2
	]
}
```
## Data after validating with schema
```js
{
	"fxo": [
		1,
		2
	]
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `properties, patternProperties, additionalProperties interaction, patternProperty invalidates nonproperty`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "array",
			"maxItems": 3
		},
		"bar": {
			"type": "array"
		}
	},
	"patternProperties": {
		"f.o": {
			"minItems": 2
		}
	},
	"additionalProperties": {
		"type": "integer"
	}
}
```
## Original data
```js
{
	"fxo": []
}
```
## Data after validating with schema
```js
{
	"fxo": []
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `properties, patternProperties, additionalProperties interaction, additionalProperty ignores property`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "array",
			"maxItems": 3
		},
		"bar": {
			"type": "array"
		}
	},
	"patternProperties": {
		"f.o": {
			"minItems": 2
		}
	},
	"additionalProperties": {
		"type": "integer"
	}
}
```
## Original data
```js
{
	"bar": []
}
```
## Data after validating with schema
```js
{
	"bar": []
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `properties, patternProperties, additionalProperties interaction, additionalProperty validates others`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "array",
			"maxItems": 3
		},
		"bar": {
			"type": "array"
		}
	},
	"patternProperties": {
		"f.o": {
			"minItems": 2
		}
	},
	"additionalProperties": {
		"type": "integer"
	}
}
```
## Original data
```js
{
	"quux": 3
}
```
## Data after validating with schema
```js
{
	"quux": 3
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `properties, patternProperties, additionalProperties interaction, additionalProperty invalidates others`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "array",
			"maxItems": 3
		},
		"bar": {
			"type": "array"
		}
	},
	"patternProperties": {
		"f.o": {
			"minItems": 2
		}
	},
	"additionalProperties": {
		"type": "integer"
	}
}
```
## Original data
```js
{
	"quux": "foo"
}
```
## Data after validating with schema
```js
{
	"quux": "foo"
}
```

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

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Default value: 'foo' as number, Valid if not present`
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
{}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Does not see inexisting elements on new objects: 'foo' via required, Valid if not present`
## Schema
```js
{
	"properties": {
		"foo": {
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
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `Does not see inexisting elements on new objects: 'foo' via required, Valid if not present`
## Schema
```js
{
	"properties": {
		"foo": {
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
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `root pointer ref, mismatch`
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
	"bar": false
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `root pointer ref, recursive mismatch`
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
	"foo": {
		"bar": false
	}
}
```
## Data after validating with schema
```js
{
	"foo": {
		"bar": false
	}
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `relative pointer ref to object, match`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "integer"
		},
		"bar": {
			"$ref": "#/properties/foo"
		}
	}
}
```
## Original data
```js
{
	"bar": 3
}
```
## Data after validating with schema
```js
{
	"bar": 3
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `relative pointer ref to object, mismatch`
## Schema
```js
{
	"properties": {
		"foo": {
			"type": "integer"
		},
		"bar": {
			"$ref": "#/properties/foo"
		}
	}
}
```
## Original data
```js
{
	"bar": true
}
```
## Data after validating with schema
```js
{
	"bar": true
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `required validation, non-present required property is invalid`
## Schema
```js
{
	"properties": {
		"foo": {},
		"bar": {}
	},
	"required": [
		"foo"
	]
}
```
## Original data
```js
{
	"bar": 1
}
```
## Data after validating with schema
```js
{
	"bar": 1
}
```

# Side-effect on data
[`jsonschema`](https://github.com/tdegrunt/jsonschema#readme) had a side-effect on (altered the original) data in the test `required default validation, not required by default`
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
{}
```

[back to benchmarks](https://github.com/ebdrup/json-schema-benchmark)