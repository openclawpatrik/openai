# PR ‑plan: Dokumentation och mallar

1. **Syfte:** Lägga till dokumentation och mallar för processerna “Mission Control”, standardmallar för uppdrag, Morning Brief, Weekly Digest och QA‑checklista i repositoryt.
2. **Branch:** Denna PR skapas från en separat dokumentationsbranch (`docs-templates`) för att undvika förändringar i huvudbranschen.
3. **Filer som inkluderas:**
   - `docs/mission-control.md` – Kanban struktur med kolumnerna Backlog, Doing, Review, Done samt WIP regler och definition of done.
   - `docs/prompt-mallar.md` – Standardmall för uppdrag (promptmall) med rubriker för mål, förutsättningar, leverans och risker.
   - `docs/morning-brief.md` – Mall för daglig morgonbrief med sektioner för datum, lägesrapport, plan, blockerare och assistentens status.
   - `docs/weekly-digest.md` – Mall för veckovis sammanfattning med highlights, uppgiftsstatus, risker och nästa veckas fokus.
   - `docs/qa-checklista.md` – QA checklista för pull requests och förändringar.
   - `docs/pr_plan.md` – Denna plan för PR:n för spårbarhet.
4. **Commit meddelande:** “Add documentation and templates (Mission Control, prompt mall, Morning Brief, Weekly Digest, QA checklist, PR plan)”
5. **Pull request:** Skapa en PR mot huvudbranschen och länka till relaterade issues. Inkludera sektionerna What/Why/Verify i beskrivningen. `Verify` ska notera att PR:n endast innehåller dokumentation och inte påverkar runtime.
