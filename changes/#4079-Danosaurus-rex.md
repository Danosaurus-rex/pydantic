Arbitrary types (types without validators/a `__modify_schema__` classmethod) are 
ignored (and a `UserWarning` is raised) when trying to generate a schema from 
a model containing references to arbitrary types. Additionally works for 
subfields.
