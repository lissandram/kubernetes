# kubernetes
Descrição dos comandos mais utilizados. 
## Propósito
Utilizar esse espaço para estudo.

## O que é Kubernetes
O Kubernetes é uma ferramenta de código aberto que dimensiona e gerencia aplicações em contêineres, realizando a implantação de forma automatizada.

## Para que serve o Kubernetes?
O Kubernetes serve para resolver um dos grandes problemas da implementação em contêineres: a necessidade de gerenciar os contêineres que executam as aplicações para que não haja tempo de inatividade.

Isso se deve ao fato de que, depois de terminado um contêiner, o outro precisa ser executado logo. Para isso, é bem mais eficiente fazer isso por meio de um sistema. É aí que entra o Kubernetes. Ele oferece uma estrutura para executar sistemas distribuídos de forma firme.

Cuida do escalonamento e da recuperação à falha de sua aplicação, fornece alguns padrões de implantação, entre outras funcionalidades.

## Comandos

### Comando para listar os pods (Um conjunto de um ou mais contêiners)
    kubectl get pods
### Comando para listar também deployments e serviços
    kubectl get services
### Comando para conseguir detalhes de um pod
    kubectl describe pod <nome-pod>
### Comando para descrever também deployments e serviços
    kubectl describe service <nome>


### Referências
* https://medium.com/programming-to-live/kubernetes-confira-os-comandos-mais-usados-abdc17f50364
* https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands
