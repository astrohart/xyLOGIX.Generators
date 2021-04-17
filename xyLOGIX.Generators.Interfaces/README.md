<a name='assembly'></a>
# xyLOGIX.Generators.Interfaces

## Contents

- [IFixedGeneratorTypeObject](#T-xyLOGIX-Generators-Interfaces-IFixedGeneratorTypeObject 'xyLOGIX.Generators.Interfaces.IFixedGeneratorTypeObject')
  - [GeneratorType](#P-xyLOGIX-Generators-Interfaces-IFixedGeneratorTypeObject-GeneratorType 'xyLOGIX.Generators.Interfaces.IFixedGeneratorTypeObject.GeneratorType')
- [IGenerator\`2](#T-xyLOGIX-Generators-Interfaces-IGenerator`2 'xyLOGIX.Generators.Interfaces.IGenerator`2')
  - [Generate(value)](#M-xyLOGIX-Generators-Interfaces-IGenerator`2-Generate-`0- 'xyLOGIX.Generators.Interfaces.IGenerator`2.Generate(`0)')
- [Resources](#T-xyLOGIX-Generators-Interfaces-Properties-Resources 'xyLOGIX.Generators.Interfaces.Properties.Resources')
  - [Culture](#P-xyLOGIX-Generators-Interfaces-Properties-Resources-Culture 'xyLOGIX.Generators.Interfaces.Properties.Resources.Culture')
  - [ResourceManager](#P-xyLOGIX-Generators-Interfaces-Properties-Resources-ResourceManager 'xyLOGIX.Generators.Interfaces.Properties.Resources.ResourceManager')

<a name='T-xyLOGIX-Generators-Interfaces-IFixedGeneratorTypeObject'></a>
## IFixedGeneratorTypeObject `type`

##### Namespace

xyLOGIX.Generators.Interfaces

##### Summary

Object that provides functionality for a particular
[GeneratorType](#T-xyLOGIX-Generators-Constants-GeneratorType 'xyLOGIX.Generators.Constants.GeneratorType')
value.

<a name='P-xyLOGIX-Generators-Interfaces-IFixedGeneratorTypeObject-GeneratorType'></a>
### GeneratorType `property`

##### Summary

A [GeneratorType](#T-xyLOGIX-Generators-Constants-GeneratorType 'xyLOGIX.Generators.Constants.GeneratorType')
value that specifies which type of generator this object is.

<a name='T-xyLOGIX-Generators-Interfaces-IGenerator`2'></a>
## IGenerator\`2 `type`

##### Namespace

xyLOGIX.Generators.Interfaces

##### Summary

Defines the publicly-exposed methods and properties of an object that
accepts inputs and transforms them into other values.

##### Generic Types

| Name | Description |
| ---- | ----------- |
| TInput | Name of the type that is provided as input to the generator. |
| TOutput | Name of the type of the output value. |

##### Remarks

A `Generator` object is very much akin to a `Translator`
object; however where they differ is that a `Translator` may
express a one-to-one mapping from an input object's members to an output
object's members; a `Generator` object may instead transform one
directly into another .

<a name='M-xyLOGIX-Generators-Interfaces-IGenerator`2-Generate-`0-'></a>
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

<a name='T-xyLOGIX-Generators-Interfaces-Properties-Resources'></a>
## Resources `type`

##### Namespace

xyLOGIX.Generators.Interfaces.Properties

##### Summary

A strongly-typed resource class, for looking up localized strings, etc.

<a name='P-xyLOGIX-Generators-Interfaces-Properties-Resources-Culture'></a>
### Culture `property`

##### Summary

Overrides the current thread's CurrentUICulture property for all
  resource lookups using this strongly typed resource class.

<a name='P-xyLOGIX-Generators-Interfaces-Properties-Resources-ResourceManager'></a>
### ResourceManager `property`

##### Summary

Returns the cached ResourceManager instance used by this class.
