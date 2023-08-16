<a name='assembly'></a>
# xyLOGIX.Generators

## Contents

- [GeneratorBase\`2](#T-xyLOGIX-Generators-GeneratorBase`2 'xyLOGIX.Generators.GeneratorBase`2')
  - [GeneratorType](#P-xyLOGIX-Generators-GeneratorBase`2-GeneratorType 'xyLOGIX.Generators.GeneratorBase`2.GeneratorType')
  - [Generate(value)](#M-xyLOGIX-Generators-GeneratorBase`2-Generate-`0- 'xyLOGIX.Generators.GeneratorBase`2.Generate(`0)')
- [Resources](#T-xyLOGIX-Generators-Properties-Resources 'xyLOGIX.Generators.Properties.Resources')
  - [Culture](#P-xyLOGIX-Generators-Properties-Resources-Culture 'xyLOGIX.Generators.Properties.Resources.Culture')
  - [ResourceManager](#P-xyLOGIX-Generators-Properties-Resources-ResourceManager 'xyLOGIX.Generators.Properties.Resources.ResourceManager')

<a name='T-xyLOGIX-Generators-GeneratorBase`2'></a>
## GeneratorBase\`2 `type`

##### Namespace

xyLOGIX.Generators

##### Summary

Defines the events, methods, and properties that can be used by all
concrete `Generator` object implementations.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| TInput | Name of the type of the input value. |
| TOutput | Name of the type of the output value. |

<a name='P-xyLOGIX-Generators-GeneratorBase`2-GeneratorType'></a>
### GeneratorType `property`

##### Summary

A [GeneratorType](#T-xyLOGIX-Generators-Constants-GeneratorType 'xyLOGIX.Generators.Constants.GeneratorType')
value that specifies which type of generator this object is.

<a name='M-xyLOGIX-Generators-GeneratorBase`2-Generate-`0-'></a>
### Generate(value) `method`

##### Summary

Transforms the input `value` into the output value.

##### Returns

A `TOutput` whose value is the result of the
transformation.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| value | [\`0](#T-`0 '`0') | Reference to an instance of `TInput` that is
the value to be transformed. |

<a name='T-xyLOGIX-Generators-Properties-Resources'></a>
## Resources `type`

##### Namespace

xyLOGIX.Generators.Properties

##### Summary

A strongly-typed resource class, for looking up localized strings, etc.

<a name='P-xyLOGIX-Generators-Properties-Resources-Culture'></a>
### Culture `property`

##### Summary

Overrides the current thread's CurrentUICulture property for all
  resource lookups using this strongly typed resource class.

<a name='P-xyLOGIX-Generators-Properties-Resources-ResourceManager'></a>
### ResourceManager `property`

##### Summary

Returns the cached ResourceManager instance used by this class.
