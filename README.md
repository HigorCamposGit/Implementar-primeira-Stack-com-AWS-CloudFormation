# Implementar-primeira-Stack-com-AWS-CloudFormation.
# Meus Primeiros Passos com AWS: Entendendo o CloudFormation.

Oi! Este repositório foi criado para registrar minhas anotações e aprendizados durante as aulas da **Formação AWS Cloud Foundations** na **DIO [Digital Innovation One (DIO)](https://www.dio.me/)**.

---
**AWS Fundamentos** 
Como estou no início da minha jornada em nuvem, o meu objetivo aqui foi acompanhar as demonstrações práticas do professor Alexsandro Lechner, Arquiteto de Soluções AWS, e entender os conceitos principais e registrar tudo de forma simples.
linkedin.com/in/alexsandrolechner

---

## 📌 O que eu entendi das aulas?

Nas vídeo-aulas, o professor mostrou como funciona a criação de recursos na AWS utilizando a própria **interface gráfica** (o painel visual no navegador), sem complicações.

Durante a demonstração no painel da AWS, acompanhei o uso dos seguintes conceitos fundamentais.
Aqui estão os principais conceitos e palavras-chave que anotei:

* **AWS CloudFormation:** Serviço responsável por automatizar a criação e o gerenciamento da infraestrutura na nuvem de forma rápida.
* **Template (Modelo):** É a "receita" ou "manual de instruções" pré-configurado que diz à AWS o que deve ser criado.
* **Stack (Pilha):** É o grupo/pacote que reúne todos os recursos criados a partir de um Template. Se precisarmos apagar tudo depois, basta excluir a Stack com um clique.
* **AWS EC2:** O servidor/máquina virtual criado no primeiro laboratório.
* **Firewall (Security Group):** A camada de proteção e regras de rede criada no segundo laboratório.
* **Configure Stack Options:** A tela do painel onde ajustamos opções adicionais da Stack (como etiquetas de organização, permissões e tags) antes do lançamento.

---

## 🧭 O Caminho percorrido na Tela (Passo a Passo)

Acompanhando o professor mexendo no painel da AWS, o caminho que ele fez foi bem visual:

1. Ele entrou no serviço **CloudFormation** e foi na opção de **Stacks** (Pilhas).
2. Clicou no botão de criar uma nova Stack.
3. Escolheu o **Template 1** (o modelo pronto).
4. Deu um nome para a Stack e seguiu para a tela **Configure stack options** (onde ficam as opções de configurações da pilha, que no caso do teste continuaram no padrão).
5. Revisou as informações e colocou para criar.
6. Na aba **Events** (Eventos), deu para ver o passo a passo da AWS criando a máquina **EC2** até aparecer a mensagem de concluído (`CREATE_COMPLETE`).
7. Depois, ele mostrou que dá para fazer a mesma coisa para subir as configurações de **Firewall**.

---

## 🎯 Desafio entregue.
Criei o repositório com o resumo das aulas de AWS Fundamentos. Documentei o que aprendi sobre o CloudFormation, a criação de Stacks para EC2 e Firewall pelo painel visual e as etapas de configuração como o Configure stack options.
