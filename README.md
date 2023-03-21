# Social Sport
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/AdautoBenevides/SocialSport/blob/main/LICENSE) 


# Equipe:

- Adauto Benevides Couto
- João Vitor Nascimento de Souza

# Sobre o projeto

O SocialSport é uma aplicação full stack web desenvolvida durante o 3º semestre do curso de Análise e Desenvolvimento de Sistemas, no Instituto Federal de Educação, Ciência e Tecnologia Baiano, Campus Guanambi - BA. 

O SocialSport é um lugar onde você poderá experimentar diversas experiências, desde montar pequenas equipes — para organizar pequenas partidas — até montar campeonatos e ligas, onde vários times participam e somente uma das equipes será a campeã, na qual a melhor das equipes será recompensada. Além disso, existem alguns componentes na aplicação, são eles: 
 - Os jogadores, que podem ser cadastrados e alocados a uma equipe;
 - Os times, que podem receber novos jogadores, e participar de partidas convencionais, de campeonatos, e de ligas;
 - Os locais, que definem onde a partida irá acontecer;
 - O Administrador, que cadastra os locais para que partidas possam acontecer, além conseguirem punir os jogadores, que ao receberem cinco (5) punições são expulsos do time ao qual pertencem;
 - Os esportes, definem quais são os esportes disponíveis para que possa ocorrer novas partidas, campeonatos e ligas;
 - As partidas, que acontecem após a formação de dois times, no entanto, se a partida for de futsal, só poderá acontecer se cinco (5) jogadores forem escalados para a partida, e se a partida for de vôlei seis (6) jogador devem ser escalados.
 - Os campeonatos, que precisam de quatro (4) times para iniciar, sendo organizados em seminais e final, onde os vencedores das seminais se enfrentam na final, e o campeão é premiado com medalhas;
 - As ligas, que precisam de oito (8) times para começar, sendo organizado em quartas-de-final, semifinais e final, o time campeão é premiado com um troféu.
  

# Tecnologias utilizadas

## IDE
Eclipse IDE for Enterprise Java and Web Developers

## Back end
- Java
- JDBC
## Front end
- HTML
- CSS
- JSP
- JS (JavaScript)

## Implementação em produção
- Back end: Eclipse IDE for Enterprise Java and Web Developers
- Front end web: JSP
- Banco de dados: MySQL
- Ferramenta de design de banco de dados: MySql Workbench

# Como executar o projeto

## Back end
Pré-requisitos: 
 - OpenJDK 11;
 - MySql   


## Front end web
Pré-requisitos: Linguagem JavaScript


# Passos para Execução do Projeto

## Pré requisitos
- OpenJDK 11;
- IDE: Eclipse Enterprise Java and Web Developers
- Apache Tomcat version v10.1

``` bash
#instalando o openjdk 11
Vá em https://adoptopenjdk.net/ 
e baixe a versão OPENJDK 11 (LTS)

#instalando o eclipse
Vá em https://www.eclipse.org/downloads/
e baixe o eclipse
Na instalação escolha a opção Eclipse IDE for Enterprise Java Developers
Siga os passos e finalize a instalção


#instalando o Apache Tomcat
Vá em https://tomcat.apache.org/
e baixe a versão Tomcat 10.1.5
Extraia o arquivo e uma pasta e 
cole em Disco Local (C:)
```

## Passo 1 - Baixar o todo o projeto do GitHub

Baixe os arquivos do projeto e extraia-o dentro de um diretório

## Passo 2 - Abrir projeto no Eclipse Web Programming

Abra o Eclipse e vá  em ```File``` > ```Open Projects from File System...``` e escolha a pasta do projeto

``` bash
OBS.: O nome do administrador
e a senha é aplicado diretamente no banco de dados
```

## Passo 3 - Configurar o Tomcat no Eclipse

1. Na aba inferior encontre a guia ```Servers```, clique com o botão direito do mouse vá em ```New``` e clique em ```Server```.
2. Na janela que abrir vá em ```Apache``` e escolha a versão do Tomcat instalado na sua máquina e clique em ```next```.
3. Na guia que surgiu selecione o projeto e clique em ```add```, finalize clicando em ```Finish```.

## Passo 4: Executar o projeto

Clique no botão ```Run``` e selecione a configuração do servidor que você acabou de criar. Verifique se o projeto está sendo executado corretamento acessando o endereço https://localhost:8080 no navegador.

## Passo 5: Executar script SQL

Execute o script SQL fornecido eem seu SGBD MySQL para completar a instalação do projeto.

CREATE DATABASE IF NOT EXISTS sportsocial;

Entre em todas as classe DAO que estao em 
SocialSport/Java Resources/src/main/java/model/ e troque as variáveis user e password para a senha e usuário do seu MySQL


# Layout do projeto

## Página Inicial / Home Page
![Home Page](https://github.com/joaovitornso/SocialSport/blob/master/assets/home-page.png)

## Login
![Login1](https://github.com/joaovitornso/SocialSport/blob/master/assets/Login-Part1.png)
![Login 2](https://github.com/joaovitornso/SocialSport/blob/master/assets/Login-Part2.png)

## Organizar campeonato
![Organizar Campeonato](https://github.com/joaovitornso/SocialSport/blob/master/assets/organizarCampeonato.png)

## Placar da partida
![Placar da Partida](https://github.com/joaovitornso/SocialSport/blob/master/assets/placar_partida.png)

# Link de vídeo explicando o sistema no YouTube
```https://youtu.be/9VOXavmCM9k```

# Autores

- Adauto Benevides Couto
- João Vitor Nascimento de Souza

- www.linkedin.com/in/joaovitornso
- https://www.linkedin.com/in/adauto-benevides-b61119263/
