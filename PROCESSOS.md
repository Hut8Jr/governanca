# 📐 Padrão de Engenharia e Gestão — Hut 8 Jr.

Este documento define como os projetos da Hut 8 Jr. devem ser organizados no GitHub para garantir qualidade de código e agilidade.

## 🛠️ Fluxo de Trabalho (Gitflow Simplificado)
1. **Main:** Branch protegida. Ninguém commita nela diretamente.
2. **Pull Requests:** Obrigatórios para qualquer alteração de código. Deve seguir o template configurado.
3. **Issue Templates:** Obrigatórios para abrir tarefas. Exigem Critérios de Aceite e links do Figma.

## 📊 Board Estratégico (Projeto #5)
O Kanban deve ser operado usando as seguintes colunas personalizadas:
- **Etapa (Kanban):** `To Do` -> `In Progress` -> `Em Revisão` -> `Done`.
- **Tipo de Task:** Classificar entre `✨ Feature`, `🐛 Bug Crítico`, `🛠️ Melhoria` ou `📚 Documentação`.
- **Fase de QA:** Controlar o ciclo de vida (`💻 Desenvolvimento` -> `👀 Em Revisão` -> `✅ Aprovado`).
- **Time Responsável:** Atribuir à Squad correta (ex: `🚀 Squad 1`).

## 🏷️ Sistema de Labels
- `squad-1`: Azul escuro.
- `squad-2`: Verde.
- `squad-3`: Reservada até o primeiro repositório ser associado.
- `squad-carne`: Roxo.
- `bug: crítico`: Vermelho vivo.
- `revisão`: Rosa (QA).
- `urgente`: Vermelho sangue.

## 👥 Membros e Squads (Ativos)
- **Squad 1 — Ciere:** @joaoMarceloBitar (líder), @Rodrigo-AP-1, @VictorReis18 e @DevTheusP.
  - Repositório: [ciere-advocacia-landing-page](https://github.com/Hut8Jr/ciere-advocacia-landing-page)
  - Design: [Figma — Ciere Rosa](https://www.figma.com/design/3wuWAEO7jASckzKLDNRa7f/Hut8-%7C-Landing-page-%7C-Ciere-Rosa?node-id=141-884&t=N5LpW4lsDbJUFAGk-1)
  - Ativos: @joaoMarceloBitar e @Rodrigo-AP-1.
  - Onboarding pendente: @VictorReis18 e @DevTheusP.
- **Squad 2 — Auto Repair:** @Brendler17 (líder), @PedroMBortoli, @pedroizk, @marianatica e @EnzoGiacomini.
  - Todos os integrantes estão ativos.
  - Repositórios: [auto-repair-mvp](https://github.com/Hut8Jr/auto-repair-mvp) e [auto-repair-api](https://github.com/Hut8Jr/auto-repair-api).
- **Squad 3 — Em formação:** @Caspessoa (líder), @PMota173, Manuela Viera, Alan Alves e Kenzo Takahashi.
  - Ativo: @PMota173.
  - Onboarding pendente: @Caspessoa.
  - GitHub a confirmar: Manuela Viera, Alan Alves e Kenzo Takahashi.
  - Nenhum projeto ou repositório associado.
- **Squad +CARNE:** @AugustoMenchaca (governança), @gutormolina, @PMota173 e @pedroizk.
  - Repositório: [projeto-mais-carne-poc](https://github.com/Hut8Jr/projeto-mais-carne-poc)
- **Diretoria:** @Lettnin (Presidência), @AugustoMenchaca (Projetos), Gabriel Martins (Financeiro, GitHub não identificado), Amanda Viera (Marketing, sem GitHub) e @inaciortx (Pessoas).

---
*Documento atualizado em 06/08/2026.*
