# Merging Workspace

-Copy all imports and main NCO file into folder
-Run OBO ROBOT merge command, along with annotation. See below

## OBO ROBOT command line

robot merge --inputs "*.owl" --include-annotations true annotate --ontology-iri http://w3id.org/nco --version-iri http://w3id.org/nco/2025-09-09/nco.owl --annotation-file annotations.ttl --output results/nco.owl



N.B. substitute the versioning information to the appropriate date
