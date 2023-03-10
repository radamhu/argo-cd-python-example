# Develop and deploy a Flask application

## Develop a Flask application which can communicate with the Redis database. The application should 
have the following endpoints:

- /healthz: return the string "ok" (without quotes)
- /alert: increment a counter in redis
- /counter: print the value of the counter
- /version: return the short git commit hash

Deploy your Flask application into the Kubernetes cluster. Use liveness probe to let Kubernetes know 
whether your app is healthy. 
