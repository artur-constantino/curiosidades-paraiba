# Curiosidades da Paraíba 🌅

Site de página única sobre curiosidades da Paraíba, estruturado como um dia paraibano — da madrugada à noite — inspirado no fato de que o estado tem o ponto mais oriental das Américas e é o primeiro lugar do continente a ver o sol nascer todos os dias.

**[Ver demo ao vivo](https://artur-constantino.github.io/curiosidades-paraiba.html/)**

## Sobre

O conteúdo percorre seis curiosidades reais sobre o estado, cada uma ancorada em um período do dia:

- **Madrugada** — Ponta do Seixas, o ponto mais oriental das Américas
- **Manhã** — João Pessoa ("Jampa") e a Mata do Buraquinho
- **Tarde** — Vale dos Dinossauros (Sousa) e a Ilha de Areia Vermelha
- **Entardecer** — o São João de Campina Grande e as garrafas de areia colorida
- **Noite** — literatura de cordel e forró

O visual é inspirado nos folhetos de cordel nordestinos: bordas grossas, tipografia de cartaz e um degradê que acompanha a passagem do sol ao longo da página.

## Tecnologias

- HTML5
- CSS3 (sem frameworks)
- JavaScript puro (vanilla JS)

Nenhuma dependência de build — é um único arquivo HTML autocontido.

## Como rodar localmente

Não é necessário instalar nada. Basta abrir o arquivo direto no navegador:

```bash
git clone https://github.com/artur-constantino/curiosidades-paraiba.html.git
cd curiosidades-paraiba.html
```

Depois é só abrir `index.html` clicando duas vezes nele, ou rodar um servidor local simples:

```bash
python3 -m http.server 8000
```

E acessar `http://localhost:8000` no navegador.

## Estrutura

```
.
├── index.html   # site completo (HTML + CSS + JS embutidos)
└── README.md
```

## Publicar no GitHub Pages

1. Renomeie o arquivo principal para `index.html` (se ainda não estiver assim).
2. Vá em **Settings → Pages** no repositório.
3. Em **Source**, selecione a branch `main` e a pasta `/root`.
4. Salve e aguarde alguns minutos — o site ficará disponível em `https://artur-constantino.github.io/curiosidades-paraiba.html/`.

## Funcionalidades

- Botão **"Curiosidade aleatória"** no topo, com fatos extras sobre o estado
- Botão flutuante de **música de fundo**, com player do YouTube tocando em segundo plano
- Cards que aparecem suavemente ao rolar a página (respeitando `prefers-reduced-motion`)
- Layout responsivo, do celular ao desktop

## Licença

Sinta-se livre para usar, adaptar e compartilhar.
