Run the RDF HDT cpp implementation to convert RDF to HDT (or the other way around).

Use Docker Image from https://hub.docker.com/r/rdfhdt/hdt-cpp  

## Usage

### RDF to HDT

```yaml
- uses: vemonet/rdfhdt-action@master
  with:
    input: my_file.nt
    output: my_file.hdt
```

### HDT to RDF

```yaml
- uses: vemonet/rdfhdt-action@master
  with:
  	operation: hdt2rdf
    input: my_file.hdt
    output: my_file.nt
```

