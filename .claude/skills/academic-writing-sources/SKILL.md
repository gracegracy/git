---
name: academic-writing-sources
description: Rigorous, verified sourcing for academic writing. Use whenever drafting, revising or checking academic text, including thesis chapters, journal manuscripts, literature reviews, responses to reviewers or examiners, research proposals and conference papers, and whenever the user asks for references, citations or evidence for a claim. Every important statement must be backed by a verified, reliable source. Prefer peer-reviewed work from Elsevier (ScienceDirect), Springer Nature, Routledge/Taylor & Francis or Wiley, or official sources such as international organisations, governments and regulators. Give the user a working link for every source and flag anything not fully verified. Use this skill even when the user only says "write this section", "revise this paragraph", "add references" or "plan the revision", because academic text without verified sources is not usable.
---

# Academic writing with reliable sources

Examiners, reviewers and editors check citations. A fabricated DOI, a wrong page range, or a source that does not say what the text claims damages the author's credibility far more than a missing citation does. The aim of this skill is text in which every important statement can be traced to a reliable source, the user can see and open that source, and anything uncertain is visibly flagged rather than hidden.

## 1. What needs a source

Treat a statement as needing a citation if a careful examiner could reasonably ask "how do you know?". In practice:

- facts and statistics, such as throughput, market shares, rankings, regulatory dates and targets;
- claims about what the literature has found, or about gaps in it;
- theoretical claims, such as "absorptive capacity theory holds that…";
- definitions of key concepts and the origin of a method or framework;
- claims about a country, organisation or policy;
- any claim used to justify a design choice, such as the choice of sample, context or method.

Statements about the author's own results cite the relevant chapter, section, table or figure rather than an external source. Interpretive or synthesising claims that go beyond any one source should be worded as the author's interpretation ("this suggests…", "consistent with…"), not presented as established fact.

## 2. Source hierarchy

Use the highest tier that genuinely supports the claim.

**Tier 1: peer-reviewed academic work from the preferred publishers.** Journal articles and scholarly books from Elsevier (ScienceDirect, including Pergamon and North-Holland imprints), Springer Nature (including Palgrave Macmillan and Nature titles), Taylor & Francis (including Routledge) and Wiley (including Wiley-Blackwell and Jossey-Bass). Prefer established journals in the field over obscure ones, and recent work for current-state claims. For foundational ideas, cite the original work.

**Tier 1b: other reputable scholarly publishers.** Examples are SAGE, Oxford University Press, Cambridge University Press, Emerald, INFORMS, the Academy of Management and the American Economic Association. Use these when the classic or best source for a claim is published there, for example a seminal paper. They are fully acceptable, but tell the user that they fall outside the preferred list.

**Tier 2: official sources.** Use these for statistics, regulations and policy facts:

- international organisations, such as UNCTAD, OECD, the World Bank, IMO, IEA, WIPO and the UN;
- the European Commission, EUR-Lex and EU agencies;
- national ministries, regulators and statistics offices;
- port authorities;
- a company's own official releases, but only for facts about that company.

Always cite the primary release (the agency's own page, report or press release), not a news story that repeats it. When a newer edition or year of the data exists, use the newest.

**Tier 3: reputable trade press and news.** Examples are Reuters, S&P Global, Argus, Lloyd's List and the Financial Times. Use these only when no official or academic source can be found for a specific fact, such as the date a standard was announced. Flag the citation as news-based.

**Avoid as evidence:**

- Wikipedia, blogs, content farms and AI-generated summaries. These may help you find a primary source, but never cite them.
- Predatory or unindexed journals.
- Retracted papers.
- Statistics with no traceable origin.

Use open-access mega-journals (e.g., MDPI titles) with care. Prefer a preferred-publisher source for the same point when one exists.

## 3. Finding and verifying a source

For each source:

1. **Search** with the web search tool, using author, title, journal or key phrase. Use publisher sites, DOI pages, Crossref, RePEc/IDEAS, PubMed Central, university repositories and official websites to confirm the details. A list of portals is in `references/source-portals.md`.
2. **Confirm the bibliographic details** from at least one reliable record: authors, year, title, journal or publisher, volume, issue, pages or article number, and DOI. Never construct a DOI, page range or volume from memory or by pattern. If a detail cannot be confirmed, omit it and mark the entry for the user to check.
3. **Confirm the content.** Check that the source actually supports the specific statement, at least from the abstract, summary or the relevant section. If only the abstract was seen, word the claim no more strongly than the abstract supports. Do not attribute findings to a paper based on its title alone.
4. **Check currency.** For statistics, regulations and rankings, check whether a more recent edition exists before citing an older one.
5. **Record the verification status** so it can be reported (Section 6).

Some environments block DOI resolvers, Crossref or publisher pages. If that happens, verify through search results and repository records instead, and tell the user which details you could not open directly.

## 4. Citations and reference list

- Match the citation style already used in the user's document. If none is evident, use APA 7th edition.
- Give an in-text citation for every sourced statement and a full reference-list entry for every in-text citation, and vice versa. Run a consistency check before delivering: every name and year cited in the text appears in the list, and the list contains nothing that is not cited.
- When adding to an existing document, reuse the user's existing references where they fit. Mark entries already in their list (e.g., †) so they do not duplicate them. Point out inconsistencies you notice in their existing list, such as wrong years, duplicate entries, mismatched suffixes (2024a/2024b) or author-format errors.
- Include DOIs as https://doi.org/... links where they are confirmed. For official sources without a DOI, give the stable URL.

## 5. Writing style for academic text

Unless the user asks otherwise:

- Write in continuous, well-structured paragraphs with clear topic sentences. Avoid bullet points in thesis or manuscript text.
- Keep tables concise, with short phrases in cells. Move citations out of table cells into a "Sources:" note under the table.
- Use a formal, measured register. Distinguish association from causation, and match the strength of a claim to the strength of the evidence and design.
- Follow the spelling convention of the user's document (e.g., British English).
- Be candid about limitations. A clearly stated boundary ("the coefficients apply only to the studied context") is more persuasive to examiners than an overclaim.
- Write revised thesis or manuscript text as normal academic writing. Never mention reviewers, examiners, their comments or suggestions, or the revision process in the thesis text itself (no "as the reviewer suggested", "in response to the examiner"). Such statements belong only in the response letter.

## 6. What to report back to the user

After drafting, give the user, in the chat:

1. **A source list with links.** For each source: a markdown link (DOI or official URL), one line on what it supports, and its status:
   - ✓ details confirmed (say how, e.g., "publisher page" or "DOI record via search");
   - ‡ some detail not confirmed (say which: pages, DOI, date);
   - † already in the user's reference list.
2. **Anything left unsourced,** with a suggested fix (Section 7).
3. **Publisher notes:** any source outside the preferred publishers, and any news-based (Tier 3) citations.

Keep this report short and scannable. The point is that the user can open and check each source quickly.

## 7. When no reliable source can be found

Do not fill the gap with an invented or weak citation. Instead:

- reword the statement so it is supported by what you do have;
- present it as the author's own interpretation or as a finding of the thesis, with a chapter reference;
- leave a clearly marked placeholder (e.g., "[source needed: labour arrangements in Chinese terminals]") and tell the user; or
- recommend removing the statement.

Say plainly what you searched for and could not find, so the user can decide or search their library databases.

## Reference files

- `references/source-portals.md` lists databases, publisher platforms, official data portals and integrity-checking tools, with links. Read it when you need to locate or verify a source, or when the user asks where to search.
