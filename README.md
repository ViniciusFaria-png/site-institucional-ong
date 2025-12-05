# Briefing de Projeto Web

**Projeto:** Site Institucional - ONG Anjos de Patas  
**Cliente:** Anjos de Patas da Região Oeste  
**Desenvolvedores:** Pedro Henrique, Matheus, Vinícius Faria

---

## 1. Visão Geral e Contexto
O projeto consiste no desenvolvimento de um site institucional responsivo para a ONG "Anjos de Patas", atuante na região de Araçariguama a Sorocaba. A organização atua desde 2010 no resgate, cuidado e recolocação de animais em situação de risco. O site serve como o principal ponto de contato digital para centralizar informações e facilitar o apoio da comunidade.

## 2. Objetivos do Site
O site foi projetado para resolver três dores principais da organização:
* **Aumentar a Arrecadação:** Facilitar o processo de doação financeira através de opções claras de valores (R$ 5, 10, 15) e integração direta para contato via WhatsApp para doações personalizadas.
* **Credibilidade e Transparência:** Mostrar os "Resgates" realizados e a galeria de animais recuperados para provar o impacto do trabalho da ONG.
* **Engajamento de Parceiros:** Destacar empresas que já apoiam a causa (como Cobasi e Agrocat) para incentivar novos patrocinadores e transmitir confiança.

## 3. Público-Alvo
* **Perfil:** Moradores da região oeste de SP (Araçariguama, Sorocaba e arredores).
* **Interesses:** Amantes de animais, potenciais adotantes e pessoas dispostas a contribuir financeiramente com causas sociais.
* **Comportamento:** Usuários que acessam via mobile e desktop, buscando formas rápidas de ajudar ou entrar em contato.

## 4. Estrutura e Conteúdo (Arquitetura da Informação)
O site é uma *Landing Page* com navegação fluida (*smooth scroll*), dividida nas seguintes seções estratégicas:
1.  **Header/Hero:** Imagem de impacto emocional com Call-to-Action (Botão) focado em "DOE AGORA".
2.  **Quem Somos:** História da ONG, missão e área de atuação.
3.  **Resgates:** Galeria visual de casos de sucesso para gerar empatia.
4.  **Parceiros:** Área de prova social com logos de apoiadores.
5.  **Faça uma Doação:** Cards interativos que materializam o valor da doação (ex: R$ 10 = medicamentos), com funcionalidade de Modal para exibição de QR Code PIX.
6.  **Contato:** Dados claros de localização, telefone e links para redes sociais.

## 5. Identidade Visual (Look & Feel)
A interface foi desenhada para transmitir **acolhimento, natureza e seriedade**.

* **Paleta de Cores:**
    * *Background (`#F1E3B6`):* Um tom creme/bege suave para garantir conforto visual e remeter a algo orgânico e natural.
    * *Cor Primária (`#351A03`):* Marrom café escuro para textos e elementos de navegação, oferecendo alto contraste e legibilidade.
* **Tipografia:**
    * Uso da família *Segoe UI/Verdana* para garantir leitura fácil em qualquer dispositivo e um ar moderno.
* **Estilo de UI:**
    * Bordas arredondadas (`border-radius: 20px`) nas seções e imagens para transmitir amabilidade (*friendly*).
    * Sombras suaves para criar profundidade.
    * Interatividade lúdica na galeria de fotos (imagens inclinadas que se alinham ao passar o mouse).

## 6. Tecnologias Utilizadas
* **HTML5 Semântico:** Estruturação correta de seções.
* **CSS3:** Flexbox para layouts, Media Queries para responsividade total e animações de transição.
* **JavaScript:** Manipulação do DOM para o menu responsivo, botão "Voltar ao Topo" e lógica do Modal de Doação.
