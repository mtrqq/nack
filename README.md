## Description

Fork of NATS Controllers for Kubernetes (NACK) - https://github.com/nats-io/nack with DiscardPerSubject support


## Maintainers

| Name  | Email                   | Url                        |
| ----- | ----------------------- | -------------------------- |
| Mtrqq | <maxym.fugol@gmail.com> | <https://github.com/mtrqq> |

## Deployment

```shell
helm repo add nack-discard-fork https://mtrqq.github.io/nack
helm install nack nack-discard-fork/nack
```
