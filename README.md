This is a repository used to store publicly avalaible data for an Earthquake Ontology model based on CIDOC-CRM (v. 7.2.4), CRMsci (v. 2.0) and CRMinf (v. 1.0).

- Basic_model (rdf,ttl) contains only the newly created classes and properties of this model, along with their super-classes and super-properties from CRM models. Also contains CRM model classes that are the domain or range of newly created properties of this model (CRM classes in this are created, not imported).

- Earthquake_model (rdf,ttl) contains newly created classes along with the imported CIDOC-CRM and CRMsci ontologies. Classes and properties from CRMinf we used were created in the model, as an updated example of the model is not available for import at the time of writing.

- Earthquake_model_with_examples (rdf,ttl) contains ' Earthquake_model ' and individuals connected using object and data properties.

- Individuals_only (rdf,ttl) contains only the individuals used.

- Earthquake_model (txt) provides newly created classes and properties information. It also provides the examples in "Earthquake_model_with_examples" (rdf,ttl) in text form.

- Query Examples (docx,odt) contains two example queries tested on "Earthquake_model_with_examples" (rdf,ttl).
