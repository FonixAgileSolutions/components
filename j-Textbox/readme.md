## j-Textbox

__Attributes__:

- `data-component-type=""` (optional), supports __email__, __password__, __date__, __number__ or __currency__ default __empty__
- `data-required="true"` (optional) the field must have some value, default __false__
- `data-icon="fa-envelope"` (optional) the label icon, default __empty__
- `data-placeholder="some placeholder"` (optional) the placeholder for the input, default __empty__
- `data-align=""` (optional) text align (default __left__)
- `data-autofocus="true"` (optional) auto focus, default __false__
- `data-control-icon="fa-envelope"` (optional) adds icon into the html control
- `data-component-keypress-delay` - more in jComponent documentation
- `data-component-keypress` - more in jComponent documentation
- `data-increment="true"` - appends increment/decrement numbers (works with `number` and `currency` - `data-component-type`)
- `data-component-format` - works with `date` only e.g. `dd.MM.yyyy`
- `data-validate="value.match(/[a-z]+/) !== null"` - can add a custom validation
- `data-name="password" (optional) adds name attribute to input

__Methods__:
- `component.required(value)` - can enable/disable `required` with validation

__Interesting:__

If you `data-component-type="date"` then the component uses `calendar` component (an application must depend `calendar` component).

### Author

- Peter Širka <petersirka@gmail.com>
- License: MIT