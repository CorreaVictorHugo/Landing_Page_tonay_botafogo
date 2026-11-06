# Tonay Park — Landing Page

Landing page responsiva para apresentar um estacionamento em Botafogo, Rio de Janeiro. O visual combina tons escuros e dourados, tipografia Raleway e navegação simples para levar o visitante ao contato pelo WhatsApp.

**[Ver o site publicado](https://tonay-park-botafogo.netlify.app/)**

![Prévia da landing page Tonay Park](docs/preview.png)

## Funcionalidades

- Informações sobre funcionamento 24 horas, área coberta, segurança eletrônica e vagas para mensalistas.
- Links de WhatsApp com mensagens diferentes para contato geral e consulta de vaga mensal.
- Botão flutuante de WhatsApp, menu para celular e seção de dúvidas frequentes.
- Animação discreta ao rolar a página, respeitando a preferência por movimento reduzido.
- Layout responsivo feito com HTML, CSS e JavaScript, sem dependências de framework.
- Favicon próprio com o símbolo do carro.
- Foto real da entrada pela Rua Sorocaba, 305, junto às informações de localização.

## Rodar localmente

Abra `index.html` no navegador. Os arquivos de fonte estão em `assets/fonts/` e a licença da fonte está em `assets/fonts/OFL.txt`.

## Configuração

O número do WhatsApp da Tonay Park está configurado no início de `script.js`:

```js
const whatsappNumber = '5521999470811';
const whatsappDisplay = '(21) 99947-0811';
```

Em `whatsappNumber`, use código do país, DDD e número, sem espaços ou símbolos. Se o número mudar novamente, atualize também os links de reserva em `index.html`.

## SEO local

A página inclui título e descrição para buscas locais, URL canônica, dados estruturados `LocalBusiness`, `robots.txt` e `sitemap.xml`. Ao trocar o domínio, atualize as URLs absolutas em `index.html`, `robots.txt` e `sitemap.xml`.

Para acompanhar a indexação, cadastre o site no Google Search Console e envie o sitemap. Para aparecer nas buscas e no Google Maps, o responsável pelo estacionamento deve criar e verificar o Perfil da Empresa no Google com nome, endereço, telefone e horários consistentes com o site.

## Publicação

O site está hospedado no Netlify. A pasta `dist/` é gerada localmente com `index.html`, `styles.css`, `script.js`, `robots.txt`, `sitemap.xml`, `_headers`, `favicon.ico` e `assets/`, e não faz parte do repositório. Após alterações, atualize esses arquivos em `dist/` e execute `netlify deploy --prod --dir=dist`. O arquivo `_headers` deve estar na raiz de `dist/` para que a Netlify aplique os cabeçalhos de segurança.

A fotografia principal de abertura é ilustrativa. A foto na seção de contato mostra a entrada real pela Rua Sorocaba.
