# form system

## Structure & Organization
- sub forms with same semantics as main form, despite `<form>` not being allowed to nest
- sub sections (scoped to namespace)
- list/array types
- multiple steps with different validation on each

## Form Elements & Data Handling
- form components must selectively register their initial values if they are not present in form context
  - facilitates dynamic addition/removal of form sections without toggling controlled/uncontrolled state
- input and output types with note: initial values might differ from output
- field encoders to convert to/from specific data types
- support for complex data types like classes and objects

## Lifecycle & Extensibility
- hook into form life cycles with support for a plugin system
- automatic persistence to multiple data stores

## Validation
- schema-based validation

# subform vs subsection
- subform: a complete form with its own submission criteria and context
- subsection: a namespace within a form
