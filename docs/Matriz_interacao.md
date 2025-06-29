
## 📊 Matriz de Interação entre Requisitos (Histórias de Usuário)

|       | EU01 | EU02 | EU03 | EU04 | NU01 | NU02 | NU03 | AD01 | AD02 | AD03 |
|-------|------|------|------|------|------|------|------|------|------|------|
| EU01  | 0    | 1000 | 1000 | 1000 | 1000 | 1000 | 0    | 0    | 0    | 0    |
| EU02  | 1000 | 0    | 1000 | 1000 | 1000 | 1000 | 0    | 0    | 0    | 0    |
| EU03  | 1000 | 1000 | 0    | 0    | 1000 | 1000 | 0    | 0    | 0    | 0    |
| EU04  | 1000 | 1000 | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    |
| NU01  | 1000 | 1000 | 1000 | 0    | 0    | 1000 | 1000 | 0    | 0    | 0    |
| NU02  | 1000 | 1000 | 1000 | 0    | 1000 | 0    | 1000 | 0    | 0    | 0    |
| NU03  | 0    | 0    | 0    | 0    | 1000 | 1000 | 0    | 0    | 0    | 0    |
| AD01  | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1000 | 1000 |
| AD02  | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1000 | 0    | 1000 |
| AD03  | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1000 | 1000 | 0    |

- **0:** independente | **1000:** sobreposição/interação forte | **1:** conflito direto (não aplicado)

---

---

## 📌 Explicação das Interações Identificadas na Matriz

### 🔹 **EU01 (Visualização do cardápio atual)**  
Está fortemente ligada (sobreposição - valor **1000**) às histórias:
- **EU02 (Visualização do cardápio seguinte):** ambas dependem diretamente da funcionalidade de visualização do cardápio.
- **EU03 (Informações nutricionais/alérgenos):** ao visualizar o cardápio, o estudante acessa diretamente essas informações.
- **EU04 (Avisos importantes):** a visualização do cardápio pode incluir informações e avisos importantes sobre refeições.
- **NU01 e NU02 (Cadastro e informações nutricionais feitas pelo nutricionista):** o conteúdo visualizado pelos estudantes depende diretamente da ação dos nutricionistas.

### 🔹 **NU01 (Cadastro e edição de pratos)**  
Sobrepõe-se diretamente às histórias:
- **NU02 (Inserir informações nutricionais):** ao cadastrar pratos, é essencial incluir suas informações nutricionais.
- **NU03 (Interface organizada para nutricionista):** uma interface bem organizada facilita diretamente o processo de cadastrar e editar pratos.

### 🔹 **AD01 (Gerenciamento de usuários)**  
Relaciona-se diretamente às histórias:
- **AD02 (Definir permissões):** para gerenciar usuários é necessário definir e atribuir permissões.
- **AD03 (Visualizar relatórios de uso):** relatórios frequentemente dependem diretamente dos dados relacionados ao gerenciamento de usuários e permissões.

---  
