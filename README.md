# ☕ Triple Espresso - Coffee Shop

## 📅 Sprints

Projeto da **Sprint 4** do curso de Desenvolvimento Web da TripleTen Brasil.

| Sprint | O que foi feito neste repositório |
| --- | --- |
| 4 | página da cafeteria: BEM Flat, formulário de reserva, vídeo com `iframe`, Google Fonts e estados `:hover` |

---

## 📝 Descrição do Projeto
O **Triple Espresso** é uma página web desenvolvida para uma cafeteria situada na biblioteca Triple Peaks. O objetivo do projeto é oferecer um ambiente digital aconchegante que reflita a experiência física do local, permitindo que estudantes e amantes de café consultem horários, aprendam novas receitas e façam reservas de mesas.

### 🛠 Tecnologias Utilizadas
* **HTML5 Semântico**: Estruturação robusta utilizando tags que melhoram a acessibilidade e o SEO.
* **CSS3 (Metodologia BEM)**: Organização das folhas de estilo seguindo o padrão *Block Element Modifier*, garantindo que o código seja limpo e fácil de manter.
* **Integração de Mídia**: Uso de `iframes` para incorporação de vídeos do YouTube e fontes externas via Google Fonts (*Inter* e *Noto Serif*).
* **Formulários Estruturados**: Sistema de captura de dados para reservas com validações nativas de campo.

---

## 🔧 Melhorias depois da sprint

Revisão feita depois da entrega, mantendo o HTML e o CSS puros e o padrão BEM
Flat (cada media query fica no arquivo do próprio bloco).

| O que mudou | Por quê |
| --- | --- |
| Fundos com caminho relativo (`../images/...`) | O caminho `/web_project_coffeeshop/images/...` só funcionava no GitHub Pages; aberto localmente, os círculos decorativos sumiam |
| Ilustração do topo posicionada dentro da página | Em telas largas ela colava na borda da janela, fora do container de 1600px |
| **Responsividade** de 320px a 1920px (pontos de quebra em 1439, 1200, 1024, 768 e 480px) | Antes, o `min-width: 1100px` gerava rolagem lateral no celular e a ilustração cobria o título abaixo de 1440px |
| Vídeos em grade de uma coluna no celular, com proporção 16:9 | Os vídeos acompanham a largura da tela sem se sobrepor |
| Campo "Data e hora" com `datetime-local` | O rótulo pedia data e hora, mas o campo só aceitava a data |
| Termos de uso obrigatórios e antes do botão | O aceite precisa vir antes do envio |
| `lang="pt-BR"`, títulos descritivos nos `iframe`, hierarquia `h1 → h2 → h3` | Acessibilidade para leitores de tela |
| Foco visível no teclado, transições suaves no `:hover`, `cursor: pointer` no botão, rolagem suave que respeita `prefers-reduced-motion` | Acabamento e acessibilidade |
| Espaçamento interno nos campos do formulário | O texto digitado encostava na borda |

---

## 📈 Planos de Melhoria
Abaixo, listo as funcionalidades e evoluções que planejei para este projeto, demonstrando uma visão de expansão técnica e de experiência do usuário:

1.  **Integração com API de Mapas**: Implementar o Google Maps na seção de contatos para que o cliente possa traçar a rota até a cafeteria em Triple Peaks diretamente da página.
2.  **Galeria de Imagens Dinâmica**: Desenvolver um carrossel de fotos do ambiente da biblioteca para mostrar mais detalhes do espaço físico, utilizando técnicas avançadas de posicionamento e animação CSS.

---

## 👤 Autor
**Leonardo Dias Caumo** - *Desenvolvido como parte do portfólio de estudos em Desenvolvimento Web da TripleTen.*

---
© 2026 Leonardo Dias Caumo
