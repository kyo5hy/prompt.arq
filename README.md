# Prompt.Arq | Architectural Render Workflow

Uma solução desenvolvida para **otimizar a criação de visualizações arquitetônicas de alto padrão** por meio de **engenharia de prompts estruturados**, garantindo fidelidade geométrica e realismo físico com Inteligência Artificial.

---

## 📐 Sobre o Projeto

O **Prompt.Arq** nasceu de um desafio real do mercado de arquitetura:  
auxiliar arquitetos e designers a obterem **renders fotorealistas** com IA **sem perder o controle da geometria original do projeto**.

Ferramentas de IA generativa costumam “interpretar” demais plantas, cortes e modelos, gerando imagens artísticas, porém **imprecisas tecnicamente**.

Este projeto atua como uma **ponte técnica entre o arquiteto e a IA**, utilizando um sistema de **JSON estruturado** para:

- Travar geometria  
- Controlar iluminação  
- Manter realismo físico (PBR)  
- Eliminar estilização artística indesejada  

O processamento final é realizado no **Google Gemini**, com controle absoluto via prompts programados.

---

## 🛠️ Como o Sistema Resolve o Problema

O workflow do **Prompt.Arq** é dividido em **três pilares fundamentais**:

### 1️⃣ Geração do JSON MASTER

- Utiliza **travas absolutas (LOCKS)** para impedir distorções
- Define:
  - Estilo fotográfico
  - Iluminação global realista
  - Materiais PBR
  - Geometria imutável
- O arquiteto informa os parâmetros desejados e o sistema gera um **JSON estruturado**, educando a IA a priorizar precisão técnica em vez de interpretação artística

---

### 2️⃣ Motor de Render (Google Gemini)

- O **JSON MASTER** é aplicado diretamente no Gemini
- A imagem base é usada **exclusivamente como referência geométrica**
- O sistema garante:
  - Preservação total da volumetria
  - Iluminação coerente
  - Materiais realistas
  - Zero efeito cartoon ou estilização

---

### 3️⃣ Ajustes Controlados (JSON Delta)

- Evita retrabalho e múltiplos renders do zero
- Permite ajustes pontuais como:
  - Troca de materiais
  - Alteração de cores
  - Substituição de mobiliário
- Utiliza um **JSON Delta**, que:
  - Identifica elementos específicos (especialmente quando marcados visualmente com setas ou círculos)
  - Aplica alterações **preservando 100% do restante da imagem**

---

## 🚀 Diferenciais Técnicos

- **Interface Estúdio**
  - UI focada em estética arquitetônica
  - Grids técnicos, minimalismo e organização visual

- **Workflow Guiado**
  - Validação por etapas
  - Impede erros comuns e saltos de processo

- **Prompt Engineering Avançado**
  - Lógica de programação aplicada a prompts
  - Consistência visual entre múltiplos renders
  - Controle absoluto sobre o comportamento da IA

---

## 💻 Tecnologias e Linguagens

O projeto foi desenvolvido como uma **SPA (Single Page Application)**, priorizando leveza, performance e experiência profissional:

- **HTML5**
  - Estrutura semântica
  - Foco em acessibilidade

- **CSS3 (Tailwind CSS)**
  - Design responsivo
  - Glassmorphism
  - Layout moderno e limpo

- **JavaScript (ES6+)**
  - Manipulação dinâmica de prompts
  - Controle de estados e navegação

- **AOS Library**
  - Animações de scroll
  - Transições suaves

- **Lucide Icons**
  - Iconografia técnica vetorial

---

## 📌 Público-Alvo

- Arquitetos
- Designers de interiores
- Estúdios de visualização arquitetônica
- Profissionais que exigem **controle técnico total** em renders com IA

---

## 🏗️ Status do Projeto

🟢 Em desenvolvimento ativo  
🟢 Estrutura funcional  
🟢 Pronto para uso profissional

---

## 👨‍💻 Desenvolvido por

**Kyotech Studio**  
*Inovação tecnológica aplicada à visualização arquitetônica.*
