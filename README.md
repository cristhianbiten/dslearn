# DSLearn
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/cristhianbiten/dslearn/blob/main/LICENSE) 

# Sobre o projeto

Projeto desenvolvido durante o módulo de domínio, ORM e autorizações do Bootcamp Spring da DevSuperior.

# Visão geral do sistema

O sistema consiste em uma plataforma de ensino que mantém informações de cursos, suas turmas e alunos, bem como um fórum para perguntas e respostas sobre os conteúdos do curso. Os atores do sistema podem ser alunos e professores. Há também usuários administradores, que são os únicos autorizados a cadastrar cursos e turmas.

Um curso é composto de vários “recursos”, que são grupos de conteúdos. Estes recursos podem ser trilhas de aprendizado, bônus, links externos, e o próprio fórum de perguntas e respostas do curso. Cada recurso pode conter seções, e estas seções por sua vez é que vão conter as aulas, que podem ser conteúdos em vídeo e/ou texto, ou tarefas para serem entregues pelos alunos.

Uma tarefa pode ter um peso, uma data de entrega, um número de questões e a quantidade mínima de acertos necessários para ser aceita. Quando um aluno entrega a tarefa, esta fica aguardando pelo feedback do professor, e ela pode ser aceita ou rejeitada.

Cada nova turma do curso corresponde a uma oferta ou edição deste curso, que possui uma data de início e fim. Diferentes ofertas do mesmo curso podem ter pequenas variações no conteúdo, conforme a necessidade de customização para cada turma.


## Modelo conceitual
![Modelo Conceitual](https://github.com/cristhianbiten/assets/blob/main/dslearn.jpg)


# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- H2
- Spring Security
- JWT
- OAuth 2

# Como executar o projeto

## Back end
Pré-requisitos: Java

[Tutorial de instalação Java](https://www.youtube.com/watch?v=QekeJBShCy4)

```bash
# Clonar repositório
git clone https://github.com/cristhianbiten/dslearn.git

# Entrar na pasta do projeto dslearn
cd dslearn

# Entrar na pasta do projeto back end
cd backend

# Executar o projeto
./mvnw spring-boot:run
```

## Testes manuais
Pré-requisitos: Postman

[Collection do Postman](https://www.getpostman.com/collections/b156d5adf224f89f6ca3)


# Autor

Cristhian Bitencourt

https://www.linkedin.com/in/cristhian-bitencourt-588b3317a/
