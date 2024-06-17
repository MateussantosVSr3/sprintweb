# Projeto de Scripts em JavaScript

Este repositório contém três arquivos JavaScript distintos, cada um implementando funcionalidades específicas para um site. A seguir, uma descrição detalhada de cada um dos arquivos:

## Arquivo 1: `script_about.js`

Este arquivo contém scripts para o gerenciamento de um formulário de contato e um menu de navegação.

### Funcionalidades

1. **Validação de Formulário de Contato**:
   - Adiciona um ouvinte de evento para o envio do formulário (`submit`).
   - Valida os campos do formulário (`nome`, `email` e `mensagem`).
   - Exibe mensagens de erro caso os campos não sejam preenchidos corretamente.
   - Exibe um alerta de sucesso se o formulário for válido.

2. **Contador de Caracteres para a Mensagem**:
   - Atualiza a contagem de caracteres à medida que o usuário digita na mensagem.
   - Limita a mensagem a 250 caracteres.

3. **Menu de Navegação**:
   - Adiciona um ouvinte de evento para o clique no ícone de menu (hamburger).
   - Alterna a exibição das seções de navegação (`nav-sections`).