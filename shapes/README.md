# SHACL Shapes

This folder contains the **SHACL (Shapes Constraint Language) shapes** associated with the ontology.  
These shapes are used to **validate RDF data** and ensure that instance data conforms to the ontology’s structure, constraints, and semantics.

# Purpose
The goal of this directory is to store the **validation rules and constraints** defined for the ontology.  
SHACL shapes help verify that data using the ontology follows the intended model by checking class memberships, property ranges, cardinalities, and other structural conditions.

# Contents
Include here any files that define SHACL shapes, such as:

- `.ttl` — SHACL shapes written in Turtle syntax  
- `.rdf` — SHACL shapes in RDF/XML format  
- `.jsonld` — SHACL shapes in JSON-LD format  

You may also include supporting documentation that explains the validation logic or usage instructions.

# Best Practices
- Keep SHACL shapes **consistent** with the latest version of the ontology.  
- Validate all example datasets (stored in `/examples/`) against these shapes regularly.  
- Document the purpose and scope of each shape (e.g., class-level, property-level, dataset-level).  
- Use modular design if your ontology includes multiple domains or modules (e.g., `/shapes/core/`, `/shapes/extensions/`).

# Notes
- This folder is for **validation and constraint definitions only** — not for ontology implementation or example data.  
- Consider maintaining a changelog to track updates to SHACL rules.