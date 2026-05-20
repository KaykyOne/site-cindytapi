# Guia do Site da Cindy Tapia

Este documento explica de forma simples como funciona o site da cantora e palestrante Cindy Tapia.

## 🎨 Cores e Estilo Principal

O site usa uma paleta de cores elegante e sofisticada:

- **Preto escuro** (#0F0D0B) - fundo principal
- **Dourado** (#D6B17E) - detalhes importantes, títulos e destaques
- **Bege claro** (#FBF7F0) - textos principais
- **Cinza** (#A79E92) - textos secundários

A fonte principal é a **Jost** (moderna) e para títulos especiais usa a **Cormorant Garamond** (clássica e elegante).

## 🧱 Componentes do Site

### Navegação (Menu)
- Fica fixo no topo da página
- Quando você rola a página, ele fica com fundo escuro (efeito "vidro fosco")
- No celular, se transforma em um menu "hambúrguer" (três linhas)

### Seção Hero (Início)
- É a primeira coisa que você vê ao entrar
- Tem uma imagem de fundo que dá um zoom suave (efeito cinematográfico)
- Mostra o logo, um botão para ouvir músicas e links para redes sociais

### Seção Sobre
- Foto da Cindy Tapia com moldura decorativa
- Lista de funções: cantora, palestrante, capelã, atriz, empresária
- Texto contando um pouco da história dela

### Seção Ministérios
- Mostra os 4 principais trabalhos:
  1. Adoradora & Cantora
  2. Palestrante
  3. Capelã
  4. Atriz

### Seção Trajetória (Músicas)
- Mostra cards com músicas do Spotify
- Cada card tem um player para ouvir a música
- São 5 músicas no total

### Seção Vídeo
- Vídeo contando a história da Cindy
- Layout lado a lado: texto explicativo à esquerda, vídeo à direita
- No celular, o vídeo fica embaixo do texto

### Depoimentos
- 3 cards com comentários de pessoas
- Cada card tem aspas, o texto e o nome da pessoa

### Contato
- Botão para falar no WhatsApp
- Links para Instagram, Facebook e WhatsApp

### Rodapé (Footer)
- Logo da Cindy
- Informação de direitos autorais
- Créditos da empresa que fez o site

## 📱 Responsividade (Funciona em qualquer tela)

O site se adapta para celulares e tablets:

| Tamanho de tela | Mudanças |
|----------------|----------|
| **Tablet (menos de 900px)** | Conteúdo em coluna, margens menores |
| **Celular (menos de 768px)** | Menu vira hambúrguer, botões ocupam largura toda, fonte menor |
| **Celular pequeno (menos de 380px)** | Fonte ainda menor, espaços reduzidos |

## 🎯 Detalhes Técnicos Importantes

### Scrollbar (barra de rolagem)
- Tem cor escura combinando com o tema
- A parte que você arrasta é dourada

### Animações
- O menu muda de cor ao rolar a página
- As imagens têm efeitos suaves ao passar o mouse
- O texto da seção inicial aparece com animação de "subida"

### Cards de Música
- Cada música tem um card com borda dourada
- Quando passa o mouse, o card "levanta" e ganha um brilho
- No celular, os cards ficam menores

### Vídeo
- Proporção 9:16 (parecido com vídeo de TikTok/Instagram)
- Tem moldura decorativa ao redor

## 📂 Organização do CSS

O código CSS está organizado por seções:

1. **Reset e variáveis** - configurações globais e cores
2. **Elementos base** - body, imagens, scrollbar
3. **Componentes reutilizáveis** - botões, títulos, divisórias
4. **Seção por seção** - hero, sobre, ministérios, etc.
5. **Responsividade** - ajustes para cada tamanho de tela

## 🔧 Funcionalidades JavaScript

```javascript
// Menu que muda ao rolar
quando rolar mais de 60px → menu fica escuro

// Menu mobile
botão hambúrguer → abre menu
clicar no X ou em um link → fecha menu
aberto → impede rolagem da página