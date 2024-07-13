#  4º HACKATHON – DEVOPS – IT TALENT 2024 

Este projeto foi desenvolvido para o quarto hackathon, tivemos a oportunidade de aplicar os conhecimentos adquiridos ao longo do curso. 

## Objetivo
Criar um ReplicaSet no Kubernetes com 1 instância do Banco de Dados e 2 instâncias do backend.

## Pré-requisitos 
- Conta no GitHub
- Minikube com kubectl

## Desafio
Para essa atividade, iremos criar um ReplicaSet com 1 instância do Banco de Dados e 2 do backend, usando os repositórios:
- Projeto de Banco de Dados: [moisesAlc/Banco-IT_Talent](https://github.com/moisesAlc/Banco-IT_Talent);
- Projeto de backend: [moisesAlc/Backend-IT_Talent](https://github.com/moisesAlc/Backend-IT_Talent);
- Criar um repositório no Github onde subirá o(s) arquivo(s) .yaml necessários para a criação desse ReplicaSet.

  ## Entregáveis
- print com a execução do ReplicaSet:
  ![Imagem1](https://github.com/ingridmoitinho/kubernetes-ittalent/blob/main/prints/1%20print%20com%20a%20execu%C3%A7%C3%A3o%20do%20ReplicaSet.png)
- print com a exclusão de um dos pods do ReplicaSet:
  ![Imagem2](https://github.com/ingridmoitinho/kubernetes-ittalent/blob/main/prints/2%20print%20com%20a%20exclus%C3%A3o%20de%20um%20dos%20pods%20do%20ReplicaSet.png)
- print demonstrando a subida de um novo pod para a normalização do ReplicaSet, feita automaticamente pelo K8S:
  ![Imagem3](https://github.com/ingridmoitinho/kubernetes-ittalent/blob/main/prints/3%20print%20demonstrando%20a%20subida%20de%20um%20novo%20pod.png)


