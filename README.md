# k8s-demo

## Descrição
Este repositório contém um exemplo de aplicativo Kubernetes.

## Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas em sua máquina:
- Docker
- Kubernetes

## Instalação
Siga as etapas abaixo para executar o aplicativo:

1. Clone este repositório:
    ```
    git clone https://github.com/seu-usuario/k8s-demo.git
    ```

2. Navegue até o diretório do projeto:
    ```
    cd k8s-demo
    ```

3. Construa a imagem Docker:
    ```
    docker build -t k8s-demo .
    ```

4. Execute o aplicativo no Kubernetes:
    ```
    kubectl apply -f deployment.yaml
    ```

## Uso
Após a instalação, você pode acessar o aplicativo em:

    Verifique o ip do seu minikue com:
    ```
    minikube ip
    ```
    Verifique a porta que o webapp está rodando.

    ip:30100 por ex.



## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).