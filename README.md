# 📋 Formulário de Solicitação de Acessos - TI

Sistema web para solicitação padronizada de acessos aos sistemas de TI da 

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Ativo-success)](https://github.com)

---

## 🎯 Objetivo

Facilitar e padronizar o processo de solicitação de acessos aos sistemas de TI, seguindo o **POP TI 001 - Política Geral de Gestão de Acessos a Sistemas de TI**.

---

## 🚀 Acesso Rápido

### 🌐 URL de Produção
```
https://SEUUSUARIO.github.io/formulario-acessos-ti/
```

> ⚠️ **Substitua `SEUUSUARIO`** pelo seu nome de usuário do GitHub após o deploy

---

## 📦 Sistemas Suportados

O formulário permite solicitar acessos para:

### 1. 🏥 **Sistema Tasy**
- 67 perfis organizados em 6 categorias
- Gestão e Cadastros
- Operação Administrativa
- Assistencial/Clínica
- Apoio Operacional
- Supervisão e Coordenação
- Perfis Excepcionais

### 2. 📧 **Microsoft 365**
- Business Basic (R$ 33,40/mês)
- Business Standard (R$ 83,50/mês)
- Exchange Online P2 (adicional R$ 53,40/mês)

### 3. 📊 **BI Weknow**
- 4 perfis de sistema (Visualizador, Contato, Administrador, Desenvolvedor)
- 13 grupos de acesso organizados por setor
- 142 dashboards disponíveis

### 4. 💻 **Hardware**
- Computadores (Desktop/Notebook)
- Periféricos (Impressora, Scanner, Monitor, etc.)

---

## ✨ Funcionalidades

### ✅ Interface Intuitiva
- Design moderno e responsivo
- Funciona em desktop, tablet e celular
- Validação automática de campos obrigatórios

### ✅ Seleção Inteligente
- **Accordion para Perfis Tasy**: Expanda/recolha categorias
- **Campo de busca**: Filtre perfis por nome
- **Checkboxes múltiplos**: Selecione vários perfis/grupos facilmente
- **Badges visuais**: Identifique perfis que precisam aprovação especial

### ✅ Geração de Email Automática
- Gera email formatado profissionalmente
- Preenche automaticamente:
  - Para: `ti@ti.com.br`
  - CC: Email do aprovador selecionado
  - Assunto: Gerado com nome e tipo de solicitação
  - Corpo: Formatado em texto ASCII estruturado

### ✅ Copiar e Enviar
- Botões de copiar para cada campo
- Instrução passo a passo no modal
- Feedback visual ao copiar

---

## 🏗️ Estrutura do Projeto

```
formulario-acessos-ti/
│
├── index.html          # Formulário principal (arquivo único)
├── README.md           # Este arquivo
└── docs/              # Documentação adicional (opcional)
    ├── GUIA_USUARIO.md
    └── prints/
```

---

## 📖 Como Usar

### Para **Coordenadores/Solicitantes**:

1. **Acesse o formulário** através da URL do GitHub Pages
2. **Preencha os dados**:
   - Dados do solicitante (seu nome, setor, estabelecimento)
   - Dados do colaborador (nome, CPF, função)
   - Tipo de solicitação (Nova Admissão ou Alteração)
   - Sistemas necessários (marque e selecione perfis/grupos)
   - Justificativa detalhada
   - Gerente aprovador responsável

3. **Clique em "📧 Gerar Email para Envio"**

4. **Copie os campos** usando os botões 📋:
   - Para
   - CC (Cópia para aprovador)
   - Assunto
   - Corpo do email

5. **Abra seu Outlook/Gmail** e cole os dados

6. **Envie o email**

7. **Aguarde aprovação**: O gerente (em cópia) responderá confirmando

8. **TI implementa** os acessos após aprovação

---

## 👥 Responsáveis

### 📧 Destinatários dos Emails

| Destinatário | Email | Função |
|--------------|-------|--------|
| **TI** | ti@ticom.br | Implementa os acessos |
| **Aprovadores** | *[conforme gerente selecionado]* | Aprovam as solicitações |

### Aprovadores por Estabelecimento:

| Estabelecimento | Gerente | Email |
|-----------------|---------|-------|
| ESTAB | GETEN | GERENTE@GERENTE.com.br |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Estilização moderna com gradientes e animações
- **JavaScript Vanilla** - Funcionalidades (sem dependências externas)
- **GitHub Pages** - Hospedagem gratuita

### 📦 Sem Dependências Externas
- ✅ Não precisa de jQuery
- ✅ Não precisa de Bootstrap
- ✅ Não precisa de Node.js
- ✅ 100% standalone - um único arquivo HTML

---

## 📋 Requisitos

### Para Usar o Formulário:
- ✅ Navegador moderno (Chrome, Firefox, Edge, Safari)
- ✅ JavaScript habilitado
- ✅ Acesso à internet

### Para Deploy no GitHub:
- ✅ Conta no GitHub (gratuita)
- ✅ Repositório público

---

## 🚀 Deploy no GitHub Pages

### Passo 1: Criar Repositório

1. Acesse [github.com](https://github.com)
2. Clique em **"New repository"** (botão verde)
3. Preencha:
   ```
   Nome: formulario-acessos-ti
   Descrição: Formulário de Solicitação de Acessos - Grupo CSB
   ☑️ Public
   ☑️ Add a README file
   ```
4. Clique em **"Create repository"**

### Passo 2: Upload do Arquivo

1. No seu novo repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste o arquivo `index.html` para a área de upload
3. Em "Commit changes":
   ```
   Título: Adicionar formulário de solicitação de acessos
   Descrição: Versão 1.0 - Formulário completo com 4 sistemas
   ```
4. Clique em **"Commit changes"**

### Passo 3: Ativar GitHub Pages

1. Vá em **"Settings"** (Configurações) do repositório
2. No menu lateral, clique em **"Pages"**
3. Configure:
   ```
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   ```
4. Clique em **"Save"**

### Passo 4: Aguardar Deploy

⏱️ Aguarde 2-5 minutos

Você verá uma mensagem:
```
✅ Your site is live at https://SEUUSUARIO.github.io/formulario-acessos-ti/
```

### Passo 5: Testar

Acesse a URL e teste o formulário!

---

## 🔄 Como Atualizar

### Quando precisar fazer alterações:

1. No GitHub, clique no arquivo `index.html`
2. Clique no ícone de **lápis** (Edit)
3. Faça suas alterações
4. No final da página:
   ```
   Commit message: Descreva o que mudou
   ```
5. Clique em **"Commit changes"**

⏱️ A atualização estará online em 1-2 minutos

---

## 📱 Compatibilidade

### Navegadores Suportados:
- ✅ Google Chrome 90+
- ✅ Mozilla Firefox 88+
- ✅ Microsoft Edge 90+
- ✅ Safari 14+
- ✅ Opera 76+

### Dispositivos:
- ✅ Desktop (Windows, macOS, Linux)
- ✅ Tablet (iPad, Android)
- ✅ Mobile (iOS, Android)

---

## 📊 Estatísticas do Sistema

- **Perfis Tasy**: 67 perfis organizados
- **Licenças M365**: 3 opções
- **Perfis BI**: 4 perfis de sistema
- **Grupos BI**: 13 grupos de acesso
- **Dashboards BI**: 142 dashboards mapeados
- **Equipamentos**: 6 tipos de hardware

---

## 🔒 Segurança

### ✅ Dados Locais
- Nenhum dado é enviado para servidores externos
- Formulário processa tudo localmente no navegador
- Geração de email acontece no lado do cliente

### ✅ Sem Backend
- Não há banco de dados
- Não há armazenamento de informações
- LGPD friendly

### ✅ HTTPS
- GitHub Pages fornece HTTPS automático
- Conexão segura garantida

---

## 📞 Suporte

### 🐛 Encontrou um Bug?
Abra uma [Issue](https://github.com/SEUUSUARIO/formulario-acessos-ti/issues) descrevendo:
- O que aconteceu
- O que deveria acontecer
- Navegador e versão
- Prints (se possível)

### 💡 Tem uma Sugestão?
Abra uma [Issue](https://github.com/SEUUSUARIO/formulario-acessos-ti/issues) com a tag `enhancement`

### 📧 Contato TI
Para dúvidas sobre acessos: **ti@ticom.br**..

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🏥 Sobre o Grupo CSB

**Clínica Senhor do Bonfim** - Grupo especializado em nefrologia e diálise, com unidades em:
- Matriz (Feira de Santana)
- Convênios
- Rio Vermelho
- Monte Serrat
- Santo Estevão
- Gratidão

---

## 📚 Documentos Relacionados

- [POP TI 001 - Política Geral de Gestão de Acessos](docs/POP_TI_001.md)
- [DOC TI 002 - Guia de Perfis Tasy](docs/DOC_TI_002.md)
- [DOC TI 003 - Guia Microsoft 365](docs/DOC_TI_003.md)
- [DOC TI 004 - Guia BI Weknow](docs/DOC_TI_004.md)
- [DOC TI 005 - Guia Hardware](docs/DOC_TI_005.md)

---

## 🎨 Créditos

**Desenvolvido por**: Equipe de TI - Grupo CSB  
**Data**: Novembro 2024  
**Versão**: 1.0  

---

## 📝 Changelog

### v1.0 (2024-11-24)
- ✨ Lançamento inicial
- ✅ Formulário completo com 4 sistemas
- ✅ Geração automática de email
- ✅ 67 perfis Tasy organizados
- ✅ Interface responsiva e moderna
- ✅ Campo de busca para perfis
- ✅ Accordion para categorias
- ✅ Instruções de envio incluídas

---

## 🚀 Roadmap Futuro

- [ ] Versão em PDF para impressão
- [ ] Histórico de solicitações (se implementar backend)
- [ ] Integração com sistema de tickets
- [ ] Dashboard de aprovações pendentes
- [ ] Notificações automáticas por email
- [ ] Assinatura digital

---

<div align="center">

**⭐ Se este projeto foi útil, considere dar uma estrela no GitHub! ⭐**

Feito com ❤️ pela equipe de TI 

</div>
