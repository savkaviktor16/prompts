| NAME           | PROMPT                           | DESCRIPTION                                      | EXAMPLE                                   |
|----------------|----------------------------------|--------------------------------------------------|-------------------------------------------|
| app                 | generate a pod YAML with 2 labels spec ports                                    |                 |              |
| app-livenessProbe   | generate a pod YAML in namespace demo with spec livenessProbe and ports http    |    |                           |
| app-readinessProbe  | generate a pod YAML without labels with spec livenessProbe, readinessProbe and ports http |  |                   |
| app-volumeMounts    | generate a pod YAML without labels with spec livenessProbe, readinessProbe, ports http and volumes |     |      |
| app-cronjob         | generate a cronjob YAML |  |  |
| app-job             | generate a Job YAML that copies data from GCS to a disk |   |  |
| app-multicontainer  | generate a pod YAML with nginx and debian containers, volume |    |         |
| app-resources       | generate a pod YAML with resources, livenessprobe and readinessprobe |          |   |
| app-secret-env      | generate a simple pod YAML for secret purposes |     |  |