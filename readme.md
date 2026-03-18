### Validate spec
```shell
npx @redocly/cli lint --format=stylish --extends=recommended-strict --skip-rule=operation-4xx-response seamless-wallet-api.yaml 
```

### Build docs
```shell
npx @redocly/cli build-docs seamless-wallet-api.yaml
mv redoc-static.html index.html
```
