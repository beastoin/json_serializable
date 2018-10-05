# fields

| Field | JsonSerializable | JsonKey | Description |
| --- | :---: | :---: | --- |
| `disallowUnrecognizedKeys` | ✓ |  | If `false` (the default), then any unrecognized keys passed to the generated FromJson factory will be ignored. |
| `createFactory` | ✓ |  | If `true` (the default), a private, static `_$ExampleFromJson` method is created in the generated part file. |
| `createToJson` | ✓ |  | If `true` (the default), code for decoding JSON is generated fon this class. |
| `includeIfNull` | ✓ | ✓ | `true` if the generator should include this field in the serialized output, even if the value is `null`. |
| `nullable` | ✓ | ✓ | When `true`, `null` values are handled gracefully when serializing the field to JSON and when deserializing `null` and nonexistent values from a JSON map. |
| `fieldRename` | ✓ |  | Defines the automatic naming strategy when converting class field names into JSON map keys. |
| `name` |  | ✓ | The key in a JSON map to use when reading and writing values corresponding to the annotated fields. |
| `ignore` |  | ✓ | `true` if the generator should ignore this field completely. |
| `fromJson` |  | ✓ | A top-level `Function` to use when deserializing the associated JSON value to the annotated field. |
| `toJson` |  | ✓ | A top-level `Function` to use when serializing the annotated field to JSON. |
| `defaultValue` |  | ✓ | The value to use if the source JSON does not contain this key or if the value is `null`. |
| `required` |  | ✓ | When `true`, generated code for `fromJson` will verify that the source JSON map contains the associated key. |
| `disallowNullValue` |  | ✓ | If `true`, generated code will throw a `DisallowedNullValueException` if the corresponding key exits, but the value is `null`. |
