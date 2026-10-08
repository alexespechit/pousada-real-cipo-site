# Site — Pousada Real Cipó

Site institucional responsivo para uma pousada, com foco em apresentar as acomodações e levar o visitante direto à reserva pelo WhatsApp.

> 🔒 **Código-fonte privado.** Este repositório é uma vitrine do projeto (descrição, tecnologias e decisões). Se quiser saber mais, é só entrar em contato.

🌐 **Site no ar:** [pousadarealcipo.com.br](https://pousadarealcipo.com.br)

🎟️ **Sistema de ingressos:** [ingressos.pousadarealcipo.com.br](https://ingressos.pousadarealcipo.com.br)

## O que o projeto entrega

- Site responsivo, pensado primeiro para celular
- Galeria e apresentação das acomodações e da estrutura (piscina, suítes, varanda)
- Botão de reserva que abre o WhatsApp da pousada com uma mensagem inicial já preenchida
- Animações suaves de entrada e navegação
- Fotos otimizadas por script, para carregar rápido
- Publicado como site estático em hospedagem compartilhada

## Destaques técnicos

- **Next.js 15 + React 19 + TypeScript**, exportado como site estático
- **Tailwind CSS** com direção visual documentada em uma especificação de design (componentes, tipografia e regras responsivas)
- **Framer Motion** para animações
- **Pipeline de imagens**: script que gera versões otimizadas a partir do acervo original
- **Qualidade**: checagem de tipos e lint antes de cada build
- **Sistema de ingressos** para eventos da pousada, como o Réveillon Real Cipó (checkout com Mercado Pago e dados no Supabase), mantido como aplicação separada e já em uso real

## Tecnologias

`Next.js` · `React` · `TypeScript` · `Tailwind CSS` · `Framer Motion` · `Supabase` · `Mercado Pago`

---

Feito por [Alexsander Espechit](https://github.com/alexespechit) · [LinkedIn](https://www.linkedin.com/in/alexsanderespechit/)
