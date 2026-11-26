# Vittace Bosque CRM — protótipo 3D

Protótipo de CRM para o Condomínio Residencial Vittace Bosque (Capão Raso, Curitiba-PR), com o condomínio inteiro em 3D.

- 28 torres × 4 pavimentos × 4 apartamentos (448 unidades), posicionadas pela prancha de implantação e orientadas pelo norte real
- Clique numa torre para abrir os andares; clique num apartamento para ver a planta 3D
- Quatro perfis de acesso:
  - **Morador**: boletos, visitas (com placa), reservas, chamados e encomendas
  - **Portaria**: entrada e saída de veículos, consulta de placa, visitas autorizadas e encomendas
  - **Síndico**: inadimplência, moradores, chamados, avisos, reservas e registro da portaria
  - **Construtora**: andamento da obra, assistência técnica, entregas e documentos
- Layout adaptado para celular, com navegação inferior

Feito em HTML + [Three.js](https://threejs.org) r147, sem build: basta abrir o `index.html`.

> Os dados de moradores, financeiro e obra são fictícios, só para demonstração.

## Publicar no GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch `main` / `/ (root)` → Save.
