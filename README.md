# JS Instalações Ltda - site institucional

Site one-page da **JS Instalações Ltda**, construção, reformas e instalações elétricas e hidráulicas em Manaus - AM.

## Estrutura

```
index.html   # página única (hero, sobre, serviços, depoimentos, mapa, FAQ)
styles.css   # estilos (tema claro/escuro automático, azul da marca)
script.js    # link do WhatsApp, menu mobile, header, animações, carrossel, FAQ
assets/      # favicon e fotos
```

Sem build: HTML, CSS e JS puros. Publique a pasta em GitHub Pages, Netlify, Vercel ou hospedagem comum.

## Dados usados (perfil do WhatsApp Business)

- Telefone/WhatsApp: +55 92 9284-4321 (`wa.me/559292844321`, constante `WHATSAPP` no `script.js`)
- Horário: 07:00 às 17:00
- Empresa cadastrada desde maio de 2023
- Facebook: Js Instalações Ltda

## Antes de publicar

- **Serviços**: foram deduzidos do nome e do slogan ("Construções com qualidade e confiança"). Confirme construção, reformas, elétrica e hidráulica e ajuste se preciso.
- **Depoimentos** são exemplos. Substitua por avaliações reais de clientes.
- **Mapa**: mostra Manaus. Se houver endereço fixo, troque `Manaus,+AM` no `src` do iframe.
- **Facebook**: o link abre uma busca pelo nome. Troque pela URL exata da página.
- **FAQ**: confirme nota fiscal, formas de pagamento e se o orçamento é gratuito.
- **Logo**: o cabeçalho usa um selo "JS" em texto. Para usar o logo oficial, salve em `assets/` e troque o bloco `.brand`.

## Créditos das imagens

Fotos via [Unsplash](https://unsplash.com) (licença Unsplash).
