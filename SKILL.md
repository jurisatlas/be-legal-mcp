---
name: be-legal-mcp-skill
description: Official Belgium (BE) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Belgium Legal Research & Multi-Tier Case Law Skill (`be-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Belgium (BE)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `ECLI:BE:CASS:2024:ARR.20240115 or Moniteur Belge`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Tribunaux de première instance / Rechtbanken van eerste aanleg, Tribunaux de l'entreprise / Ondernemingsrechtbanken & Tribunaux du travail / Arbeidsrechtbanken
   - **Second Instance (Cantonal / Regional / Appellate):** 5 Cours d'appel / Hoven van beroep (Bruxelles/Brussel, Liège, Mons, Gent, Antwerpen) & 5 Cours du travail / Arbeidshoven
   - **Supreme & Constitutional Instance:** Cour de cassation / Hof van Cassatie, Cour constitutionnelle / Grondwettelijk Hof & Conseil d'État / Raad van State
   - **Primary Tiered Database:** Juportal (juportal.be — First Instance, 5 Courts of Appeal & Court of Cassation) (`https://juportal.be`)
