# Programa Advogado Aprendiz — Landing Page

Página de vendas do curso prático de Direito Tributário aplicado à execução fiscal,
ministrado pela **Dra. Bianca Cardoso Marques**.

Página estática de arquivo único: [`index.html`](index.html). Sem build, sem dependências
— abra no navegador ou publique em qualquer host estático (GitHub Pages, Netlify, Vercel).

## Identidade visual

Extraída dos materiais de apoio das aulas 01–05:

| Elemento | Valor |
| --- | --- |
| Azul-marinho (primária) | `#172256` |
| Azul profundo (facetas escuras) | `#0b1030` |
| Azul médio / vivo (facetas) | `#2c3a92` · `#3f52c4` |
| Fundo claro | `#eceef2` |
| Vermelho (ênfase técnica / CTA) | `#d21f2b` |
| Tipografia | Montserrat (títulos) + Mulish (texto) + Lora (depoimentos e falas em itálico) |

Motivo gráfico: lascas geométricas diagonais (SVG). Fio condutor estrutural:
`HIT → FG → OT → LÇTO → CT → DA → EF`. Tema claro + escuro, responsivo.

## Pendências antes de publicar

- [x] **Checkout da Kiwify** — todos os CTAs de compra (`header`, herói, card de preço,
      CTA final) apontam para `https://pay.kiwify.com.br/eNDYzcG`.
- [x] **Logo** — `assets/logo-white.png` (arte oficial, versão branca) usada no cabeçalho
      e no rodapé, ambos sobre fundo azul-marinho.
- [x] **Foto da instrutora** — `assets/bianca-marques.jpg` no lugar das iniciais, no bloco
      de credibilidade do herói.
- [ ] **Depoimentos** — os 3 da seção "Prova social" ainda são exemplos da copy. Só
      publicar com autorização expressa e sem mencionar resultado de processo, valor de
      causa ou honorários (publicidade OAB). Trocar por reais ou remover a seção.

## Seção "A professora"

Bloco de autoridade (`#professora`, entre benefícios e prova social): retrato grande da
Dra. Bianca + biografia com duas linhas do tempo — **Formação** e **Trajetória
profissional** — cada item com uma elucidação do que aquela experiência agrega ao curso.

**Sobre logos de terceiros:** os nomes PGFN, EY, EBRADI etc. aparecem em texto (histórico
profissional é informação factual), mas **não** reproduzimos as marcas/brasões desses
órgãos e empresas — colocar o logo da EY ou da PGFN numa página de venda de curso sugere
endosso institucional que não existe (risco de marca; a política da EY veda uso do logo
por terceiros; o brasão da PGFN é símbolo de órgão público). No lugar, cada item usa um
selo tipográfico curto (`.cv-mono`) na identidade do próprio programa.

## Assets

| Arquivo | Uso |
| --- | --- |
| `assets/logo-white.png` | Logo oficial (branca), cabeçalho e rodapé |
| `assets/bianca-marques.jpg` | Retrato quadrado, avatar do bloco de credibilidade do herói |
| `assets/bianca-portrait.jpg` | Retrato vertical grande, seção "A professora" |

## Fonte da copy

`copy-advogado-aprendiz-v2.md` (estrutura PAS: Problema → Agitação → Solução).
