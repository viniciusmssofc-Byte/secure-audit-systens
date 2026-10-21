# Secure Audit Systens 🔒📊

Este projeto consiste em um **Sistema Automatizado de Auditoria Financeira e Gerenciamento Orçamentário** desenvolvido em Python. Ele foi projetado para ler registros de colaboradores de arquivos externos, validar a integridade dos setores operacionais e aplicar camadas de controle de acesso (autenticação de segurança) antes de permitir modificações na matriz do sistema.

O projeto demonstra a aplicação prática de conceitos de **Engenharia de Software**, **Análise de Dados** e **Secure Coding (Programação Segura)** para resolver problemas reais de conformidade e controle de riscos administrativos.

---

### 🛠️ Funcionalidades Principais
- **Processamento de Dados com Pandas:** Leitura dinâmica e mapeamento automatizado de bases cadastrais em formatos estruturados (`.csv`).
- **Gerenciamento CRUD Orçamentário:** Funções modulares para Criar, Ler, Atualizar e Deletar setores e seus tetos operacionais de forma dinâmica.
- **Camada de Autenticação de Segurança (RBAC):** Proteção de funções críticas do sistema por meio de login e mascaramento seguro de senhas em terminal (`getpass`).
- **Geração de Logs Técnicos:** Exportação automática de relatórios consolidados de conformidade (`relatorio_auditoria.txt`) contendo carimbo de data, hora e operador.

---

### 💻 Tecnologias Utilizadas
- **Linguagem Principal:** Python 3
- **Manipulação de Dados:** Pandas
- **Segurança & Utilitários:** Getpass, OS, Datetime

---

### 🛡️ Foco em Segurança de Aplicações
O sistema simula regras rígidas de segurança corporativa, identificando automaticamente falhas de integridade como:
1. Registros de colaboradores alocados em setores inválidos, inexistentes ou desativados.
2. Bloqueio preventivo de alterações administrativas sem credenciais verificadas de Operador/Administrador.
