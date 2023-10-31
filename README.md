# webapp-systems

- query param system
  - type safe/schema based query param processing with serialization/deserialization of complicated data types
  - must support default options of each when value isnt specificed
  - should be pure typescript, not tied to specific framework
  - must validate and replace invalid values with defaultts

- navigation system
  - conditional navigation, cant navigate away from a page if certain conditions are/nt met

- fileupload system
  - abstraction over URL.createObjectUrl and URL.deleteObjectUrl to create an efficient cache of file uploads to prevent unncessary memory usage
