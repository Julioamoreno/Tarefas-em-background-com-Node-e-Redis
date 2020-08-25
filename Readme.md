# Tarefas em Background utilizando node e redis

> O projeto tem como finalidade a criação de uma queue através da lib
> bull, e utilizando o redis para salvar os dados que estão sendo
> processados.

## Funcionalidade

> A funcionalidade desse projeto se dá pela criação de uma conta, com
> a geração de uma senha aleatória que posteriormente é enviada para o
> cliente através do email do cadastro. Nesse projeto foi utilizado o
> serviço do Mailtrap, para ter o feedback instantâneo da chegada dos
> emails.

## Técnologias

- Node
- Express
- Bull
- Redis
- Mailtrap

## Instalação

OS X | Linux | Windows:

```
1 - Clone ou Download do repositório

2 - Yarn ou Npm install

3 - Criação da conta do Mailtrap

4 - Instalação do redis

5 - Preencher as variáveis de ambiente, respectivamente com porta do node, host do email, porta do email, usuario de email, senha do email, host do redis e porta do redis.
```

## Próximas Implementações

- [] Adcionar o usuário de forma mais real, sem manter a senha em
  plain text.
- [] Testar outra biblioteca de filas.
- [] Criar um microserviço com essas mesmas funcionalidades.

## Meta

Júlio Armando -
[@julioamoreno](https://www.linkedin.com/in/julioamoreno/)

## Referências

Esse projeto de baseia no desafio do bootcamp da Digital Innovation
One - Desenvolvimento Node.js.
