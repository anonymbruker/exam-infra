Infra for monitoring example

## fly command
my  command
```
fly -t pgr301 set-pipeline -c exam-infra/concourse/pipeline.yml -l exam-infra/credentials.yml -p pipeline_name
```
command template
```
fly -t <target> set-pipeline -c <root-folder>/concourse/pipeline.yml -l <root-folder>/credentials.yml -p pipeline_name
```