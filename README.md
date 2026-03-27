# Olá, eu sou Tatiana de Aguiar 👋

**Senior Fullstack Engineer | 3D Graphics Specialist | Product Engineer**

Não escrevo apenas código; eu construo produtos que resolvem problemas reais. Minha especialidade é unir matemática computacional, renderização 3D de alta performance e arquitetura web escalável para criar ecossistemas interativos complexos. 

Atuo na interseção entre **Engenharia de Software e Visão de Produto**, tomando decisões arquiteturais que priorizam a eficiência da aplicação, a experiência do usuário e o valor entregue ao negócio.

---

## 🔬 Projeto em Destaque: Ecossistema Clínico Interativo 3D

Atualmente, sou a engenheira líder por trás do desenvolvimento de um **Ecossistema Clínico 3D** proprietário, focado em elevar o padrão de diagnóstico e atendimento para profissionais de Massoterapia, Acupuntura e Quiropraxia.

> 🔒 *Nota: O repositório deste projeto é privado por conter propriedade intelectual clínica e arquitetural.*
> 
> 🎥 **[Clique aqui para assistir à demonstração técnica e clínica no meu LinkedIn] (Link_do_Video_Aqui)**

### O Desafio de Negócio e Clínico
Profissionais de saúde visualizam o corpo humano em 3D, mas registram dados em 2D. O desafio foi construir uma ferramenta de precisão clínica — não apenas um modelo visual — que servisse como um "mapa interativo" para mapeamento de pontos terapêuticos, análise postural e estruturação de dossiês de saúde visual, tudo renderizado nativamente no navegador sem perda de performance.

### Soluções de Engenharia e Tomada de Decisão (CTO View)

* **Matemática Computacional e Raycasting Espacial:** Desenvolvi um sistema de precisão baseado em cálculo espacial (conversão `worldToLocal`) e interseção vetorial. Isso permite o clique e registro cirúrgico de pontos de acupuntura e gatilhos musculares na malha 3D, mantendo a precisão das coordenadas independentemente da rotação da câmera ou zoom.
* **Performance 3D e PBR no Navegador (Smart Shading):** Para evitar o carregamento de texturas massivas que destruiriam a retenção do usuário (UX), projetei um motor de "Smart Shading" via código. Utilizando React Three Fiber e shaders baseados em física (PBR), o sistema injeta cores dinâmicas e cálculos de rugosidade (`roughness`/`metalness`) em tempo real, entregando tecido orgânico e fisiologicamente realista com frações do custo de memória.
* **Arquitetura de Dados Fortemente Tipada:** Estruturei o ecossistema com TypeScript rigoroso. Cada osso, músculo ou nervo não é apenas uma malha (mesh), mas uma entidade de dados rastreável. Isso permite associar lateralidade, patologias e histórico clínico diretamente à geometria 3D de forma escalável.

---

## 🛠️ Stack Tecnológica & Especialidades

### Core 3D & WebGL
* **Three.js & React Three Fiber (R3F):** Manipulação de Scene Graph, PBR Materials, Lighting, Tone Mapping.
* **Matemática 3D:** Álgebra linear aplicada, matrizes de transformação, quaternions, raycasting.
* **Otimização de Assets:** Gestão de pipeline GLB/GLTF, compressão de geometria, vertex colors.

### Fullstack & Arquitetura
* **Frontend:** React, TypeScript, gerenciamento de estado complexo acoplado ao canvas 3D.
* **Backend:** Node.js, construção de APIs para persistência de dados espaciais e clínicos.
* **Práticas:** Clean Architecture, Code as Design, Performance Profiling.

---

## 💡 Filosofia de Engenharia

1.  **Ferramentas devem ser invisíveis:** O usuário (médico/terapeuta) deve focar no paciente, não na interface. Reduzo a fricção através de UX fluida e interações nativas.
2.  **O Código trabalha para o Produto:** Uma arquitetura complexa só faz sentido se gerar utilidade real. Troco "overengineering" por soluções eficientes que entregam o ROI esperado.
3.  **Precisão é inegociável:** Em contextos de saúde, a exatidão da informação visual e do armazenamento de dados dita a autoridade da ferramenta.

---

### 📬 Vamos conectar?

Sempre aberta a discutir arquitetura de software, inovações em WebGL e como a tecnologia 3D pode transformar produtos.

* [LinkedIn](Seu_Link_Aqui)
