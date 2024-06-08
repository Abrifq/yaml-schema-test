# Yaml as JSON-Schema Testing Ground

Why not?

Seriously, why not? We parse YAML into JSON objects anyway.

## Testing

~~Use this fork of v8r: [Abrifq's fork of v8r](https://github.com/Abrifq/v8r)~~
The [PR chris48s/v8r/#364](https://github.com/chris48s/v8r/pull/364) has merged, try it with

```bash
npx v8r example-product.yaml --schema schema.yaml
```

## Disclaimers and references

I'm using an edited version of [json-schema.org](https://json-schema.org)'s [tutorial schema](http://json-schema.org/learn/getting-started-step-by-step.html),
converting with an online YAML-to-JSON converter from [transform.tools](https://transform.tools/json-to-yaml)
