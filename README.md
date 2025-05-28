| NAME           | PROMPT                           | DESCRIPTION                                      | EXAMPLE                                   |
|----------------|----------------------------------|--------------------------------------------------|-------------------------------------------|
| app                 | generate a pod YAML with 2 labels spec ports                                    |                 |  https://github.com/savkaviktor16/prompts/blob/main/yaml/app.yaml |
| app-livenessProbe   | generate a pod YAML in namespace demo with spec livenessProbe and ports http    |    |  https://github.com/savkaviktor16/prompts/blob/main/yaml/app-livenessProbe.yaml  |
| app-readinessProbe  | generate a pod YAML without labels with spec livenessProbe, readinessProbe and ports http |  | https://github.com/savkaviktor16/prompts/blob/main/yaml/app-readinessProbe.yaml |
| app-volumeMounts    | generate a pod YAML without labels with spec livenessProbe, readinessProbe, ports http and volumes |     |  https://github.com/savkaviktor16/prompts/blob/main/yaml/app-volumeMounts.yaml |
| app-cronjob         | generate a cronjob YAML |  | https://github.com/savkaviktor16/prompts/blob/main/yaml/app-cronjob.yaml |
| app-job             | generate a Job YAML that copies data from GCS to a disk |   | https://github.com/savkaviktor16/prompts/blob/main/yaml/app-job.yaml |
| app-multicontainer  | generate a pod YAML with nginx and debian containers, volume |    | https://github.com/savkaviktor16/prompts/blob/main/yaml/app-multicontainer.yaml  |
| app-resources       | generate a pod YAML with resources, livenessprobe and readinessprobe |          | https://github.com/savkaviktor16/prompts/blob/main/yaml/app-resources.yaml  |
| app-secret-env      | generate a simple pod YAML for secret purposes |     | https://github.com/savkaviktor16/prompts/blob/main/yaml/app-secret-env.yaml |
