# ADL Gestão Contábil

Site institucional de um escritório de contabilidade, feito em HTML, CSS e JavaScript puro, sem frameworks e sem etapa de build.

**Ao vivo:** [adlgestaocontabil.com.br](https://adlgestaocontabil.com.br/)

## O que o site tem

- **Página de apresentação** com proposta de valor, serviços e diferenciais do escritório.
- **Seção de serviços** com ícones próprios (abertura de empresas, planejamento tributário, folha de pagamento, IR, consultoria de gestão e outros), com versões para tema claro e escuro.
- **Formulário de agendamento de reunião** com validação dos campos (nome, empresa, assunto, dia e horário) antes de encaminhar ao WhatsApp do escritório.
- **Formulário de dúvidas** que também encaminha ao WhatsApp.
- **Botões de contato direto** (WhatsApp com mensagem pré-preenchida, e-mail e redes sociais).
- **Layout responsivo**, com menu adaptado para celular.
- **SEO básico**: meta description, Open Graph, URLs canônicas absolutas e dados estruturados (schema.org).

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis, layout responsivo)
- JavaScript puro (validação de formulários, menu mobile)
- Google Fonts (Montserrat e Playfair Display)
- Hospedagem no GitHub Pages, com domínio personalizado

## Estrutura

```
index.html   página única do site
assets/      logos, ícones, fotos e favicons
CNAME        domínio personalizado do GitHub Pages
```

## Como rodar localmente

Não precisa instalar nada. Basta abrir o `index.html` no navegador, ou servir a pasta com qualquer servidor estático:

```bash
npx serve .
```

## Publicação

O site é publicado automaticamente pelo GitHub Pages a partir da branch `main`. O arquivo `CNAME` define o domínio personalizado, e o `.nojekyll` desativa o processamento do Jekyll.
