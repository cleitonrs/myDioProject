# Projeto de Simulação QA

Este repositório contém a simulação de um projeto de **Quality Assurance (QA)**, desenvolvido como parte de um desafio de documentação e práticas de testes.

---

## 📌 Entregáveis

A documentação foi estruturada em arquivos PDF:

- **Projeto_QA_Simulacao.pdf** → Documentação completa:
  - Fluxo de trabalho de desenvolvimento
  - Ciclo de vida do bug
  - User Stories com critérios de aceitação
  - Casos de Teste (Step-by-Step)
  - Casos de Teste em BDD (Gherkin)
  - Mind Map (texto descritivo)

- **Projeto_QA_Simulacao_Com_Imagens.pdf** → Versão complementar com diagramas visuais:
  - Fluxo de trabalho do desenvolvimento
  - Ciclo de vida do bug
  - Mind Map do Cadastro de Usuário

---

## 🛠️ Estrutura do Projeto

```
.
├── Projeto_QA_Simulacao.pdf              # Documento textual completo
├── Projeto_QA_Simulacao_Com_Imagens.pdf  # Documento com diagramas
└── README.md                             # Documentação do repositório
```

---

## 📋 User Stories Criadas

### **User Story 1 - Cadastro de Usuário**
- **Como** novo visitante,
- **Quero** criar uma conta no sistema,
- **Para** poder acessar recursos exclusivos.

**Critérios de aceitação:**
- Formulário com campos obrigatórios (nome, e-mail, senha)
- Validação de e-mail no formato correto
- Senha com no mínimo 8 caracteres

---

### **User Story 2 - Login no Sistema**
- **Como** usuário cadastrado,
- **Quero** fazer login com minhas credenciais,
- **Para** acessar minha conta.

**Critérios de aceitação:**
- Campo de e-mail e senha obrigatórios
- Mensagem de erro caso as credenciais sejam inválidas
- Redirecionamento para o painel após login bem-sucedido

---

## ✅ Casos de Teste

### **Step-by-Step**
- **CT-001** → Cadastro com dados válidos
- **CT-002** → Cadastro com e-mail inválido

### **BDD (Gherkin)**
- **CT-003** → Login bem-sucedido
- **CT-004** → Login com senha incorreta

---

## 📊 Diagramas

Os diagramas estão no arquivo `Projeto_QA_Simulacao_Com_Imagens.pdf`:
- Fluxograma do fluxo de trabalho
- Ciclo de vida do bug
- Mind Map do cadastro de usuário

---

## 🚀 Como utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-qa-simulacao.git
   ```

2. Abra os arquivos PDF para consultar a documentação.

3. Utilize como base de estudo ou para estruturar futuros projetos QA.





