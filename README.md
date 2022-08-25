# Schema

The schema of a block is in YAML format. 

It is defined by its inputs and outputs. 

```yaml
name: Addition
description: Adds two arguments together and returns the result
input: 
  - name: arg1
    type: int64
    value: 1
  - name: arg2
    type: int64
    value: 2
output:
  - name: out
    type: int64   

```


