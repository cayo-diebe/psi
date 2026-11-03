# Guia Rápido: Como Substituir as Imagens "Fake" pelas Fotos Reais da Paula Brisola

Todas as imagens do site estão organizadas na pasta [`assets/images/`](assets/images/).
Atualmente, cada imagem é um arquivo placeholder editorial criado especificamente para manter o site bonito e indicar onde cada foto entra.

## Lista de Arquivos de Imagem para Substituir

| Onde aparece no site | Arquivo Atual ("Fake") | Dimensão Recomendada | O que colocar na foto real |
| :--- | :--- | :--- | :--- |
| **1. Topo do Site (Hero)** | `assets/images/paula-hero.svg` | **800 × 1000 px** (Vertical 4:5) | Retrato principal da Paula Brisola, iluminação suave/natural, olhar acolhedor. |
| **2. Seção Sobre Mim** | `assets/images/paula-sobre.svg` | **800 × 960 px** (Vertical) | Foto da Paula sentada no consultório, com bloco de notas ou postura de escuta. |
| **3. Seção Terapia Online** | `assets/images/terapia-online.svg` | **960 × 720 px** (Horizontal 4:3) | Paula atendendo no notebook, ou detalhe elegante de mesa com computador e xícara de chá/café. |
| **4. Seção Como Funciona / Espaço** | `assets/images/consultorio-ambiente.svg` | **900 × 640 px** (Horizontal) | Foto da poltrona do consultório, iluminação aconchegante, planta ou detalhe da sala. |
| **5. Vitrine Instagram #1** | `assets/images/insta-post-1.svg` | **600 × 600 px** (Quadrado 1:1) | Print/capa de post real do `@psipaulabrisola` ou foto quadrada. |
| **6. Vitrine Instagram #2** | `assets/images/insta-post-2.svg` | **600 × 600 px** (Quadrado 1:1) | Print/capa de post real do `@psipaulabrisola` ou foto quadrada. |
| **7. Vitrine Instagram #3** | `assets/images/insta-post-3.svg` | **600 × 600 px** (Quadrado 1:1) | Print/capa de post real do `@psipaulabrisola` ou foto quadrada. |
| **8. Vitrine Instagram #4** | `assets/images/insta-post-4.svg` | **600 × 600 px** (Quadrado 1:1) | Print/capa de post real do `@psipaulabrisola` ou foto quadrada. |
| **9. Capa de Compartilhamento (WhatsApp)** | `assets/images/og-compartilhamento.svg` | **1200 × 630 px** (Horizontal) | Imagem que aparece quando alguém envia o link do site no WhatsApp. |
| **10. Logotipo & Ícone** | `assets/images/logo-paula-brisola.svg` e `favicon.svg` | Vetorial (`.svg` ou `.png`) | Logotipo oficial da Paula Brisola. |

## Como trocar na prática?
1. Coloque suas fotos reais (em formato `.jpg`, `.png` ou `.webp`) dentro da pasta `assets/images/`.
2. No arquivo `index.html`, basta trocar a extensão `.svg` para `.jpg` (ou `.png` / `.webp`) nos trechos marcados com o comentário `<!-- IMAGEM FAKE #... -->`.
