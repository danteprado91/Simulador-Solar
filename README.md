# 🪐 Helios System v11.21

**Helios System** é um simulador interativo e cientificamente embasado do Sistema Solar em 3D[cite: 1]. Construído diretamente no navegador, ele combina renderização gráfica avançada com motores de física orbital e de voo, proporcionando tanto uma visão educacional dos astros quanto uma experiência imersiva de exploração espacial.

## ✨ Funcionalidades Principais

* **Motor de Física Kepleriana:** Movimentação orbital realista baseada em efemérides (JPL/NASA J2000), suportando anomalias excêntricas, inclinações e órbitas complexas[cite: 1].
* **Modo Nave (Voo Livre 6DOF):** Assuma o controle de uma nave com física newtoniana inercial[cite: 1]. Inclui sistema RCS (Assistência de Voo) alternável, controle completo de rotação/translação e um efeito visual de *Warp Drive* dinâmico[cite: 1].
* **Gráficos e Shaders Avançados:**
  * **Atmosferas Físicas:** Dispersão de Rayleigh e Mie aplicadas nos shaders para simular halos atmosféricos e o terminador dia/noite[cite: 1].
  * **Geração Procedural:** Superfície solar dinâmica com plasma e Erupções Solares (CMEs), além de Auroras Boreais procedurais na Terra e em Júpiter[cite: 1].
  * **Iluminação Realista:** Luzes de cidades no lado noturno da Terra (Night lights), e anéis planetários com sombras projetadas precisas (Umbra e Penumbra)[cite: 1].
* **Ferramentas de Análise Científica:** Visualização em tempo real de vetores de velocidade e gravidade, malhas geográficas (Latitude/Longitude), eixos polares e marcação da Zona Habitável do sistema[cite: 1].
* **Dados Planetários Detalhados:** Painel de interface contendo gráficos de composição atmosférica, tipo de planeta, tamanho, distância, luas e temperaturas extremas[cite: 1].
* **Trajetórias Históricas:** Mapeamento visual das trajetórias interplanetárias das missões Voyager 1 e Voyager 2[cite: 1].
* **Corpos Celestes Dinâmicos:** Cinturões de asteroides volumétricos (InstancedMesh) e cometas (ex: Halley) com caudas que reagem dinamicamente à proximidade e calor do Sol[cite: 1].

## 🎮 Controles de Voo (Modo Nave)

No "Modo Nave", você pode explorar o vácuo espacial com controles completos de 6 graus de liberdade (6DOF)[cite: 1]:

* `W` / `S`: Acelerar para Frente / Trás[cite: 1]
* `A` / `D`: Translação Lateral (Esquerda / Direita)[cite: 1]
* `R` / `F`: Translação Vertical (Subir / Descer)[cite: 1]
* `Setas Direcionais`: Girar a visão (Pitch e Yaw)[cite: 1]
* `Q` / `E`: Rotação lateral (Roll)[cite: 1]
* `C`: Alternar Assistência de Voo (RCS) - Liga/desliga a frenagem inercial automática[cite: 1]

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3 / JavaScript (ES Modules)**[cite: 1]
* **[Three.js](https://threejs.org/) (v0.160.0):** Biblioteca principal para renderização 3D, instanciamento de malhas e cálculos matemáticos[cite: 1].
* **[Tailwind CSS](https://tailwindcss.com/):** Utilizado via CDN para estilização fluida e moderna da interface de usuário (HUD e menus)[cite: 1].
* **GLSL (Shaders Customizados):** Para efeitos volumétricos, auroras, atmosfera e física de luz avançada[cite: 1].
