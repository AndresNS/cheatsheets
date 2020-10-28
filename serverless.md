[Documentation](https://www.serverless.com/framework/docs/providers/aws/cli-reference/)

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
sls invoke local -f [function_name] --stage local
```

Deploy en AWS
```
sls deploy --stage local|dev|prod
```
