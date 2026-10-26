# Escritório Virtual com Agentes de IA

Visual pixel-art de um escritório virtual com agentes de IA animados + integração real com APIs **gratuitas**.

## Funcionalidades

- Mapa interativo do escritório (canvas)
- Agentes com estados que mudam automaticamente (trabalhando, explorando, ocioso, etc.)
- Clique nos agentes para selecionar
- **Atribua tarefas reais** que são processadas por IAs gratuitas:
  - Groq (modelos open, muito rápido)
  - Google Gemini (AI Studio free tier)
  - OpenRouter (modelos `:free`)

## Como usar as APIs gratuitas

1. Crie uma chave gratuita:
   - **Groq**: https://console.groq.com
   - **Gemini**: https://aistudio.google.com/app/apikey
   - **OpenRouter**: https://openrouter.ai/keys
2. No site, selecione o provedor, cole a chave e clique em "Salvar chave".
3. Digite uma tarefa e clique em "Atribuir tarefa ao agente".

> ⚠️ As chaves ficam apenas no `localStorage` do seu navegador.  
> Algumas APIs podem bloquear chamadas diretas do browser (CORS). Para uso real, prefira um backend (ex: Netlify Functions).

## Deploy

Site estático → pode ser publicado em qualquer host (Netlify, GitHub Pages, etc.).

## Créditos

Base visual original + melhorias de integração com IAs gratuitas.
