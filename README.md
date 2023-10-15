# webapp-systems

- query param system
  - type safe/schema based query param processing with serialization/deserialization of complicated data types
  - must support default options of each when value isnt specificed
  - should be pure typescript, not tied to specific framework
  - must validate and replace invalid values with defaultts

- navigation system
  - conditional navigation, cant navigate away from a page if certain conditions are/nt met

- form system
  - must support sub forms with same semantics as main form, despite <form> not being allowed to nest 
  - form legos must be able to selectively register their initial values if they are not present in form context
    - this allows dynamically adding/removing sections of forms without controllex/uncontrolled switch
