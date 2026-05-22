# Site da Psicóloga Larissa Lorrayne

Landing page estática (HTML/CSS/JS puro) publicada via GitHub Pages — sem backend, sem build, sem dependências.

## Arquivos

```
index.html      → Estrutura completa da página (todo o conteúdo textual está aqui)
style.css       → Estilos, cores, responsividade e animações
script.js       → Menu mobile, navbar scrolled, animações de entrada
foto.jpeg       → Foto da psicóloga (usada no Hero e Sobre)
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

## Como editar o conteúdo

Todo o texto está diretamente no `index.html`. Localize a seção pelo comentário:

```
<!-- NAVBAR -->         nome e CRP no topo
<!-- HERO -->           título principal e especialidades
<!-- SOBRE -->          bio da psicóloga
<!-- SERVIÇOS -->       cards de cada especialidade
<!-- ABORDAGENS -->     TCC, ACT, Psicoterapia Breve
<!-- DEPOIMENTOS -->    substituir pelos depoimentos reais
<!-- CTA WHATSAPP -->   seção de conversão principal
<!-- FOOTER -->         redes sociais e aviso ético
```

## Como publicar atualizações

```bash
git add .
git commit -m "descrição da mudança"
git push
```

O GitHub Pages atualiza automaticamente em cerca de 1 minuto.

## Como trocar a foto

Substitua o arquivo `foto.jpeg` na raiz mantendo o mesmo nome — ou atualize o atributo `src` nas duas tags `<img src="foto.jpeg">` do `index.html` (Hero e Sobre).
