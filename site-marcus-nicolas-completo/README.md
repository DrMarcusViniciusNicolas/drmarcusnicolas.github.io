# Site profissional — Marcus Vinicius Seco Nicolas

Este pacote está pronto para publicação em GitHub Pages, Netlify ou Vercel.

## Arquivos principais

- `index.html` — estrutura do site
- `styles.css` — aparência
- `config.js` — links e contatos editáveis
- `script.js` — comportamento dos botões
- `assets/marcus-profile.jpg` — foto profissional
- `assets/favicon.svg` — ícone do navegador

## Como adicionar e-mail, WhatsApp e Lattes depois

Abra `config.js` e preencha apenas os campos desejados:

```js
const SITE_CONFIG = {
  region: "São João da Boa Vista e região",
  linkedin: "https://www.linkedin.com/in/drmarcusnicolas/",
  email: "contato@seudominio.com.br",
  whatsapp: "5519999999999",
  lattes: "https://lattes.cnpq.br/..."
};
```

Se um campo ficar vazio, o botão correspondente não aparece no site.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos e a pasta `assets`.
3. Vá a `Settings` → `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha `main` e `/root`.
6. Salve.

## Privacidade

Os PDFs de certificados e o TCC não foram publicados diretamente no site. Isso evita expor CPF, códigos de validação e material clínico de paciente. O site mostra apenas informações profissionais necessárias.

## Atualização futura

Quando houver e-mail profissional, WhatsApp profissional ou Lattes, basta editar `config.js`.
