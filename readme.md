# Checkpoint 6: Vibecoding

**Portfólio Henri VF · RM569586** — landing page criada com IA

- **GitHub:** https://github.com/HenriVF
- **Repositório:** _(cole o link)_
- **Deploy:** _(cole o link)_

## Como abrir o projeto

```
portfolio/
├── index.html
└── style.css
```

Coloque os dois arquivos na mesma pasta e abra o `index.html` no navegador. Não precisa instalar nada.

## 1. Conceito

Portfólio de um estudante de Front-end, inspirado no site da Apple Brasil: muito espaço em branco, títulos grandes e animações discretas. O conteúdo vem das atividades do ano: Revisão (Figma), Bootstrap, Tailwind e Vibecode.

## 2. Referências

| # | Referência | O que aproveitei | Seção |
|---|---|---|---|
| 1 | apple.com/br | Barra de navegação fixa e translúcida, com blur | Navegação |
| 2 | apple.com/br | Títulos enormes e centralizados, com frases curtas | Hero |
| 3 | apple.com/br | Grade de blocos grandes com cantos arredondados, sobre fundo preto | Projetos |
| 4 | apple.com/br (animação) | Elementos surgem conforme o scroll (fade e subida suave) | Todas as seções |
| 5 | Grão Nobre (Bootstrap, CP5) | Cards com cantos bem arredondados e título forte | Skills |
| 6 | Fio & Prensa (Tailwind, CP5) | Divisores finos e hierarquia editorial | Jornada |
| 7 | Dobra (Vibecode, CP5) | Botão em formato de pílula e rótulo pequeno acima do título | Hero e botões |

> Antes de entregar, abra o site da Apple Brasil e confirme cada comportamento citado.

## 3. Decisões de identidade visual

### Paleta

| Cor | Hex | Papel | Por que combina |
|---|---|---|---|
| Cinza-claro | `#F5F5F7` | Fundo das seções claras | Neutro, deixa o conteúdo respirar, como na Apple |
| Grafite | `#1D1D1F` | Texto principal e cards escuros | Contraste alto sem o peso do preto puro |
| Azul | `#0071E3` | Destaque: botões, links e linha do tempo | Uma única cor de ação guia o olhar |
| Preto | `#000000` | Fundo da seção Projetos | Faz as cores de cada projeto se destacarem |
| Cinza suave | `#6E6E73` | Texto secundário | Cria hierarquia entre título e descrição |

Cada projeto aparece com a paleta própria que ele já tinha (roxo, verde e cereja, verde e dourado, petróleo e laranja). O portfólio fica neutro para valorizar o trabalho.

### Tipografia

Inter, que transmite a sensação limpa e moderna da fonte da Apple (SF Pro). A SF Pro é proprietária e não pode ser carregada em um site comum, por isso a pilha de fontes tenta `-apple-system` antes de cair para a Inter. Títulos em peso 700 com espaçamento levemente negativo; textos em peso 400.

### Tom e personalidade

Moderno, minimalista e direto. Os textos são curtos ("Interfaces que ganham vida."). O layout usa muito espaço vazio e uma cor de destaque só.

### Estrutura da página

1. **Navegação fixa:** acesso rápido a qualquer seção.
2. **Hero:** apresenta quem sou e o foco em Front-end.
3. **Skills:** o que aprendi.
4. **Projetos:** a prova prática das skills.
5. **Jornada do ano:** mostra a evolução entre as etapas.
6. **Contato:** leva ao GitHub.

## 4. Prompts utilizados

### Prompt inicial

> Crie uma landing page de portfólio pessoal em um único arquivo HTML (HTML, CSS e JS puros, sem frameworks), inspirada no site da Apple Brasil. Pessoa: Henri VF, estudante de Front-end. Seções, nesta ordem: navegação fixa translúcida com blur; hero centralizado com o título "Interfaces que ganham vida." e dois botões; Skills em 6 cards (HTML e acessibilidade, CSS moderno, Bootstrap 5, Tailwind CSS, Do Figma ao código, Vibecoding com IA); Projetos em 4 blocos grandes sobre fundo preto (landing de tecnologia do Figma, Grão Nobre, Fio & Prensa, Dobra), cada um com as cores do projeto e tags de tecnologia; Jornada do ano em linha do tempo vertical; Contato com botão para o GitHub; rodapé. Paleta: fundo #F5F5F7, texto #1D1D1F, destaque #0071E3, seção escura #000000, texto suave #6E6E73. Fonte Inter. Os elementos devem surgir conforme o scroll, respeitando prefers-reduced-motion. Responsivo, com quebra em 800px. Acessibilidade: HTML semântico, foco visível e contraste AA. Não use imagens externas.

### Prompts de ajuste

_Cole aqui, na ordem em que enviou, cada prompt de ajuste que você realmente usar. Corrija um problema por vez._

1. _(prompt de ajuste 1)_
2. _(prompt de ajuste 2)_

## 5. Registro de correções

_Uma ficha por rodada. Preencha com o que aconteceu de verdade na conversa com a IA._

### Rodada 1

| Campo | Registro |
|---|---|
| Problema | |
| Prompt de correção | |
| Resultado (resolveu, em parte ou não) | |
| Aprendizado | |

### Rodada 2

| Campo | Registro |
|---|---|
| Problema | |
| Prompt de correção | |
| Resultado (resolveu, em parte ou não) | |
| Aprendizado | |

**Roteiro de QA:** clique em todos os links e botões; teste em celular, tablet e desktop; confira o menu no celular; role a página para ver as animações; ative "reduzir movimento" no sistema; navegue só com o teclado (Tab).

## 6. Resultado final

- **Repositório:** _(cole o link)_
- **Deploy:** _(cole o link)_

### Reflexão

_Escreva com suas palavras: o que ficou como você imaginou? O que ainda mudaria (por exemplo, links de deploy em cada projeto, imagens reais, seção de eventos)?_