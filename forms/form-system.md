# form system
  - sub forms with same semantics as main form, despite <form> not being allowed to nest 
  - form legos must be able to selectively register their initial values if they are not present in form context
    - this allows dynamically adding/removing sections of forms without controllex/uncontrolled switch
  - allow hooking into form life cycles
    - should support a plugin system
  - input and output types
    - initial values dont always match output
  - automatic persistence to multiple data stores