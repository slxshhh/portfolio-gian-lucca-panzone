# 👔 ProfiMatch - Classificador de Perfis Profissionais via IA

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Teachable_Machine](https://img.shields.io/badge/Teachable_Machine-4285F4?style=for-the-badge&logo=google&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 📝 Descrição do Projeto
O **ProfiMatch** é um experimento técnico de visão computacional desenvolvido para analisar como modelos de Deep Learning interpretam "Perfis de Liderança" e "Perfis Operacionais". O objetivo central do projeto é investigar a formação de vieses algorítmicos quando expostos a datasets com seleções restritas de vestuário e contexto.

Diferente de sistemas de RH convencionais, o ProfiMatch utiliza o motor do **TensorFlow.js** para processar frames de vídeo em tempo real, servindo como uma ferramenta educacional e crítica sobre o impacto da ética na Inteligência Artificial e como a correlação entre "Terno vs. Casual" pode corromper a lógica de classificação de competências humanas.

![Figura 1: Interface de detecção em tempo real classificando perfis baseados em padrões visuais.](./images/main-dashboard.png)
*Figura 1: Interface de detecção em tempo real classificando perfis baseados em padrões visuais.*

## 🚀 Tecnologias Utilizadas
* **Frontend:** React 18, Vite, Framer Motion
* **Estilização:** Tailwind CSS (Design focado em Dashboard Analítico)
* **Inteligência Artificial:** Teachable Machine (Modelo de Classificação de Imagens)
* **Core Engine:** TensorFlow.js para inferência local no navegador
* **Dataset:** Curadoria específica de imagens para teste de viés (Formal vs. Operacional)

## 📊 Resultados e Aprendizados
O projeto serviu como uma prova de conceito sobre a importância da curadoria de dados e a responsabilidade do desenvolvedor.
* **Identificação de Viés:** Concluí que a IA cria estereótipos imediatos (ex: Terno = Líder) se o treinamento não for diversificado, ignorando competências reais.
* **Performance de Inferência:** Implementei o carregamento assíncrono do modelo `tm-my-image-model`, garantindo uma taxa de atualização superior a 30 FPS no navegador.
* **Human-in-the-loop:** Aprendi a desenhar intervenções éticas onde a curadoria humana atua na recalibragem de pesos para garantir a equidade do sistema.

![Figura 2: Análise de confiança do modelo e métricas de classificação por categoria.](./images/metrics-view.png)
*Figura 2: Análise de confiança do modelo e métricas de classificação por categoria.*

## 🔧 Como Executar
1. Clone o repositório: `git clone https://github.com/gianluccapanzone/profimatch`.
2. Instale as dependências: `npm install`.
3. Adicione os arquivos do modelo (`model.json`, `weights.bin`) na pasta public.
4. Inicie a aplicação: `npm run dev`.

![Figura 3: Fluxo de processamento desde a captura da câmera até a resposta do modelo.](./images/pipeline-ia.png)
*Figura 3: Representação visual do fluxo de dados e comunicação entre os serviços.*

---
[Voltar ao início](https://github.com/gianluccapanzone/profimatch)
