# Grade de Pintura

Aplicativo web simples para pintar uma grade quadriculada e salvar o resultado em PDF.

## Funcionalidades

- Três tamanhos de grade: 33×33, 41×41 e 42×42 (cada tamanho guarda seu próprio desenho)
- Linhas-guia a cada 10 quadrados e no centro
- Réguas numeradas acima e à esquerda, com destaque da linha e coluna sob o mouse
- Paleta com 18 cores e seletor de cor personalizada
- Clique em um quadrado vazio para pintá-lo; clique em um quadrado preenchido para apagá-lo
- Botão "Limpar tudo"
- Exportação para PDF (A4), com opção de incluir ou não as linhas da grade e as réguas
- O desenho fica salvo no navegador (localStorage) entre uma visita e outra

## Como usar

Abra o arquivo `index.html` em qualquer navegador, ou acesse a versão publicada pelo GitHub Pages.

Não precisa instalar nada: tudo roda no navegador. A geração do PDF usa a biblioteca
[jsPDF](https://github.com/parallax/jsPDF), carregada via CDN (é preciso estar conectado à internet).

## Tecnologias

- HTML, CSS e JavaScript puro
- jsPDF 2.5.1
