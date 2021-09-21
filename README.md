# Projeto de Infra as Code

O projeto tem a lição de mostrar que é possível fazer uma infra totalmente programavel, evitando passos manuais para facilitar a entrega de uma infraestrutura ágil e de facil entendimento.

Todos os recursos usados foram baseados na percepção de melhor estratégia para o desafio e pensando em expandir não apenas ao que foi pedido mas que com uma pequena mudança pode atender outras features.


## Quais ferramentas foram utlizadas e porque o uso destas?

**° Terraforms**: Dentre todos os gerenciadores para criação de instancias o terraforms foi o mais amigavel e de facil utilização. O que mais me motivou em usar ele foi a vasta documentação que possúi e a comunidade ser ativa tendo assim respostas para muitas das duvidas que tive dentro do processo alem de ser uma ferramenta muito simples e de facil entendimento.

**° Ansible**: Antes de usar o ansible eu pesquisei outras ferramentas pois queria ser um pouco diferente mas vi que muitas delas não atenderiam o proposito deste processo. (Vangrant, puppet... etc). Diferente dessas outras duas o Ansible tem uma capacidade de fazer todas as tarefas de forma muito simples. Num teste que fiz eu subi cerca de 15 maquinas ao mesmo tempo aonde o ansible configurou todas padronamente e ao mesmo stage de tempo para cada tarefa. A organização e simplicidade foi o que me fez optar por usar ele.

**° GCP**: Primeira vez que trabalhei com GCP é simplesmente incrivel a infraestrutura deles. Painel completo, muita doc por parte não só da google mas com a comunidade não tem como tu passar sufoco usando essa plataforma.

**° Docker**: Acredito que não exista sistema melhor que o docker hoje em dia para container. Como todas as outras opções  alem da super compatibilidade que possui já integrado com as outras ferramentas como (Ansible e o Nginx) não poderia optar por outro a não ser ele.

**° Nginx**: Efetuei a configuração do nginx em todas as instancias, para fazer a melhor manobra do proxy com uso das portas disponiveis dentro do ambiente. Alem de ser um excelente webserver a facil integração com docker facilitou muito a utilização da estrutura.
