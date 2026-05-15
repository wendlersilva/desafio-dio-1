# Gerenciamento de Instâncias EC2 na AWS

## Descrição

Este laboratório teve como objetivo realizar a criação de uma instância EC2 utilizando a AWS, aplicando na prática os conceitos aprendidos durante as aulas.

O projeto foi desenvolvido como atividade prática da plataforma DIO para reforçar os conhecimentos sobre computação em nuvem e gerenciamento de instâncias no Amazon EC2.

---

# Etapas Realizadas

## 1. Acesso ao serviço EC2

Na primeira etapa, foi acessado o painel do serviço EC2 dentro da AWS para iniciar a criação de uma nova instância.

![Tela inicial da EC2](images/1.png)

---

## 2. Definição do nome e escolha do sistema operacional

Foi definido um nome para a instância e selecionada a imagem do sistema operacional Amazon Linux.

![Definição da instância](images/2.png)

---

## 3. Escolha do tipo da instância

Foi selecionada a instância do tipo `t2.micro`, que está disponível na camada gratuita da AWS.

Também não foi criado um par de chaves (Key Pair), pois não seria necessário realizar acesso SSH neste laboratório.

![Tipo da instância](images/3.png)

---

## 4. Configurações de segurança

Nenhum grupo de segurança adicional foi configurado e não foram habilitadas portas HTTP ou HTTPS, já que o objetivo era apenas criar a instância para fins de aprendizado.

![Configurações de segurança](images/4.png)

---

## 5. Criação da instância

As demais configurações permaneceram no padrão da AWS.

Por fim, foi marcada a opção para executar a instância e realizado o lançamento da máquina virtual.

![Criação da instância](images/5.png)

---

## 6. Instância em execução

Após a criação, a instância foi iniciada com sucesso e ficou disponível no painel da AWS com o status de execução.

![Instância rodando](images/6.png)

---

# Aprendizados

Durante este laboratório foi possível compreender:

* Como criar uma instância EC2 na AWS;
* Como selecionar imagens de sistemas operacionais;
* Como escolher tipos de instâncias;
* Conceitos básicos de configuração e segurança;
* Processo inicial de provisionamento de máquinas virtuais na nuvem.

---

# Conclusão

A prática permitiu consolidar os conhecimentos básicos sobre o Amazon EC2, proporcionando uma experiência prática com criação e gerenciamento inicial de instâncias na AWS.

---

# Tecnologias e Serviços Utilizados

* Amazon EC2
* Amazon Linux
* AWS Management Console
* GitHub

---

# Referências

* https://docs.aws.amazon.com/ec2/
