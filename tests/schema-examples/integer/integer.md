# jsonschema-markdown

JSON Schema missing a description, provide it using the `description` key in the root of the JSON document.

| Property | Type | Required | Possible Values | Deprecated | Default | Description | Examples
| -------- | ---- | -------- | --------------- | ---------- | ------- | ----------- | --------
| firstName | `string` |  | string|  |  | The person's first name. | |
| lastName | `string` |  | string|  |  | The person's last name. | |
| age | `integer` |  | `0 <= x <= 150` and multiple of `1`|  | `25` | Age in years which must be equal to or greater than zero. | |
