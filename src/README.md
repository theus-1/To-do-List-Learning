# 📝 To-Do List CLI (Java)

Um gerenciador de tarefas robusto que roda diretamente no terminal. Este projeto foi desenvolvido para consolidar os fundamentos da linguagem Java, focando em manipulação de coleções e experiência do usuário (UX) via console.

---

## 🚀 Funcionalidades

O programa oferece um fluxo completo de gerenciamento de tarefas com as seguintes opções:

* **[1] Adicionar Tarefa:** Cadastro rápido de novas pendências.
* **[2] Listar Tarefas:** Visualização organizada com índices numéricos.
* **[3] Remover Tarefa:** Exclusão inteligente via **índice** ou **nome da tarefa**.
* **[4] Concluir Tarefa:** Adição visual da tag `[CONCLUÍDA]` via número ou nome.
* **[0] Sair:** Encerramento seguro do programa.

---

## 💡 Diferenciais Técnicos

Para tornar o código mais profissional, implementei:

* **Case-Insensitive:** O sistema utiliza `.equalsIgnoreCase()`, permitindo que o usuário interaja sem se preocupar com letras maiúsculas ou minúsculas.
* **Tratamento de Strings:** Uso de `.trim()` para limpar espaços em branco acidentais e `.contains()` para evitar duplicação de etiquetas de conclusão.
* **Robustez:** Tratamento de erros para entradas inválidas e listas vazias, além de gerenciamento de buffer do `Scanner`.

---

## 🛠️ Tecnologias e Conceitos

* **Linguagem:** Java (JDK 17+)
* **Coleções:** `ArrayList` e `List` para armazenamento dinâmico.
* **Entrada de Dados:** `java.util.Scanner`.
* **Lógica de Controle:** Estruturas de repetição (`while`) e condicionais (`switch/case`, `if/else`).

---

## 📂 Como rodar o projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)