Infra for monitoring example

## fly command
my  command
```
fly -t pgr301 sp -p pipeline_name -c concourse/pipeline.yml -l credentials.yaml
```
command template
```
fly -t ≤target> sp -p pipeline_name -c concourse/pipeline.yml -l credentials.yaml
```