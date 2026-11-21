# Literature Review: Diagnostic and Prognostic Potential of Long Non-Coding RNAs (lncRNAs) in Human Pathologies

![Diagnostic and Prognostic Potential of Long Non-Coding RNAs](Diagnostic%20and%20Prognostic%20Potential%20of%20Long%20Non-Coding%20RNAs%20(IncRNAs)%20in%20Human%20Pathologies.jpg)

**Author:** Mashiur Rahman  
**Context:** Research Assistant (RA) Literature Synthesis — North South University (NSU)  
**Scope:** Comparative molecular synthesis evaluating circulating plasma lncRNA diagnostic panels in acute/early HIV-1 infection (Biswas et al., 2024) versus tissue-based lncRNA–ceRNA regulatory networks in colorectal cancer (Khajehdehi et al., 2022).

---

## 1. Introduction & Regulatory Role of lncRNAs
Non-coding RNAs constitute nearly 99% of the human transcriptome, among which **long non-coding RNAs (lncRNAs)**—transcripts exceeding $200\ \text{nucleotides}$ without protein-coding potential—function as master regulators of gene expression at the transcriptional, post-transcriptional, and epigenetic levels (Khajehdehi et al., 2022; Biswas et al., 2024). Subcellularly, lncRNAs operate either as nuclear chromatin-remodeling scaffolds or as cytoplasmic **competing endogenous RNAs (ceRNAs)** that sequester microRNAs (miRNAs) to derepress target mRNAs (Khajehdehi et al., 2022). Because their dysregulation drives key pathological processes—including cellular proliferation, apoptosis evasion, immune modulation, and viral replication—profiling aberrant lncRNA signatures has emerged as a promising strategy for early disease detection and therapeutic monitoring across both oncological and infectious diseases.

---

## 2. Multi-Marker Circulating lncRNA Panels in Infectious Disease: Acute/Early HIV-1 Detection
Early diagnosis of Human Immunodeficiency Virus-1 (**HIV-1**) is critical to curbing transmission, as viral loads peak during the acute phase ($>1\times 10^7\ \text{copies/mL}$) before anti-HIV-1 antibodies become detectable (Biswas et al., 2024). Conventional 3rd- and 4th-generation immunoassays fail during this seronegative window, and even Nucleic Acid Testing (NAT) misses infections during the initial **eclipse stage**, when viral RNA remains below detection thresholds (Biswas et al., 2024). Addressing the limitations of earlier single-marker peripheral blood mononuclear cell (PBMC) studies (e.g., `NRON`, `NEAT1`), Biswas et al. (2024) evaluated extracellular circulating lncRNAs across $172$ plasma samples spanning eclipse, acute, post-seroconversion (p31-negative and p31-positive), and antiretroviral therapy (ART)-treated stages.

Using a four-phase workflow (*Discovery* via Qiagen $\text{RT}^2$ lncRNA PCR Array screening 84 lncRNAs, *Validation* via qRT-PCR normalized to `RPLP0` and `RN7SK`, *Logistic Regression Panel Development*, and *Independent Blinded Testing*), Biswas et al. (2024) established that multi-marker combinations substantially outperform individual lncRNAs:

* **Pan-HIV-1 Detection ($P_{\text{model-I}}$):** An eight-lncRNA signature (`DISC2`, `H19`, `IPW`, `KRASP1`, `NEAT1`, `PRINS`, `WT1-AS`, and `ZFAS1`) distinguished HIV-1 infection from uninfected controls with an Area Under the ROC Curve (**AUC**) of $0.990$ ($98.75\%$ sensitivity, $95\%$ specificity) in the validation cohort and $96.88\%$ accuracy ($100\%$ sensitivity, $91.67\%$ specificity) in independent blinded testing.
* **Stage-Specific Discrimination:** Sub-panels tailored to specific infection phases—$P_{\text{model-II}}$ (`DISC2`, `GACAT1`, `H19`, `NEAT1`) for the eclipse stage and $P_{\text{model-III}}$ (`FTX`, `GACAT1`, `H19`, `NEAT1`, `PRINS`) for the acute stage—achieved $100\%$ sensitivity and $100\%$ specificity ($\text{AUC} = 1.00$) in validation, and $94.12\%$ and $100\%$ accuracy in independent testing, respectively.
* **Prognostic Monitoring Under ART:** Following at least 12 weeks of ART and viral suppression ($<100\ \text{copies/mL}$), the dysregulated expression levels of the eight-lncRNA panel reverted toward healthy baseline levels, demonstrating utility for monitoring therapeutic efficacy (Biswas et al., 2024).

---

## 3. Tissue-Based lncRNA Profiling and ceRNA Networks in Oncology: Colorectal Cancer
In oncology, delayed diagnosis and metastasis remain primary drivers of mortality in **colorectal cancer (CRC)**, highlighting the need for molecular biomarkers capable of differentiating benign precursor lesions from malignant tumors (Khajehdehi et al., 2022). Investigating $160$ paired fresh tissue biopsies (50 CRC tumors, 30 adenomatous colorectal polyps [ACP], and their adjacent non-tumor margins), Khajehdehi et al. (2022) profiled 90 cancer-related lncRNAs using the SBI Human LncProfiler qPCR Array followed by qRT-PCR validation normalized against `RNU6`.

Three lncRNAs upregulated in exploratory Stage III tumor screening—`HAR1B`, `JPX`, and `KRASP1`—were evaluated in the validation cohort:

* **Diagnostic Biomarker Potential (`JPX` and `HAR1B`):** Both `JPX` and `HAR1B` were significantly overexpressed in CRC tissues compared to adjacent margins (~7-fold increase) and benign ACP lesions (18-fold and 9.7-fold increases, respectively). ROC analyses showed that `JPX` and `HAR1B` discriminated CRC from ACP with AUCs of $\approx 0.70$ (sensitivity: $73.3\%$, specificity: $86.6\%$ for `JPX`; sensitivity: $73.3\%$, specificity: $80\%$ for `HAR1B`), supporting their role as indicators of malignant progression (Khajehdehi et al., 2022).
* **Cohort Validation Filtering (`KRASP1`):** Despite initial upregulation in exploratory screening, `KRASP1` displayed a statistically non-significant downregulation in the larger CRC validation cohort ($p = 0.163$), illustrating the necessity of large-scale validation to exclude false-positive candidates (Khajehdehi et al., 2022).
* **Functional ceRNA Pathway Enrichment:** Through *in silico* interaction modeling (DIANA LncBase, miRWalk2, TargetScan) and KEGG enrichment analysis (DAVID), Khajehdehi et al. (2022) demonstrated that `HAR1B` and `JPX` sponge seven and three tumor-suppressor miRNAs, respectively, promoting CRC pathogenesis via the canonical **Wnt/$\beta$-catenin**, **ErbB**, and **FoxO** signaling pathways, alongside apoptosis regulation and focal adhesion.

---

## 4. Comparative Synthesis & Critical Research Gaps

| Analytical Dimension | Khajehdehi et al. (2022) | Biswas et al. (2024) |
| :--- | :--- | :--- |
| **Pathological Focus** | Colorectal Cancer (CRC) & Adenomatous Polyps (ACP) | Acute & Early-Stage HIV-1 Infection (Eclipse to Post-Seroconversion) |
| **Sample Matrix & Cohort** | Invasive fresh tissue biopsies ($n = 160$ paired samples) | Minimally invasive blood plasma ($n = 172$ samples across 4 phases) |
| **Discovery Array** | SBI Human LncProfiler qPCR Array (90 lncRNAs) | Qiagen $\text{RT}^2$ lncRNA PCR Array Human lncFinder (84 lncRNAs) |
| **Modeling Approach** | Single-biomarker ROC evaluation (`HAR1B`, `JPX`) | Multi-marker logistic regression panels ($P_{\text{model-I}}$ to $P_{\text{model-VI}}$) |
| **Diagnostic Performance** | Moderate standalone accuracy ($\text{AUC} \approx 0.63\text{–}0.70$; Sens: $66\text{–}74\%$) | High multi-panel accuracy ($\text{AUC} = 0.99\text{–}1.00$; Sens: $98.3\text{–}100\%$) |
| **Behavior of `KRASP1`** | Overexpressed in discovery; non-significant in validation ($p = 0.163$) | Upregulated across HIV-1 stages; retained in $P_{\text{model-I}}$ & $P_{\text{model-V}}$ |
| **Mechanistic Investigation** | **High** — mapped lncRNA–miRNA–mRNA ceRNA networks & KEGG pathways | **Low** — focused on diagnostic/prognostic modeling without pathway analysis |

### Synthesized Insights & Gaps in Current Literature
1. **Multi-Marker Panels Outperform Single Biomarkers:** Evaluating individual lncRNAs yields moderate diagnostic separation ($\text{AUC} \approx 0.70$ in Khajehdehi et al., 2022), whereas combining multiple weighted lncRNAs via logistic regression captures complex disease heterogeneity and achieves near-perfect sensitivity and specificity ($\text{AUC}\ 0.99\text{–}1.00$ in Biswas et al., 2024).
2. **Liquid Biopsy vs. Tissue Profiling:** Tissue biopsies (Khajehdehi et al., 2022) directly capture local pathway perturbations (`Wnt/β-catenin`, `ErbB`, `FoxO`), whereas circulating plasma lncRNAs (Biswas et al., 2024) provide a minimally invasive liquid biopsy platform suitable for early window-period screening and longitudinal treatment monitoring.
3. **Methodological & Functional Gaps:** Both studies interrogated fewer than 100 pre-selected lncRNAs out of over 127,000 annotated human lncRNA transcripts (LNCipedia). Moreover, neither study bridged diagnostic panel modeling with downstream functional validation—Khajehdehi et al. (2022) relied on *in silico* pathway predictions without multi-marker modeling, while Biswas et al. (2024) validated multi-marker diagnostic panels without characterizing their host molecular signaling pathways. Future translational research should integrate unbiased transcriptome-wide screening, multi-lncRNA predictive modeling, and experimental pathway validation.

---

## 5. References
* Biswas, S., Nagarajan, N., Hewlett, I., & Devadas, K. (2024). Identification of a circulating long noncoding RNA signature panel in plasma as a novel biomarker for the detection of acute/early-stage HIV-1 infection. *Biomarker Research*, 12(1), 61. https://doi.org/10.1186/s40364-024-00597-7
* Khajehdehi, M., Khalaj-Kondori, M., & Hosseinpour Feizi, M. A. (2022). Expression profiling of cancer-related long non-coding RNAs revealed upregulation and biomarker potential of HAR1B and JPX in colorectal cancer. *Molecular Biology Reports*, 49(7), 6075–6084. https://doi.org/10.1007/s11033-022-07396-z
