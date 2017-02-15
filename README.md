
# nodejs_cache Step
Cache `./node_modules` directory

### INPUTS
* `FLOW_ENABLE_CACHE` - 

## EXAMPLE 

```yml
steps:
  - name: nodejs_cache
    enable: true
    failure: true
    plugin:
      name: nodejs_cache
      inputs:
        - FLOW_ENABLE_CACHE=$FLOW_ENABLE_CACHE
```
