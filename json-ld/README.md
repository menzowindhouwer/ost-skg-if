
# Experiments with JSON-LD and validation using [SHACL](https://www.w3.org/TR/shacl/)

- builds on https://github.com/essepuntato/skg-if

- Turtle instances created using [convert.py](https://github.com/essepuntato/skg-if/blob/main/convert.py)

```sh
python3 convert.py example-agent.json > example-agent.ttl
```

- Validation done using [pySHACL](https://github.com/RDFLib/pySHACL)

```sh
pyshacl -s AgentShape.ttl -m -i rdfs -f human example-agent.ttl
```

 ## results

 
