# Santander Dev Week - 2025
Java RESTfuk API criada para o Santander Dev Week.

## Diagrama de Classes

```mermaid
classDiagram
    class User {
        - String name
        - Account account
        - Feature [] features
        - Card card
        - News [] news
    }

    class Account {
        - String number
        - String agency
        - double balance
        - double limit
    }

    class Feature {
        - String icon
        - String description
    }

    class Card {
        - String number
        - double limit
    }

    class News {
        - String icon
        - String description
    }

    User "1" *-- "1" Account
    User "1" *-- "N" Feature
    User "1" *-- "1" Card
    User "1" *-- "N" News
```

# 💻 **Santander Dev Week**

[DIO](https://www.dio.me/)

**Autrores:**

[Jéssica Fernandes](https://github.com/Jessica-SFernandes)

# 

## Descrição

Projeto reproduzido com o auxilio do professor [Venilton FalvoJr](https://github.com/falvojr), realizado na aula Santander DEV Week.

## Tecnologias Utilizadas

![API](https://img.shields.io/badge/API-%23007396.svg?style=for-the-badge&logo=swagger&logoColor=white) ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Spring](https://img.shields.io/badge/Spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-%230B0D0E.svg?style=for-the-badge&logo=railway&logoColor=white)


