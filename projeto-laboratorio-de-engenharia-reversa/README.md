# 🎨 QR Code Styling - Professional Design Platform

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Motion](https://img.shields.io/badge/Motion-000000?style=for-the-badge&logo=framer&logoColor=white)

## 📝 Descrição do Projeto
O **QR Code Styling** é uma plataforma de design de alto nível para a criação de códigos QR personalizados e profissionais. O projeto permite que usuários transformem códigos QR genéricos em peças de branding únicas, ajustando desde a geometria dos pontos até gradientes complexos nos cantos, tudo com um preview em tempo real.

Inspirado na biblioteca de Denys Kozak, este app oferece uma interface minimalista com estética **Glassmorphism**, focando na facilidade de uso para designers e desenvolvedores que precisam de códigos QR com identidade visual marcante.

![Figura 1: Dashboard principal do QR Code Styling exibindo a interface de design e preview em tempo real.](https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=1000)
*Figura 1: Dashboard principal do sistema exibindo as 8 categorias de ferramentas de customização e preview em tempo real.*

## 🚀 Tecnologias Utilizadas
* **Frontend:** React 19, Vite, Motion (Animações de entrada e transições)
* **Estilização:** Tailwind CSS 4 (Arquitetura Glassmorphism com paleta White & Pink)
* **Componentes:** Shadcn/UI (Accordion, Inputs, Sliders, Tabs) e Lucide React para ícones
* **Core Engine:** QR Code Styling (Pipeline de renderização híbrida SVG/Canvas)

## 📊 Resultados e Aprendizados
O projeto implementa uma interface de estúdio completa com 8 seções de controle granular:
* **Customização Atômica:** Controle total sobre `Dots`, `Corners Square`, `Corners Dot`, e `Background`.
* **Motor de Gradientes:** Implementação de suporte a gradientes lineares e radiais com controle de rotação em todas as partes do código.
* **Pipeline de Imagem:** Integração de logos com controles de margem, tamanho e opção de "ocultar pontos" para garantir legibilidade máxima.
* **Exportação Profissional:** Suporte nativo para download em PNG, JPEG e SVG, além da exportação do estado atual em JSON.

![Figura 2: Detalhes da interface de controle de pontos e gradientes.](https://images.unsplash.com/photo-1558655146-d09347e92766?auto=format&fit=crop&q=80&w=1000)
*Figura 2: Análise da interface detalhada para customização de formas e cores.*

## 🔧 Como Executar
1. Clone o repositório: `git clone https://github.com/user/qr-styling`.
2. Instale as dependências: `npm install`.
3. Inicie o estúdio de design: `npm run dev`.

![Figura 3: Representação visual da arquitetura de componentes do sistema.](https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=1000)
*Figura 3: Representação visual do fluxo de dados entre o estado do React e a engine de renderização.*

---
[Voltar ao início](https://github.com/user/qr-styling)
