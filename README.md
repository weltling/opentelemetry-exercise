
# Preparation

## Ubuntu

apt-get install docker.io nodejs node-npm code

# Node.js

```
npm i @opentelemetry/core @opentelemetry/node @opentelemetry/plugin-http @opentelemetry/plugin-https \
	@opentelemetry/exporter-zipkin @opentelemetry/tracing express
npm i @opentelemetry/plugin-express
```

# Zipkin Container

docker run --rm -d -p 9411:9411 --name zipkin openzipkin/zipkin

