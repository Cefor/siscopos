
# Sistema de Coordenação de Pós-Graduação - SisCopos

O SisCopos é um sistema informatizado desenvolvido para apoiar a gestão acadêmica do Programa de Pós-Graduação da Câmara dos Deputados (PPG-Cefor). Seu desenvolvimento teve início em janeiro de 2023, como parte de iniciativa de modernização do Programa, com o objetivo de automatizar processos internos antes realizados manualmente, sujeitos a falhas e exigentes em termos de tempo e esforço.

![Tela de estatísticas](imagem/estatisticas.png)

## Autor: Fabiano Peruzzo Schwartz

## Objetivo

O SisCopos tem por objetivo garantir maior integridade, eficiência e transparência na gestão dos dados acadêmicos, consolidando um modelo robusto de governança da informação, com impacto direto na agilidade e confiabilidade dos registros relacionados a:

* Cursos e linhas de pesquisa
* Disciplinas e componentes curriculares
* Cadastro de docentes e discentes (regulares e especiais)
* Matrículas, trancamentos e atividades complementares
* Exames de qualificação, defesas de TCC e emissão de histórico escolar

## Arquitetura de desenvolvimento

* Back-end: Java 8+
* Framework: Spring Boot (versão usada: 1.5.6.RELEASE)
* Banco de dados: MySQL
* Gerenciador de dependências: Maven (pom.xml)
* Front-end: Thymeleaf/Bootstrap

## Estrutura do Projeto

```
siscopos/
├── pom.xml
└── src/
    ├── main/
    │   ├── java/
    │   │   └── br/
    │   │       └── leg/
    │   │           └── camara/
    │   │               └── copos/
    │   └── resources/
    │       ├── templates/
    │       └── application.properties
    └── test/
```

## Instruções

* Instale o **Spring Tool Suit - STS**.
* Baixe a pasta **src** e o arquivo **pom.xml** em uma pasta apropriada no **workspace** do Eclpipse.
* Importe os arquivos como **Existing Maven Projects**.
* Crie um esquema denominado **copos** no banco de dados MySQL: usuário **root**, senha em branco.
* Rode a aplicação.
* Faça o login:
  * com o e-mail **admin@copos.edu** e senha **admin** para perfil de administrador
  * com o e-mail **apoio@copos.edu** e senha **apoio** para simular o perfil de apoio
  * com o e-mail **consulta@copos.edu** e senha **consulta** para simular o perfil de consulta
  * com o e-mail **painel@copos.edu** e senha **painel** para simular o perfil de painel
