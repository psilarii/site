# Site da Psicóloga Larissa Lorrayne

Landing page estática (HTML/CSS/JS puro) para a psicóloga Larissa Lorrayne Gomes da Silva. Publicada via GitHub Pages — sem backend, sem build, sem dependências.

## Arquivos

```
index.html   → Estrutura completa da página (todo o conteúdo textual está aqui)
style.css    → Estilos, cores, responsividade e animações
script.js    → Menu mobile, navbar scrolled, animações de entrada
foto.jpeg    → Foto da psicóloga (usada no Hero e Sobre)
```

## Paleta de Cores

| Variável CSS       | Hex       | Uso                        |
|--------------------|-----------|----------------------------|
| `--lilac`          | `#9B72CF` | Botões, destaques          |
| `--lilac-light`    | `#D4BAF0` | Bordas de cards            |
| `--lilac-dark`     | `#6A4A9C` | Hover, textos de destaque  |
| `--lilac-pale`     | `#f0e8ff` | Fundos suaves, badges      |
| `--gold`           | `#C9A84C` | Acentos dourados           |
| `--gold-light`     | `#E8C97A` | Texto dourado claro        |
| `--whatsapp`       | `#25D366` | Botões WhatsApp            |

## Dados de Contato (para atualizar links)

- **WhatsApp:** `5531973090779` — aparece em todos os `href="https://wa.me/..."` do `index.html`
- **Instagram:** `https://instagram.com/psi_larii` — no footer
- **CRP:** 04/81817 — no navbar e footer

## Como editar conteúdo

Todo o texto está diretamente no `index.html`. Procure pelos comentários de seção:
- `<!-- NAVBAR -->` — nome e CRP no topo
- `<!-- HERO -->` — título principal e especialidades
- `<!-- SOBRE -->` — bio da psicóloga
- `<!-- SERVIÇOS -->` — cards de cada especialidade
- `<!-- ABORDAGENS -->` — TCC, ACT, Psicoterapia Breve *(confirmar com Larissa)*
- `<!-- DEPOIMENTOS -->` — substituir pelos depoimentos reais quando disponíveis
- `<!-- CTA WHATSAPP -->` — seção de conversão principal
- `<!-- FOOTER -->` — redes sociais e aviso ético

## Como publicar no GitHub Pages

1. Criar conta no [github.com](https://github.com) se ainda não tiver
2. Criar um repositório público (ex: `site-larissa`)
3. No terminal, dentro da pasta do projeto:
   ```
   git init
   git add .
   git commit -m "initial commit"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/site-larissa.git
   git push -u origin main
   ```
4. No GitHub: **Settings → Pages → Branch: main → Save**
5. Aguardar ~1 minuto → URL: `https://SEU_USUARIO.github.io/site-larissa`

## Como atualizar o site

Editar os arquivos → salvar → rodar no terminal:
```
git add .
git commit -m "atualização"
git push
```
O GitHub Pages publica automaticamente em ~1 minuto.

## Foto

A `foto.jpeg` já está na raiz. Para trocar a foto, substitua o arquivo mantendo o mesmo nome — ou atualize o `src` nas tags `<img src="foto.jpeg">` do `index.html` (aparece duas vezes: Hero e Sobre).
