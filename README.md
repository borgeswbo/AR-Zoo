# Toninha – protótipo de exibição AR

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Netlify-blueviolet?logo=netlify&style=for-the-badge)](https://ar-zoo-exhibit.netlify.app/) <!-- 🔁 Replace with your real Netlify link -->

Um protótipo estudantil de pequena escala que explora como a Realidade Aumentada (AR) pode ser usada em exposições educacionais para aumentar a conscientização sobre espécies criticamente ameaçadas de extinção, como a **toninha (Pontoporia blainvillei)**.

---

## Visão Geral

Essa experiência de AR foi projetada para ser exibida em museus, escolas ou campanhas de conscientização. Os usuários podem girar, aplicar zoom e explorar um modelo 3D da toninha e acessar informações básicas sobre seu status de ameaça de extinção. Futuras expansões podem incluir exposições de várias espécies, interatividade e cenas acionadas por código QR.

---

## Funcionalidades

- Layout HTML/CSS simples e compatível com dispositivos móveis  
- Modelo `.glb` incorporado com controles de câmera  
- Rotação automática e modo AR ativados  
- Leve, sem necessidade de frameworks  
- Implementável no [Netlify](https://netlify.com)

---

## Estrutura da Pasta

```
/assets
  /models
    dolphin.glb
index.html
style.css
```

---

## Ferramentas utilizadas

- [Model-Viewer by Google](https://modelviewer.dev/)
- HTML5 / CSS3
- Python para hospedagem local
- Netlify

---

## Testando localmente

Para testar localmente, baixe este repositório, abra o terminal de comando na pasta e execute:

```bash
python -m http.server
```

No navegador, abra:
```bash
http://localhost:8000
```

---

## Estrutura Analítica do Projeto (WBS)

```mermaid
graph TD
  A[Protótipo AR Zoo – 7 dias no total]

  A1[Configuração do projeto – 1 dia]
  A2[Integração do modelo 3D – 1 dia]
  A3[Layout básico de HTML e CSS – 1 dia]
  A4[Estilização compatível com dispositivos móveis – 1 dia]
  A5[Texto informativo e acessibilidade – 1 dia]
  A6[Testes e correções locais – 1 dia]
  A7[Implementação e README – 1 dia]

  A --> A1
  A --> A2
  A --> A3
  A --> A4
  A --> A5
  A --> A6
  A --> A7
```

---

## Funcionalidades futuras (Planejadas)

- [ ] Adicionar cenas de AR de outras espécies difíceis de serem observadas em seu ambiente natural.  
- [ ] Cenas acionadas por códio QR em locais selecionados.  
- [ ] Narração em áudio e hotspots de informação interativos  
- [ ] Alternância de idiomas (português/inglês)  
- [ ] Reprodução de animações para os modelos 3D 

---

## Sobre a toninha

A toninha (Pontoporia blainvillei), também chamada de boto-cachimbo ou franciscana é uma espécie de golfinho fluvial nativo da América do Sul e em **perigo de extinção**. Entre as ameaças que enfrenta estão as redes de pesca, a pesca excessiva de suas presas e a poluição.

---

## Licença & Créditos

- Modelo 3D usado apenas para fins educacionais  
- Criado por William Borges como parte de um trabalho escolar  
- [Model-Viewer](https://github.com/google/model-viewer) sob Apache License 2.0

---

