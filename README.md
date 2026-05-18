# Churrascaria Colonial

Site institucional estático para a Churrascaria Colonial, feito apenas com HTML, CSS e JavaScript puro.

## Estrutura

- `index.html`: conteúdo e estrutura semântica do site.
- `css/style.css`: estilos visuais, responsividade e animações.
- `js/script.js`: menu mobile, header ao rolar, animações e destaque do menu.
- `assets/fotos/`: fotos usadas nas seções.
- `assets/logo/`: imagem de logo usada no header.
- `assets/icons/`: favicon.

## Como trocar fotos

Substitua os arquivos dentro de `assets/fotos/` mantendo exatamente estes nomes:

- `hero-churrascaria.jpg`
- `buffet-salao.jpg`
- `buffet-saladas.jpg`
- `pratos-quentes.jpg`
- `prato-cliente.jpg`
- `ambiente-buffet.jpg`
- `salao-eventos.jpg`
- `fachada-churrascaria.jpg`
- `churrasco-banner.jpg`

Para trocar a imagem do logo no header, substitua:

- `assets/logo/churrascaria-colonial-logo.jpg`

Use imagens em `.jpg` otimizadas para web. Fotos maiores que 2500 px de largura podem deixar o site mais pesado.

## Como alterar telefone

Procure no `index.html` por:

```html
tel:4133722101
```

Troque pelo novo número sem espaços, parênteses ou hífens. Também atualize os textos visíveis com o telefone formatado, como:

```html
(41) 3372-2101
```

## Como alterar endereço

Procure no `index.html` por:

```text
R. Virgínia Dalabona, 283 - Orleans, Curitiba - PR
```

Atualize o texto nas seções de localização, contato, footer e no bloco JSON-LD do `<head>`.

Para atualizar o mapa, troque também os links do Google Maps que usam o endereço codificado na seção `#localizacao`.

## Como alterar e-mail

Procure no `index.html` por:

```text
Churrascariacolonia@yahoo.com
```

Atualize o texto visível e o link `mailto:`.

## Como atualizar avaliações

A seção `#avaliacoes` não cria sistema próprio de avaliação. Ela apenas exibe prova social já existente.

Para atualizar:

1. Altere o texto `92%` se a recomendação mudar.
2. Altere o texto `Centenas de avaliações no Google` se o resumo público mudar.
3. Atualize os cards de depoimentos reais na seção `#avaliacoes`.
4. Troque o link do botão `Ver avaliações no Google` pelo link real da ficha do Google Business Profile.

## Como publicar o site

Este site não precisa de backend, banco de dados ou Node.js.

Você pode publicar enviando todos os arquivos e pastas para qualquer hospedagem estática, como:

- Hostinger, Locaweb ou servidor FTP comum
- Netlify
- Vercel
- GitHub Pages

O arquivo inicial deve ser `index.html`, mantendo as pastas `css`, `js` e `assets` no mesmo nível.
