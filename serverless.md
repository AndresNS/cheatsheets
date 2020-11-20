[Documentation](https://www.serverless.com/framework/docs/providers/aws/cli-reference/)

Create serverless project:
```
npm init
npm install serverless
serverless create --template aws-nodejs
```

Install dependencies:
```
npm install serverless-offline serverless-dynamodb-local
```

Start serverless offline:
```
sls offline start
```

Preview `serverless.yml` with all the variables resolved:
```
sls print --stage dev|local|prod|anything
```

Invoke a single function:
```
sls invoke local -f [function_name] --stage local --path ./invokes/listener.json
```

Deploy en AWS
```
sls deploy --stage local|dev|prod
```
