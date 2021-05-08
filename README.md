# DS Vendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/RangelMoreira/projeto-sds3/blob/main/LICENSE) 

# Sobre o projeto

https://kevin-dsvendas.netlify.app/

DS Vendas é uma aplicação full stack web construída durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um dashboard o qual apresenta dados referentes as vendas realizadas. Nela é apresentada uma tabela que exibe de maneira paginada o desempenho das vendas de cada vendedor, a aplicação apresenta ainda um gráfico de barras com a taxa de sucesso por vendedor e um gráfico de rosca com a porcentagem individual de vendas.

## Layout web
![Web 1](https://raw.githubusercontent.com/RangelMoreira/projeto-sds3/main/assets/paginaInicial.png)

![Web 2](https://raw.githubusercontent.com/RangelMoreira/projeto-sds3/main/assets/dashboard.png)

## Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/RangelMoreira/projeto-sds3/main/assets/sds3-mc.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- Bootstrap
- Apex Charts
- Axios
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/RangelMoreira/projeto-sds3/tree/main/backend

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/RangelMoreira/projeto-sds3/tree/main/frontend

# entrar na pasta do projeto front end
cd frontend

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Kevin Rangel Moreira

https://br.linkedin.com/in/kevin-rangel-moreira-a282b780

