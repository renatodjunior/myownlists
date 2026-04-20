# MyOwnLists

**[🌐 myownlists.app](https://myownlists.app)** — App de listas pessoais que roda direto no navegador, sem cadastro e sem servidor.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 📋 Múltiplas listas | Crie listas com nome e emoji personalizado |
| 📂 Categorias | Agrupe itens por seção (ex: Frutas, Laticínios) |
| ✅ 3 estados por item | Pendente → Comprado ✅ → Talvez 🤔 |
| ↕️ Arrastar e soltar | Reordene itens e categorias livremente |
| 📊 Progresso | Barra de progresso por lista |
| 📋 Copiar lista | Exporte a lista como texto (WhatsApp, etc.) |
| 🌙 Modo escuro | Tema claro e escuro com um clique |
| 🌐 6 idiomas | PT, EN, ES, 日本語, עברית, 한국어 |
| 📱 PWA | Instale como app nativo no celular |
| ❓ Ajuda | Botão **?** com guia rápido de funcionalidades |

---

## 🖼️ Capturas de tela

### Tela inicial — suas listas

> Lista de compras com emoji, contador de itens e botões de backup.

![Tela inicial](https://myownlists.app/icon-192.png)

### Dentro de uma lista — itens por categoria

> Itens organizados por categoria com barra de progresso, arrastar para reordenar e 3 estados de marcação.

---

## 💾 Armazenamento no navegador

Todos os dados são salvos no **localStorage** do seu navegador — nenhuma conta, servidor ou internet necessários após o primeiro carregamento.

> Isso significa que os dados ficam **apenas no seu dispositivo e navegador atual**.  
> Trocar de navegador, usar aba anônima ou limpar os dados do site apagará suas listas.

---

## ⚠️ Faça backup regularmente

> **Antes de limpar o cache, os dados do site ou desinstalar o app, exporte seu backup!**

Na tela inicial você encontra dois botões:

- **⬆️ Exportar backup** — salva todas as suas listas em um arquivo `.json` no dispositivo
- **⬇️ Importar backup** — restaura as listas a partir de um arquivo exportado anteriormente

O arquivo de backup pode ser guardado em qualquer lugar (nuvem, e-mail, pasta local) e importado a qualquer momento.

---

## 🌐 Idiomas suportados

| Idioma | Flag | Código |
|---|---|---|
| Português (BR) | 🇧🇷 | `pt` |
| English | 🇺🇸 | `en` |
| Español | 🇪🇸 | `es` |
| 日本語 | 🇯🇵 | `ja` |
| עברית | 🇮🇱 | `he` |
| 한국어 | 🇰🇷 | `ko` |

---

## 🔧 Como usar

1. Acesse **[myownlists.app](https://myownlists.app)**
2. Escolha seu idioma e tema
3. Crie uma lista com nome e emoji
4. Abra a lista e adicione itens (com ou sem categoria)
5. Marque os itens conforme vai comprando
6. Use **?** para ver o guia de funcionalidades
7. Exporte o backup regularmente para não perder seus dados

---

## 📦 Tecnologia

Aplicação 100% frontend — HTML, CSS e JavaScript puro, sem frameworks ou dependências de backend.  
Funciona offline após o primeiro acesso (Service Worker + PWA).

---

## 👤 Autor

Feito por **[@renatodjunior](https://github.com/renatodjunior)**

---

*MyOwnLists — suas listas, no seu navegador.*
