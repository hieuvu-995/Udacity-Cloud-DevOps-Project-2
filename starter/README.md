# CD12352 - Infrastructure as Code Project Solution
# [github.com/hieuvu-995]

## Create:

- Create networking resource
```
$sh scripts/create.sh udagram-project-2-network-stack network.yml network-params.json
```
- Create servers
```
$ scripts/create.sh udagram-project-2-servers-stack servers.yml servers-params.json
```

## Update
```
$sh scripts/update.sh *stack-name *script.yml *params.json
```

example: $ sh scripts/update.sh udagram-project-2-servers-stack servers.yml servers-params.json

## Delete
```
$sh scripts/delete.sh *stack-name
```

# Endpoint Link :
http://udagra-webse-iepfokuyvlos-790020358.us-east-1.elb.amazonaws.com/
