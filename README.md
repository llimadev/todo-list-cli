# 📝 To Do List CLI em Java

Um projeto básico de **To Do List** (lista de tarefas) desenvolvido em **Java**, rodando no terminal (CLI).  
O objetivo é praticar conceitos de programação orientada a objetos, manipulação de listas e interação com o usuário via linha de comando.

---

## 🚀 Funcionalidades
- Adicionar novas tarefas
- Listar todas as tarefas
- Marcar tarefas como concluídas
- Remover tarefas
- Sair do programa

---

## 🛠️ Tecnologias utilizadas
- **Java 17+** (compatível com versões mais recentes)
- **Maven** para gerenciamento de dependências e build
- **IntelliJ IDEA** como IDE

---

## 📂 Estrutura do projeto
```
todo-list-cli/
├── src/
│   └── main/
│       └── java/
│           └── org/example/
│               └── Main.java
├── pom.xml
└── README.md
```
---

## ▶️ Como executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/llimadev/todo-list-cli.git
   cd todo-list-cli
   
   mvn clean install
   mvn exec:java -Dexec.mainClass="org.example.Main"
    ```
---
## 📌 Próximos passos

- Implementar persistência (salvar tarefas em arquivo ou banco de dados)
- Criar testes automatizados com JUnit
- Melhorar interface de linha de comando
---
## Licença
Este projeto está sob a licença MIT.<br>
Sinta-se livre para usar, modificar e compartilhar.