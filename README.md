# 🐾 Petshop Bichin

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Java](https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/build-Maven-C71A36?logo=apachemaven&logoColor=white)
![Licença](https://img.shields.io/badge/licença-MIT-green)

> Projeto acadêmico da disciplina de **Programação Orientada a Objetos** do IFMG - Campus Formiga. Sistema de console em Java para gerenciar clientes, pets e serviços de um petshop.

---

## 📖 Sobre o projeto

O sistema é organizado em camadas: **model → repository → controller → visão (console)**. Os dados são carregados e salvos em arquivos de texto na pasta `dados/`.

## 🚀 Funcionalidades

- **Clientes e Pets:** cadastrar, listar, buscar, alterar e apagar
- **Serviços:** listar, buscar, alterar e apagar os serviços oferecidos
- **Serviços prestados (atendimentos):**
  - Registrar atendimento
  - Atendimentos por período
  - Atendimentos de um cliente
  - Animais atendidos pelo nome do dono
  - Maior valor pago por um cliente
- **Persistência** em arquivos `.txt`

## 💻 Como executar

Pré-requisitos: **JDK 17+** e **Maven**.

```bash
git clone https://github.com/reireymond/IFMG-PetshopBichin.git
cd IFMG-PetshopBichin
mvn compile
mvn exec:java -Dexec.mainClass="br.edu.ifmg.poo04.Main"
```

Ou abra o projeto na sua IDE (IntelliJ, Eclipse, NetBeans) e rode a classe `Main`.

## 📂 Estrutura

```
src/main/java/br/edu/ifmg/poo04/
├── model/        Cliente, Pet, Servico, ServicoPrestado
├── repository/   leitura e gravação dos dados
├── controller/   regras de negócio
└── visao/cmd/    menus de console
dados/            arquivos .txt com os dados
docs/             enunciado do trabalho
```

## 👨‍💻 Autor

[Kaua Teixeira Nascimento](https://github.com/reireymond)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [`LICENSE`](LICENSE).
