
# Sistema de Coordenação de Pós-Graduação - SisCopos

O presente projeto tem por objetivo a construção de sistema informatizado para dar suporte aos processos de trabalho de programas de pós-graduação em nível *lato* e *stricto sensu*.

O desenvolvimento é baseado nas experiências e procedimentos adotados no Programa de Pós-Graduação da Câmara dos Deputados.

## Autor: Fabiano Peruzzo Schwartz

## Arquitetura de desenvolvimento
* Spring Boot MVC
* JPA
* Thymeleaf
* Bootstrap
* Devtools

## Instruções

* Instale o **Spring Tool Suit - STS**.
* Baixe a pasta **src** e o arquivo **pom.xml** em uma pasta apropriada no **workspace** do Eclpipse.
* Importe os arquivos como **Existing Maven Projects**.
* Crie um esquema denominado **copos** no banco de dados MySQL: usuário **root**, senha em branco.
* Rode a aplicação.
* Faça o login:
  * com o e-mail **admin@copos.edu** e senha **admin** para perfil de administrador
  * com o e-mail **apoio@copos.edu** e senha **apoio** para simular o perfil de apoio
