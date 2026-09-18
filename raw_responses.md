# Raw Model Responses — Q3, Q4, Q5

**Date of collection:** September 2026  
**Prompt used:** See [`prompts/strict_citation_prompt.txt`](../prompts/strict_citation_prompt.txt)  
**Models:** DeepSeek, Claude, ChatGPT (exact versions unspecified; accessed via web interface)

**Note:** Q1 and Q2 were pilot questions. None of the models provided formal citations for those, so they are excluded from this dataset.

---

## Q3: What is the current evidence on CRISPR-based therapies for sickle cell disease?

### DeepSeek Response

The current evidence on CRISPR-based therapies for sickle cell disease (SCD) is highly promising, with multiple clinical trials demonstrating durable efficacy and a favorable safety profile. The therapeutic strategy primarily focuses on reactivating fetal hemoglobin (HbF) by either disrupting the BCL11A erythroid enhancer or the HBG1/HBG2 promoters using CRISPR-Cas9 or CRISPR-Cas12a platforms.

**Key Clinical Evidence**

Exagamglogene autotemcel (exa-cel, Casgevy): This CRISPR-Cas9 therapy targeting the BCL11A enhancer has shown remarkable long-term results. In the pivotal Phase 3 CLIMB SCD-121 trial and its long-term extension CLIMB-131, 100% (45/45) of evaluable SCD patients achieved freedom from severe vaso-occlusive crises (VOCs) for at least 12 consecutive months, with a median follow-up exceeding 3 years. Durable increases in total and fetal hemoglobin were observed, and allelic editing remained stable over time. A systematic review reported that the prospectively defined VF12 (freedom from severe VOCs for ≥12 months) was 96.7% (29/30) in the exa-cel pivotal cohort.

Renizgamglogene autogedtemcel (reni-cel): This investigational CRISPR-Cas12a therapy disrupts BCL11A binding sites in the HBG1 and HBG2 promoters. In a Phase 1–2 trial (RUBY), 28 patients with severe SCD were treated. At month 6, among 18 patients with available data, the mean total hemoglobin level increased from 9.8 g/dL at baseline to 13.8 g/dL, with no vaso-occlusive events occurring.

Base Editing Approaches: Early-phase trials using transformer base editors (tBE) to reactivate HbF have also shown feasibility in SCD. A recent report described an African SCD patient who achieved durable editing, sustained high-level pan-cellular HbF expression, and transfusion independence with no vaso-occlusive episodes after more than 12 months of follow-up.

**Systematic Reviews and Syntheses**

A systematic review of clinical trials (6 studies, 115 patients) concluded that CRISPR/Cas9-mediated disruption of either the BCL11A enhancer or γ-globin gene promoters results in significant HbF activation, elevated total hemoglobin, and repression of vaso-occlusive episodes in SCD, supporting a potential one-time functional cure. A more recent systematic review (25 reports, 148 infused patients across lentiviral, CRISPR-Cas9, CRISPR-Cas12a, and base-editing platforms) confirmed substantial short- to medium-term reductions in severe VOCs and improved hemoglobin biology, while noting that certainty remains limited by single-arm designs, small samples, and incomplete long-term follow-up.

**Implementation Considerations**

As the first CRISPR-based therapy to enter clinical practice, exa-cel has established a delivery model that includes mobilization, apheresis, centralized manufacturing, myeloablative conditioning, and long-term surveillance. Key barriers include stem-cell collection complexity, conditioning-related toxicity, high cost, and persistent inequities in access.

**References**

Hanna, R., Frangoul, H., Pineiro, L., McKinney, C., Mapara, M., Dalal, J., ... & Walters, M. C. (2026). CRISPR-Cas12a Gene Editing of HBG1 and HBG2 Promoters to Treat Sickle Cell Disease. New England Journal of Medicine, 394(13), 1281-1291. https://doi.org/10.1056/NEJMoa2415550

Grupp, S. A., et al. (2026). Durable Clinical Benefits with Exagamglogene Autotemcel for over 5 Years of Follow-up in Transfusion-Dependent Thalassemia and Sickle Cell Disease with Recurrent Vaso-Occlusive Crises. Transplantation and Cellular Therapy, 32(2), S2-S3. https://doi.org/10.1016/j.jtct.2025.12.025

Ahmed, R., et al. (2026). CRISPR/Cas9 System as a Promising Therapy in Thalassemia and Sickle Cell Disease: A Systematic Review of Clinical Trials. Molecular Biotechnology, 68(1), 23-32. https://doi.org/10.1007/s12033-025-01368-x

Shaik, M. Y., & Divers, S. (2026). Efficacy, Safety, and Treatment-Delivery Feasibility of Autologous Gene Therapy for Sickle Cell Disease: A Systematic Review With Descriptive Synthesis of Clinical Trials. European Journal of Haematology. https://doi.org/10.1111/ejh.70260

Hanna, R., et al. (2026). Translating CRISPR to Practice in the Clinic: Transformative Therapy in Hemoglobinopathies and Emerging Applications in Malignancies. JCO Oncology Practice. https://doi.org/10.1200/OP-26-00479

---

### Claude Response

**Current Evidence on CRISPR-Based Therapies for Sickle Cell Disease**

**Overview**

The clearest and most clinically mature evidence comes from exagamglogene autotemcel (exa-cel, brand name Casgevy) — a one-time, ex vivo CRISPR/Cas9 gene-edited autologous cell therapy developed by CRISPR Therapeutics and Vertex Pharmaceuticals. It edits CD34+ hematopoietic stem and progenitor cells at the erythroid-specific enhancer region of the *BCL11A* gene, disrupting a repressor of fetal hemoglobin (HbF) production. Because HbF doesn't sickle the way adult hemoglobin (HbS) does, reactivating it compensates for the underlying defect without directly correcting the sickle mutation itself.

**Proof of concept (2021)**

The mechanism was first validated in two patients — one with sickle cell disease (SCD), one with transfusion-dependent β-thalassemia — who received autologous CD34+ cells edited with CRISPR-Cas9 targeting the BCL11A erythroid enhancer after myeloablative conditioning, with roughly 80% of alleles modified and no detected off-target editing. More than a year post-infusion, both patients showed high levels of allelic editing, pancellular increases in fetal hemoglobin, transfusion independence, and — in the SCD patient — elimination of vaso-occlusive episodes.

**Pivotal Phase 3 trial and FDA approval (2023–2024)**

The pivotal CLIMB SCD-121 trial enrolled patients aged 12–35 with severe SCD and a history of recurrent vaso-occlusive crises (VOCs). Patients underwent myeloablative conditioning with busulfan before exa-cel infusion, and the primary endpoint was freedom from severe VOCs for at least 12 consecutive months. Results were striking: treatment eliminated vaso-occlusive crises in 97% of patients for a period of 12 months or more. This evidence supported FDA approval of exa-cel in December 2023 — the first CRISPR/Cas9-based therapy to receive FDA approval in any therapeutic area.

**Long-term durability (2025)**

More recent follow-up data (CLIMB SCD-121 completed and ongoing CLIMB-131 extension) reinforce durability: final long-term follow-up results demonstrate durable clinical benefits of exa-cel in patients with sickle cell disease and recurrent vaso-occlusive crises. Independently reported final-results data found 96.7% of patients remained free of vaso-occlusive crises for at least one year, and 100% remained hospitalization-free over the same period.

**Quality of life**

Beyond clinical endpoints, patient-reported outcome data show clinically meaningful improvements in health-related quality of life and reductions in pain in both adults and adolescents across multiple health domains following exa-cel treatment.

**Open questions and limitations**

- **Durability beyond ~2–4 years** is still being tracked via ongoing long-term follow-up (CLIMB-131); very long-term (decade-scale) safety and efficacy data don't yet exist.
- **Treatment burden is substantial**: it requires stem cell mobilization/collection, myeloablative chemotherapy (busulfan), and lengthy hospitalization — a barrier to access, especially outside high-resource settings.
- **Cost and access**: exa-cel is priced in the millions of dollars per patient, raising major questions about equitable global access, particularly since SCD disproportionately affects populations in lower-resource regions (e.g., sub-Saharan Africa, where the disease burden is highest).
- **Off-target editing and long-term oncogenic risk** remain areas of ongoing surveillance, even though no major safety signals have emerged to date.
- exa-cel is not a "gene correction" of the sickle mutation itself, but an indirect workaround (HbF reactivation) — other approaches (e.g., base editing, direct HBB correction) are in earlier-stage trials and not yet part of the approved evidence base.

**References**

Frangoul, H., Altshuler, D., Cappellini, M. D., Chen, Y.-S., Domm, J., Eustace, B. K., Foell, J., de la Fuente, J., Grupp, S., Handgretinger, R., Ho, T. W., Kattamis, A., Kernytsky, A., Lekstrom-Himes, J., Li, A. M., Locatelli, F., Mapara, M. Y., de Montalembert, M., Rondelli, D., Sharma, A., Sheth, S., Soni, S., Steinberg, M. H., Wall, D., Yen, A., & Corbacioglu, S. (2021). CRISPR-Cas9 Gene Editing for Sickle Cell Disease and β-Thalassemia. *New England Journal of Medicine*, 384(3), 252–260. https://doi.org/10.1056/NEJMoa2031054

Frangoul, H., Locatelli, F., Sharma, A., Bhatia, M., Mapara, M., Molinari, L., Wall, D., Liem, R. I., Telfer, P., Shah, A. J., Cappellini, M. D., Kattamis, A., Sheth, S., Neisa, C., Sirken, K., Karen, C., Lucarelli, G., Corbacioglu, S., et al. (2024). Exagamglogene Autotemcel for Severe Sickle Cell Disease. *New England Journal of Medicine*, 390(18), 1649–1662. https://doi.org/10.1056/NEJMoa2309676

Locatelli, F., Lang, P., Wall, D., Meisel, R., Corbacioglu, S., Li, A. M., de la Fuente, J., Shah, A. J., Carpenter, B., Kwiatkowski, J. L., Mapara, M. Y., et al. (2024). Exagamglogene Autotemcel for Transfusion-Dependent β-Thalassemia. *New England Journal of Medicine*, 390(18), 1663–1676. https://doi.org/10.1056/NEJMoa2309673

Grupp, S., Locatelli, F., Sharma, A., Bhatia, M., Mapara, M., Liem, R., Dedeken, L., Molinari, L., Eckrich, M., Kuo, K., Telfer, P., Shah, A., Cavazzana, M., Corbacioglu, S., de Montalembert, M., Lobitz, S., Rondelli, D., Steinberg, M., Walters, M., Boerner, K., Liu, T., Imren, S., Hobbs, W., & Frangoul, H. (2025). Long-term follow-up demonstrates durable clinical benefits of exagamglogene autotemcel for sickle cell disease with recurrent vaso-occlusive crises: Final results of CLIMB SCD-121. *Blood*, 146(Suppl. 1), 2537. https://doi.org/10.1182/blood-2025-2537

Min, J. (2024). Studies of Exagamglogene Autotemcel — Age and Place [Correspondence]. *New England Journal of Medicine*, 391(6), 571–572. https://doi.org/10.1056/NEJMc2407381

---

### ChatGPT Response

wsg bro — current clinical evidence suggests that **CRISPR-based therapies can produce major, potentially durable reductions in sickle-cell disease (SCD) complications**, but the evidence base is still relatively young. The strongest evidence comes from exagamglogene autotemcel (exa-cel), which edits patients' own blood-forming stem cells to increase fetal hemoglobin (HbF). A newer CRISPR-Cas12a approach is also showing promising early clinical results.

**Current evidence**

The first important clinical evidence came from Frangoul et al., who reported CRISPR-Cas9 editing of the **BCL11A erythroid enhancer**. In the early clinical study, treated patients showed substantial increases in fetal hemoglobin and marked reductions in vaso-occlusive events, providing proof of concept that CRISPR editing could produce clinically meaningful effects in SCD.

The evidence became substantially stronger with the phase 3 CLIMB SCD-121 study of **exa-cel**. Among 30 evaluable patients, **29 (97%) remained free of severe vaso-occlusive crises for at least 12 consecutive months**, while all 30 were free of hospitalization for severe vaso-occlusive crises for at least 12 months. Hemoglobin levels and markers of hemolysis also improved. Median follow-up was 19.3 months, although the study remained single-group and relatively small.

Safety is more complicated. The CRISPR editing itself showed no detected off-target editing in the reported specificity analysis, which is reassuring. However, the overall treatment involves stem-cell collection and **myeloablative busulfan conditioning**, so adverse effects such as neutropenia, thrombocytopenia, stomatitis and febrile neutropenia remain important considerations. Thus, not all treatment-related risk comes from CRISPR itself.

Importantly, the field is not limited to Cas9/BCL11A editing. A 2026 NEJM report on **renizgamglogene autogedtemcel (reni-cel)** describes CRISPR-Cas12a editing of the *HBG1/HBG2* promoters. This provides independent evidence that increasing fetal hemoglobin through alternative CRISPR targets can be clinically effective, although it remains an investigational therapy and longer follow-up is needed.

**Overall assessment**

The evidence now supports CRISPR-based therapy as a **genuine disease-modifying, potentially functional-curative approach for severe SCD**, rather than merely a laboratory concept. However, several uncertainties remain: trials have generally involved relatively small and highly selected populations, follow-up is still short compared with the lifelong consequences of genome editing, treatment requires intensive conditioning, and long-term risks—including rare consequences of editing hematopoietic stem cells—require continued surveillance. Reviews of clinical trials likewise emphasize that durability, safety, accessibility and treatment burden remain unresolved questions.

So the clean research takeaway is: **efficacy evidence is now strong enough to demonstrate major clinical benefit, but long-term safety and durability evidence are still developing.**

**References**

Frangoul, H., Altshuler, D., Cappellini, M. D., et al. (2021). CRISPR-Cas9 Gene Editing for Sickle Cell Disease and β-Thalassemia. *New England Journal of Medicine*. https://doi.org/10.1056/NEJMoa2031054

Frangoul, H., Locatelli, F., Sharma, A., et al. (2024). Exagamglogene Autotemcel for Severe Sickle Cell Disease. *New England Journal of Medicine*. https://doi.org/10.1056/NEJMoa2309676

Yen, A., Zappala, Z., Fine, R. S., et al. (2024). Specificity of CRISPR-Cas9 Editing in Exagamglogene Autotemcel. *New England Journal of Medicine*. https://doi.org/10.1056/NEJMc2313119

Hanna, R., Frangoul, H., Pineiro, L., et al. (2026). CRISPR-Cas12a Gene Editing of HBG1 and HBG2 Promoters to Treat Sickle Cell Disease. *New England Journal of Medicine*. https://doi.org/10.1056/NEJMoa2415550

Zarghamian, P., Klermund, J., & Cathomen, T. (2023). Clinical genome editing to treat sickle cell disease—A brief update. *HemaSphere*. https://pubmed.ncbi.nlm.nih.gov/36698803/

---

## Q4: How does the gut microbiome influence neurodegenerative diseases such as Parkinson's and Alzheimer's?

### DeepSeek Response

The current evidence indicates that the gut microbiome influences the pathogenesis of Parkinson's disease (PD) and Alzheimer's disease (AD) through multiple interconnected pathways of the microbiota–gut–brain axis (MGBA). Gut microbial dysbiosis—characterized by reduced short-chain fatty acid (SCFA)-producing bacteria and increased pro-inflammatory, lipopolysaccharide (LPS)-expressing taxa—is consistently observed in both conditions and is mechanistically linked to neuroinflammation, protein misfolding, and neuronal dysfunction.

**Mechanistic Pathways**

In PD, the "gut-first" hypothesis proposes that α-synuclein pathology may originate in the enteric nervous system and propagate to the central nervous system via vagal pathways. Dysbiosis-induced intestinal inflammation, compromised gut barrier integrity, and altered microbial metabolite production (notably SCFAs and LPS) trigger systemic and neuroinflammatory cascades that exacerbate dopaminergic neurodegeneration. A systematic review of mechanistic and translational evidence (11 included studies) confirmed that microbial dysbiosis is associated with reduced SCFA-producing bacteria, increased pro-inflammatory taxa, intestinal barrier disruption, microglial activation, elevated pro-inflammatory cytokines, and α-synuclein aggregation.

In AD, the gut-brain-immune axis is increasingly recognized as a driver of disease progression. Chronic stress activates the HPA axis, causing gut dysbiosis, neuroinflammation, and cognitive decline. Microbiota imbalance lowers SCFAs, disrupts neurotransmitters, and promotes amyloid-beta and tau pathology. Host genetic factors such as APOE4 and TREM2 modulate gut permeability, immune tone, and microbiota profiles, creating a self-reinforcing pathological loop between gut dysfunction and neurodegeneration.

**Shared and Disease-Specific Mechanisms**

A narrative review integrating research on both PD and AD highlights that reductions in SCFA-producing bacteria and increases in LPS-expressing bacteria may drive neuroinflammation and contribute to protein misfolding in both conditions. Proposed mechanisms include systemic inflammation, blood–brain barrier permeability, and neural propagation via the vagus nerve or olfactory bulb. A broader synthesis of the MGBA in neurodegenerative diseases further emphasizes that microbial metabolites—including SCFAs, tryptophan derivatives, and bile acids—interact with host physiology to modulate neuroinflammation, blood–brain barrier integrity, and neuronal homeostasis, with distinct and overlapping pathways across AD, PD, multiple sclerosis, and amyotrophic lateral sclerosis.

**Clinical and Translational Implications**

The evidence supports the potential of microbiota-targeted interventions—including probiotics, prebiotics, fecal microbiota transplantation, and dietary modulation—though clinical trials reveal considerable variability, underscoring the need for personalized approaches and robust biomarkers. Causality remains incompletely established, as most clinical investigations demonstrate associations rather than causal relationships, and the literature is constrained by methodological heterogeneity, limited sample sizes, and a predominance of observational and preclinical studies.

**References**

Alauddin, W., et al. (2026). Gut Microbiota, Neuroinflammation, and Autonomic Dysfunction in Neurodegenerative Diseases: A Systematic Review of Mechanistic and Translational Evidence. Cureus, 18(8), e114312. https://doi.org/10.7759/cureus.114312

Ashraf, G. M., et al. (2025). Gut-brain relationship in dementia and Alzheimer's disease: Impact on stress and immunity. Ageing Research Reviews, 111, 102843. https://doi.org/10.1016/j.arr.2025.102843

Bhattacharjee, A., et al. (2025). Gut-Brain Axis Dysregulation in Parkinson's Disease: Mechanisms Linking Microbiota to Neuroinflammation and α-Synuclein Pathology. Journal of Pharmaceutical Analysis, 101521. https://doi.org/10.1016/j.jpha.2025.101521

Chandra, S., et al. (2025). Gut dysbiosis as a potential driver of Parkinson's and Alzheimer's disease pathogenesis. Frontiers in Neuroscience, 19, 1600148. https://doi.org/10.3389/fnins.2025.1600148

Liu, L., et al. (2025). Microbiota–gut–brain axis in neurodegenerative diseases: molecular mechanisms and therapeutic targets. Molecular Biomedicine, 6, 64. https://doi.org/10.1186/s43556-025-00307-1

---

### Claude Response

**How the Gut Microbiome Influences Neurodegenerative Diseases**

**Core mechanisms**

The gut microbiome is thought to influence Parkinson's disease (PD) and Alzheimer's disease (AD) through several interconnected pathways collectively termed the "microbiota-gut-brain axis":

1. **α-Synuclein misfolding and the "gut-first" hypothesis (PD)**: A substantial body of evidence points to α-synuclein first misfolding in the enteric nervous system, then propagating retrogradely to the central nervous system via the vagus nerve. Gut dysbiosis — altered microbial composition, intestinal inflammation, and compromised gut barrier integrity — appears to be a key driver of this process, and gastrointestinal symptoms (e.g., constipation) often precede motor symptoms by years, supporting the idea that gut pathology may be an early or even initiating event rather than a downstream consequence.

2. **Microbial metabolites and neuroinflammation**: Microbiota-derived molecules such as short-chain fatty acids (SCFAs) and lipopolysaccharides (LPS) can trigger systemic and neuroinflammatory cascades. LPS in particular can increase intestinal and blood-brain barrier permeability, activating microglia and exacerbating neurodegeneration of dopaminergic neurons in PD.

3. **Innate immune signaling (Toll-like receptors)**: Dysbiosis and small intestinal bacterial overgrowth can overstimulate innate immune pathways (notably Toll-like receptors), which may directly contribute to α-synuclein pathology by triggering local and systemic inflammation.

4. **Amyloid-β and tau pathology (AD)**: In Alzheimer's disease, preclinical and clinical studies suggest gut dysbiosis contributes to amyloid-β accumulation and cognitive impairment, potentially via similar mechanisms — increased gut permeability, systemic inflammation, and altered microbial metabolite production affecting amyloid and tau processing. Mouse studies have shown that transferring AD-associated gut microbiota can transmit cognitive deficits, suggesting a causal (not merely correlative) relationship, though this remains an active area of investigation in humans.

5. **The vagus nerve as a communication conduit**: The vagus nerve — the main parasympathetic pathway — can detect microbial metabolites via its afferents and relay this information to the CNS, offering a direct physical route by which gut signals could influence brain physiology and pathology.

**Therapeutic implications**

Because of these mechanisms, gut-microbiome-targeted interventions — dietary modification, prebiotics/probiotics, fecal microbiota transplantation, and targeted bacterial therapies — are being explored as potential disease-modifying or preventive strategies in both PD and AD, though clinical trial evidence for efficacy remains preliminary.

**Caveats**

The field is still working out causation vs. correlation: most human evidence is associational (altered microbial abundance correlates with disease severity), and it's often unclear whether dysbiosis is a cause, a consequence of disease-related lifestyle/dietary changes, or a bidirectional feedback loop. Animal models provide stronger causal evidence, but translation to humans is not yet established.

**References**

Fang, X., et al. (2024). Gut-brain axis dysregulation in Parkinson's disease: Mechanisms linking microbiota to neuroinflammation and α-synuclein pathology. *Journal of Pharmaceutical Analysis*. https://doi.org/10.1016/j.jpha.2025.101360

Klingelhoefer, L., & Reichmann, H. (2023). Gut-microbiome-brain axis: The crosstalk between the vagus nerve, alpha-synuclein and the brain in Parkinson's disease. *Frontiers in Aging Neuroscience / related PD gut-brain review*. https://pubmed.ncbi.nlm.nih.gov/37449597/

Liang, C., Pereira, R., Zhang, Y., & Rojas, O. L. (2024). Gut Microbiome in Alzheimer's Disease: From Mice to Humans. *Current Neuropharmacology*, 22(14), 2314–2329. https://doi.org/10.2174/1570159X22666240308090741

Perez-Pardo, P., Kliest, T., Dodiya, H. B., Broersen, L. M., Garssen, J., Keshavarzian, A., & Kraneveld, A. D. (2018). Microbiome-Gut-Brain Axis and Toll-Like Receptors in Parkinson's Disease. *International Journal of Molecular Sciences*. https://pmc.ncbi.nlm.nih.gov/articles/PMC6032048/

Zhang, S., Lu, J., Jin, Z., Xu, H., Zhang, D., Chen, J., & Wang, J. (2024). Gut microbiota metabolites: Potential therapeutic targets for Alzheimer's disease? *Frontiers in Pharmacology*, 15, 1459655. https://doi.org/10.3389/fphar.2024.1459655

---

### ChatGPT Response

wsg bro — the current evidence suggests that the **gut microbiome can influence neurodegenerative disease through immune, metabolic, and gut–brain signaling pathways**, but researchers have not established that microbiome changes are a single cause of Parkinson's or Alzheimer's disease. Much of the strongest mechanistic evidence still comes from animal and observational human studies.

**Parkinson's disease**

In Parkinson's disease (PD), microbiome alterations have been associated with **intestinal inflammation, increased intestinal permeability, and changes in microbial metabolites**. These changes may influence α-synuclein pathology—the abnormal protein aggregation characteristic of PD—through immune signaling and communication between the gut and nervous system.

A particularly important experimental finding is that transferring microbiota from people with PD into susceptible mice can reproduce aspects of α-synuclein-related pathology and motor dysfunction. This provides stronger causal evidence than simply observing that people with PD have different gut bacteria, although animal results cannot automatically be generalized to humans.

**Alzheimer's disease**

For Alzheimer's disease (AD), studies similarly associate gut dysbiosis with **systemic inflammation, altered microbial metabolites, blood–brain-barrier function, and amyloid-related pathology**. Reduced populations of some short-chain-fatty-acid-producing bacteria and increases in potentially pro-inflammatory organisms have been reported, although the exact microbial signatures vary considerably between studies.

One proposed pathway involves microbial products such as **lipopolysaccharides and short-chain fatty acids**, which can alter immune and inflammatory signaling. These effects could influence microglial activity and the brain environment involved in amyloid and tau pathology. However, researchers are still determining which microbiome changes are causes, consequences, or merely correlates of AD.

**Overall evidence**

The strongest current interpretation is that the microbiome is **a potentially important modifier of neurodegeneration rather than a proven primary cause**. The gut–brain axis provides several plausible mechanisms—microbial metabolites, immune signaling, intestinal permeability, vagal/neuronal pathways, and effects on protein aggregation—but human clinical evidence remains less definitive than the mechanistic evidence from experimental models.

Therefore, microbiome-targeted interventions such as probiotics, dietary modification, or microbiota transplantation remain areas of research rather than established treatments for Parkinson's or Alzheimer's disease. Large, longitudinal human studies and controlled clinical trials are needed to determine whether changing the microbiome can actually prevent or slow neurodegeneration.

**References**

Sampson, T. R., Debelius, J. W., Thron, T., et al. (2016). Gut Microbiota Regulate Motor Deficits and Neuroinflammation in a Model of Parkinson's Disease. Cell. https://doi.org/10.1016/j.cell.2016.11.018

Tan, A. H., Lim, S.-Y., & Lang, A. E. (2022). The microbiome–gut–brain axis in Parkinson disease — from basic research to the clinic. Nature Reviews Neurology. https://doi.org/10.1038/s41582-022-00681-2

Seo, D.-O., & Holtzman, D. M. (2024). Current understanding of the Alzheimer's disease-associated microbiome and therapeutic strategies. Experimental & Molecular Medicine. https://doi.org/10.1038/s12276-023-01146-2

Zhou, X.-P., Sun, L.-B., Liu, W.-H., et al. (2025). The complex relationship between gut microbiota and Alzheimer's disease: A systematic review. Ageing Research Reviews. https://doi.org/10.1016/j.arr.2024.102637

Zhang, Y., et al. (2024). Microbiota–gut–brain axis and its therapeutic applications in neurodegenerative diseases. Signal Transduction and Targeted Therapy. https://doi.org/10.1038/s41392-024-01743-1

---

## Q5: What is the current status of research on high-temperature superconductivity in hydrogen-rich materials?

### DeepSeek Response

The current status of research on high-temperature superconductivity in hydrogen-rich materials is one of extraordinary promise coupled with profound reproducibility and verification challenges. While the field has produced robust evidence for conventional phonon-mediated superconductivity in binary superhydrides like H₃S and LaH₁₀, it has also been shaken by high-profile retractions and persistent controversies that have forced a reckoning with experimental standards. Below is a critical assessment addressing the four required dimensions.

**1. Binary vs. Ternary/Doped Hydrides: Evidence and Reproducibility of Tc**

Binary hydrides (H₃S, LaH₁₀) constitute the evidentiary bedrock of the field. H₃S was the first to demonstrate a critical temperature (Tc) of 203 K at megabar pressures, and LaH₁₀ subsequently achieved a record Tc of approximately 250 K. These results have been reproduced by multiple independent groups, and the superconducting transition in LaH₁₀ has been observed with consistent Tc values (~250 K) despite variations in hydrogen content and synthesis routes. The robustness of these binary systems stems from their relatively well-characterized crystal structures (e.g., the cubic Fm-3m clathrate for LaH₁₀) and the fact that their superconducting properties align with conventional BCS-Eliashberg theory.

Ternary and doped hydrides represent a newer frontier, motivated by the goal of stabilizing high-Tc phases at lower pressures. The ternary hydride LaBeH₈, synthesized at 110–130 GPa, exhibited a maximum Tc of 110 K at 80 GPa—substantially lower than the binary superhydrides but at less extreme conditions. More recently, the ternary system C2/m-(La,Hf)H₁₀ achieved a Tc of 240 K at 162 GPa, with the incorporation of Hf stabilizing a metastable phase and dramatically enhancing the upper critical field to 352 T. Another notable example is the (La,Y)H₁₀ system, which reached 253 K at 183 GPa.

However, the reproducibility of ternary hydride Tc values is considerably weaker than for binaries. Ternary synthesis is highly sensitive to stoichiometry, heating protocols, and the homogeneity of the metal sublattice, and structurally resolved superconducting ternary hydrides remain rare. The observed Tc often varies between synthesis runs, and the precise hydrogen positions are frequently unknown, complicating definitive structural assignment. Thus, while ternary hydrides offer a promising pathway to reduced-pressure superconductivity, their experimental evidence base is less mature and less reproducible than that of the binary archetypes.

**2. Metastability, Synthesis Pressure, and Experimental Techniques**

The superconducting phases in hydrogen-rich materials are typically metastable—they exist only under the high-pressure conditions of synthesis and may decompose or transform upon decompression. This metastability is a double-edged sword: it enables the formation of exotic hydrogen-rich frameworks, but it also makes phase purity and structural characterization extremely difficult. For instance, the C2/m-(La,Hf)H₁₀ phase is metastable and stabilized by Hf doping, distinct from its formation via a structural transition from the cubic phase. Theoretical studies of YSbH₆ suggest that its formation enthalpy decreases at higher pressures, indicating possible metastability and synthesis at similar high-pressure conditions.

Diamond anvil cell (DAC) measurements are the primary experimental platform, but they introduce severe constraints. Samples are micrometer-scale, often inhomogeneous, and may contain multiple coexisting phases, including non-superconducting precursor material. The Van der Pauw four-probe method is commonly used to measure resistance, but in the DAC geometry, the relationship between measured resistance and true sample resistivity is more complicated than typically assumed, and very small measured resistance values do not necessarily indicate superconductivity. Furthermore, the Meissner effect—the definitive signature of superconductivity—is notoriously difficult to measure in DACs due to the tiny sample size and the presence of background magnetic signals. Emerging techniques such as local quantum sensing, which can spatially resolve magnetic responses, are beginning to provide more direct measurements of the Meissner effect, but they are not yet routine.

The combination of metastability, extreme synthesis pressures (typically 100–200 GPa, with some phases requiring 350–400 GPa), and the limitations of DAC-based measurements creates a fundamental verification gap: the evidence for superconductivity often rests on resistance drops and magnetic susceptibility data that are susceptible to alternative explanations.

**3. Reliability of Theoretical Predictions (DFT, Eliashberg Theory)**

Density functional theory (DFT) combined with Migdal–Eliashberg (ME) theory has been remarkably successful in guiding experimental discovery. The prediction of H₃S by Duan et al. in 2014, with a Tc exceeding 200 K, was subsequently confirmed by experiment, establishing the predictive power of the approach. For LaH₁₀, the predicted Tc from ME theory also matched experimental observations reasonably well. More recently, the theory-led synthesis of LaBeH₈ validated the "alloy backbone" concept, though clear discrepancies between theory and experiment in both stabilization range and Tc were noted, attributed to DAC limitations, structural uncertainty, and quantum effects.

However, the reliability of theoretical predictions is regime-dependent and not universally quantitative. In strongly coupled hydrides, the harmonic approximation often fails. For H₃S, standard harmonic treatment predicts a rhombohedral distortion at pressures below 175 GPa, whereas experiments observe a cubic phase; incorporating anharmonicity and nuclear quantum effects restores the correct structure. Non-adiabatic corrections, such as electron–phonon vertex corrections, have been shown to be important for accurate Tc prediction in strongly coupled systems. Furthermore, predictions for ternary hydrides can vary significantly depending on the level of theory: anisotropic Migdal–Eliashberg calculations yield Tc values of 113 K for ThBeH₈ at 7 GPa, while isotropic approximations give Tc ≈ 98 K for the same material at 10 GPa. This sensitivity to methodological choices means that theoretical predictions should be treated as qualitative guides rather than precise quantitative forecasts, particularly for novel ternary compositions.

**4. Key Unresolved Challenges and Controversies**

The field is currently defined by several unresolved challenges and active controversies:

Reproducibility crisis and retractions. The most damaging controversy was the 2020 claim of room-temperature superconductivity at 287 K in a carbonaceous sulfur hydride, which was retracted by Nature in 2022 after concerns about data processing and background subtraction. A subsequent claim of near-ambient superconductivity in N-doped lutetium hydride was also retracted in 2023. A related claim of a yttrium superhydride with Tc up to 262 K was retracted by Physical Review Letters after the majority of co-authors could not locate the raw data. These retractions have severely damaged trust in the field and prompted calls for stricter data-sharing and verification standards.

Verification of superconductivity. Even for the well-established binary hydrides, some researchers argue that the evidence for superconductivity is not compelling and could be explained by alternative mechanisms, such as inhomogeneous current paths or non-superconducting resistance drops. The absence of definitive Meissner effect measurements in many early reports remains a significant weakness.

Pressure and practical applicability. All confirmed high-Tc hydride superconductors require pressures of at least 100–200 GPa, which is far beyond any practical application. The search for superconductivity at near-ambient pressure—through ternary "alloy backbone" design, metastable phases, or chemical doping—remains largely theoretical, with only a few experimental demonstrations at reduced pressures (e.g., LaBeH₈ at 80 GPa). Whether ambient-pressure superconductivity in hydrides is achievable at all is an open question.

Structural ambiguity. In many cases, the precise crystal structure—particularly the hydrogen positions—is not experimentally determined but inferred from theory. This ambiguity makes it difficult to validate theoretical predictions against experiment and to establish structure–property relationships definitively.

Field consensus and funding. Despite the controversies, a group of fifteen prominent condensed matter physicists published a declaration affirming that hydride superconductivity is real and urging continued funding. However, skeptics remain vocal, and the field's credibility is contingent on adopting more rigorous experimental protocols, including independent replication, raw data sharing, and direct Meissner effect measurements.

**References**

Yao, Y., & Carpenter-Bloudoff, M. J. (2026). Hydrogen-rich superconductors under extreme pressure: challenges, progress, and opportunities. Journal of Physics: Condensed Matter, 38(27), 273002. https://doi.org/10.1088/1361-648X/ae7ccd

Hirsch, J. E. (2023). Electrical resistance of hydrides under high pressure: Evidence of superconductivity or confirmation bias? Journal of Superconductivity and Novel Magnetism, 36, 1495–1501. https://doi.org/10.1007/s10948-023-06594-5

Minkov, V. S., et al. (2022). Revaluation of the lower critical field in superconducting H₃S and LaH₁₀. Nature Communications, 13, 3194. https://doi.org/10.1038/s41467-022-30782-x

Song, Y., et al. (2023). Stoichiometric ternary superhydride LaBeH₈ as a new template for high-temperature superconductivity at 110 K under 80 GPa. Physical Review Letters, 130, 266001. https://doi.org/10.1103/PhysRevLett.130.266001

Zhang, Z., et al. (2024). The current status and future development of high-temperature conventional superconductivity. National Science Review, 11(7), nwae047. https://doi.org/10.1093/nsr/nwae047

---

### Claude Response

**High-Temperature Superconductivity in Hydrides: A Critical Assessment**

**1. Binary vs. Ternary/Doped Hydrides: Evidence and Reproducibility**

The field's most credible results come overwhelmingly from **binary hydrides**. H3S, first predicted computationally and then synthesized under megabar pressure, exhibits a superconducting transition around 203 K, with an isotope effect (H→D substitution shifting Tc) consistent with conventional BCS/Eliashberg electron-phonon pairing. LaH10 followed, with a critical temperature in the 250–260 K range, reaching as high as 280 K under thermal cycling that raises pressure. Crucially, these binary results have been **independently reproduced by multiple laboratories** using different synthesis protocols and detection techniques — resistive transitions, magnetic susceptibility (via SQUID magnetometry), trapped-flux measurements, and even nuclear forward scattering — giving reasonably strong, convergent evidence. YH6, YH9, CaH6, CeH9, and CeH10 have similarly been confirmed across independent groups, with crystal structures characterized well enough to allow reliable cross-comparison of results.

**Ternary and doped hydrides are a different story.** The evidence base here is far thinner and far more contested. The two highest-profile claims — carbonaceous sulfur hydride (Dias et al., reporting ~288 K near-room-temperature superconductivity) and nitrogen-doped lutetium hydride (Dias et al., claiming ~294 K at near-ambient pressure) — were **both retracted by Nature** after independent groups failed to replicate the results, raw data was withheld or found to be improperly processed, and specific allegations of data fabrication/manipulation emerged. These episodes represent the most serious reproducibility failures in the field and have cast a shadow over ternary/doped hydride claims generally. Some ternary systems (e.g., La-Y-H alloys, distorted LaH10-based lattices with site substitution) remain under active investigation, but as of now none carry the same weight of independent confirmation as the leading binary hydrides.

**2. Metastability, Synthesis Pressure, and Experimental Validation**

Several experimental factors complicate validation:

- **Extreme pressure requirements**: Binary superhydrides are typically only stable/superconducting above 150–200 GPa — pressures generated exclusively in diamond anvil cells (DACs), where sample volumes are micrometer-scale and highly heterogeneous. This severely limits the diagnostic techniques available and makes reproducibility across labs technically demanding.
- **Metastability and thermal-cycling effects**: Tc has been shown to be sensitive to the exact synthesis history — the pressure at which a sample is laser-heated, the rate and direction of subsequent thermal cycling, and even sample-to-sample variation in stoichiometry or phase purity. This means nominally "the same" compound can show substantially different Tc values depending on synthesis path, complicating comparisons across studies and raising the possibility that some reported enhancements reflect metastable, non-equilibrium phases rather than a single well-defined thermodynamic phase.
- **Multiple detection methods matter**: Because DAC samples are small and background signals (e.g., from the anvils, gasket, or electrode contacts) can contaminate measurements, robust claims require convergent evidence from resistivity drop, magnetic susceptibility (Meissner effect), trapped-flux measurements, and ideally structural characterization (X-ray diffraction) confirming the phase responsible for the transition. The strongest binary-hydride claims (H3S, LaH10, YH6) meet this bar; the retracted ternary claims did not, particularly around magnetic-susceptibility background subtraction, which was the specific point of failure in the CSH controversy.
- **Raw data transparency** has become a central validation issue — the CSH and lutetium hydride retractions both involved disputes over withheld raw data and non-standard, undisclosed background-subtraction procedures.

**3. Reliability of Theoretical Predictions (DFT, Eliashberg Theory)**

Theory has been genuinely predictive in this field, which distinguishes it from many other high-Tc contexts. Density functional theory (DFT) structure searches predicted the stoichiometry and stability of H3S and, independently and near-simultaneously, LaH10 and other superhydrides, before or alongside experimental synthesis — a notable success given that historically most superconductor discoveries (including cuprates) were serendipitous. Eliashberg theory (an extension of BCS accounting for strong electron-phonon coupling) has provided Tc estimates broadly consistent with measured values for the confirmed binary hydrides, and isotope-effect measurements support the conventional electron-phonon pairing mechanism these theories assume.

However, theoretical reliability has limits:

- DFT-based structure prediction is a search over a vast configuration space under extreme pressure, and predicted "optimal" structures don't always match what actually forms experimentally — synthesis kinetics, metastability, and non-equilibrium pathways in the DAC can produce phases theory didn't specifically anticipate.
- Some skeptical analyses of the retracted room-temperature claims noted that the electronic structure would need to show features (e.g., van Hove singularities or similar peaks in the density of states) that were absent in computational screens of thousands of candidate ternary phases — meaning theory, when properly consulted, actually argued *against* some of the room-temperature claims that were later retracted, underscoring both its diagnostic value and the risk of claims proceeding without adequate theoretical vetting.
- Precise Tc prediction (not just qualitative trends) remains difficult; theory is better at flagging promising chemical systems than at forecasting exact transition temperatures.

**4. Key Unresolved Challenges and Controversies**

- **The room-temperature superconductivity scandals**: The Dias-group retractions (carbonaceous sulfur hydride in Nature, 2022; nitrogen-doped lutetium hydride in Nature, 2023; plus a related Physical Review Letters retraction) represent a serious credibility crisis, compounded by allegations of data fabrication and thesis plagiarism. This has made the community substantially more cautious about high-profile, high-Tc claims — especially those made at near-ambient pressure, which would be the most technologically consequential if real.
- **Practical inapplicability**: Even the well-confirmed binary hydrides require pressures of ~150–200 GPa, sustainable only in micrometer-scale DAC samples — nowhere near viable for real-world applications like power transmission. A central open question is whether any hydride can be stabilized at high Tc and near-ambient pressure simultaneously.
- **Reproducibility standards**: The field is still converging on what counts as sufficient independent validation — how many labs, which techniques, and what data-transparency norms should be required before a claim is accepted, especially post-Dias.
- **Structure/stoichiometry ambiguity**: For many superhydrides, precisely resolving the crystal structure and hydrogen content responsible for observed transitions remains technically challenging given DAC sample constraints, leaving some reported Tc values without fully confirmed structural assignments.
- **Ternary/quaternary chemical space**: Theoretically, doping or alloying binary hydrides could in principle reduce the pressure needed to stabilize high-Tc phases, but experimental progress here lags far behind computational proposals, and the field's most prominent ternary claims have so far failed replication.

**References**

Snider, E., Dasenbrock-Gammon, N., McBride, R., Debessai, M., Vindana, H., Vencatasamy, K., Lawler, K. V., Salamat, A., & Dias, R. P. (2020). Room-temperature superconductivity in a carbonaceous sulfur hydride. *Nature*, 586, 373–377. (Retracted 2022). https://doi.org/10.1038/s41586-020-2801-z

Drozdov, A. P., Kong, P. P., Minkov, V. S., Besedin, S. P., Kuzovnikov, M. A., Mozaffari, S., Balicas, L., Balakirev, F. F., Graf, D. E., Prakapenka, V. B., Greenberg, E., Knyazev, D. A., Tkacz, M., & Eremets, M. I. (2019). Superconductivity at 250 K in lanthanum hydride under high pressures. *Nature*, 569, 528–531. https://doi.org/10.1038/s41586-019-1201-8

Drozdov, A. P., Eremets, M. I., Troyan, I. A., Ksenofontov, V., & Shylin, S. I. (2015). Conventional superconductivity at 203 kelvin at high pressures in the sulfur hydride system. *Nature*, 525, 73–76. https://doi.org/10.1038/nature14964

Minkov, V. S., Ksenofontov, V., Bud'ko, S. L., Talantsev, E. F., & Eremets, M. I. (2022). Magnetic field screening in hydrogen-rich high-temperature superconductors. *Nature Communications*, 13, 3194. https://doi.org/10.1038/s41467-022-30782-x

Hirsch, J. E., & Marsiglio, F. (2022). Nonstandard superconductivity or no superconductivity in hydrides under high pressure. *Physical Review B*, 106, 214511. https://doi.org/10.1103/PhysRevB.106.214511

---

### ChatGPT Response

wsg bro — the evidence for high-Tc superconductivity in hydrogen-rich hydrides is now **substantial for several binary systems, especially H3S and LaH10**, but the field is much less mature for ternary/multinary materials. The central scientific picture is that hydrogen's light mass produces very high phonon frequencies, while chemical precompression from heavier elements makes hydrogen-rich metallic phases accessible at pressures achievable in diamond-anvil cells (DACs). The strongest evidence comes from the convergence of electrical transport, magnetic measurements, isotope effects, structural characterization, and theory.

**1. Binary versus ternary/doped hydrides**

**Binary hydrides have the strongest experimental case.** H3S was reported at Tc ≈ 203 K around 150–160 GPa, with zero resistance, suppression of Tc by magnetic field, an isotope effect, and magnetic susceptibility evidence. Subsequent structural and spectroscopic work has made the assignment to the high-pressure H3S phase substantially more convincing.

LaH10 provides an even higher-Tc example: approximately **250 K near 170 GPa** was reported, with later work connecting the superconducting state to the Fm3m LaH10 structure. Importantly, recent long-term measurements report transitions around 250 K even many months after synthesis, strengthening the case that the phenomenon is reproducible within a controlled sample.

Ternary and doped hydrides offer **much greater chemical design space**, potentially allowing pressure reduction or tuning of electronic structure. But their experimental evidence is generally less mature. For example, LaB2H8 has been experimentally synthesized with reported superconductivity around 106 K at 90 GPa, while many other ternary compounds remain theoretical predictions rather than experimentally established superconductors.

Thus, it would be misleading to treat a predicted ternary Tc of 200–300 K as equivalent evidence to experimentally reproduced H3S or LaH10. Theoretical ternary candidates are abundant; experimentally validated high-Tc ternaries are comparatively scarce.

**2. Metastability, pressure and DAC measurements**

A major complication is that these materials are **not necessarily the equilibrium phase expected from their starting composition**. Compression, laser heating, annealing, and decompression can move the sample between competing structures. H3S, for example, can form through pressure-induced chemistry of initially loaded H2S, meaning the material actually measured is not necessarily identical to the starting material.

Metastability can therefore be both useful and problematic. A metastable hydrogen-rich structure may survive after synthesis and exhibit a high Tc, but identifying exactly which phase is carrying the current is difficult when the sample is microscopic and contains multiple phases.

DAC experiments make this particularly challenging. Samples are typically only tens of micrometres across, while pressures exceed 100 GPa. Consequently, resistance measurements are experimentally demanding and magnetic measurements are difficult. This is why **zero resistance alone is not considered sufficient proof**. Magnetic-field dependence, magnetic screening, isotope effects, and preferably X-ray diffraction identifying the relevant phase provide important independent checks.

Recent long-term LaH10 measurements are especially relevant to reproducibility: the same samples have reportedly retained approximately 250-K transitions for years, with X-ray diffraction confirming persistence of the relevant phase. This considerably strengthens the reproducibility case for LaH10.

**3. How reliable are DFT and Eliashberg predictions?**

Theory has been **remarkably successful as a discovery guide**. Density-functional structure searches identified hydrogen-rich structures before or alongside their experimental discovery, while electron–phonon calculations using Migdal–Eliashberg theory successfully predicted high Tc values for systems such as H3S. The experimental discovery of ~203-K superconductivity therefore represents a notable theory–experiment success rather than a purely empirical discovery.

However, theoretical Tc predictions are not infallible. They depend on the assumed crystal structure, pressure, stoichiometry, anharmonicity, electron–phonon coupling, and treatment of quantum nuclear motion. Structure searches can also identify **metastable phases that may or may not actually form experimentally**.

The problem becomes particularly serious for ternary systems because their compositional and structural configuration space is enormous. Computational studies have found candidate metastable ternaries, but some predicted Tc values have not matched experimental reports, demonstrating that thermodynamic plausibility and calculated superconductivity do not by themselves establish that a particular phase exists in the DAC.

So DFT/Eliashberg theory is best viewed as a **highly effective hypothesis generator and prioritization tool**, rather than experimental confirmation.

**4. Key unresolved challenges and controversies**

Several issues remain central:

- **Phase identification:** determining exactly which hydrogen-rich phase produces the observed superconductivity, particularly in multiphase DAC samples.
- **Reproducibility:** binary systems such as H3S and LaH10 have much stronger evidence than many newer ternary claims, but synthesis history and pressure calibration can strongly affect results.
- **Magnetic confirmation:** electrical resistance is easier to measure than Meissner screening under megabar pressures. Improved high-pressure magnetometry has strengthened the evidence, but measurements remain technically difficult.
- **Pressure:** most spectacular Tc values require roughly 100–200+ GPa, making practical applications extremely remote.
- **Metastability and kinetics:** a phase predicted to be favorable thermodynamically may not form, while a metastable phase may form only under particular heating and compression histories.
- **Theory limitations:** standard electron–phonon calculations work impressively well for established systems but require increasingly careful treatment of anharmonicity, nuclear quantum effects, structural instability, and competing phases.
- **Extraordinary claims:** proposed room-temperature or unusually high-Tc ternary systems require particularly strong structural, transport, and magnetic evidence because a resistance anomaly by itself can have alternative explanations. There has also been published criticism arguing that some hydride observations are inconsistent with conventional superconductivity; these objections remain part of the scientific debate rather than an established replacement for the conventional electron–phonon interpretation.

**Bottom line**

The **binary-hydride case is considerably stronger than the general ternary-hydride case**. H3S and LaH10 have multiple mutually reinforcing experimental signatures and broadly successful theoretical descriptions. Ternary hydrides are scientifically promising because they provide additional chemical freedom, but many high-Tc predictions remain predictions rather than independently reproduced experimental results.

The field's biggest next step is therefore not simply finding a larger calculated Tc. It is obtaining **unambiguous phase identification + reproducible zero resistance + magnetic evidence + agreement with first-principles calculations**, preferably at substantially lower pressure.

**References**

Drozdov, A. P., Eremets, M. I., Troyan, I. A., Ksenofontov, V., & Shylin, S. I. (2015). Conventional superconductivity at 203 kelvin at high pressures in the sulfur hydride system. Nature. https://doi.org/10.1038/nature14964

Drozdov, A. P., Kong, P. P., Minkov, V. S., et al. (2019). Superconductivity at 250 K in lanthanum hydride under high pressures. Nature. https://doi.org/10.1038/s41586-019-1201-8

Errea, I., Belli, F., Monacelli, L., et al. (2020). Quantum hydrogen-bond symmetrization in the superconducting hydrogen sulfide system. Nature. https://doi.org/10.1038/s41586-020-1955-z

Sun, Y., Tian, Y., Jiang, B., et al. (2021). High-temperature superconductivity on the verge of a structural instability in lanthanum superhydride. Nature Communications. https://doi.org/10.1038/s41467-021-26706-w

Bianconi, A., & Jarlborg, T. (2021). Superconductivity above 100 K in MgB2-type structures and in hydrogen-rich compounds. Journal of Superconductivity and Novel Magnetism. https://doi.org/10.1007/s10948-021-05995-0
