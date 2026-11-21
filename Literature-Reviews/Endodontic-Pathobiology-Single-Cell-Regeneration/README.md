# Molecular Pathobiology, Single-Cell Dynamics, and Precision Regenerative Strategies in Endodontics: A Comprehensive Literature Review

![Molecular Pathobiology, Single-Cell Dynamics & Precision Endodontics](Molecular%20Pathobiology%2C%20Single-Cell%20Dynamics%20%26%20Precision%20Endodontics.jpg)

**Author:** Mashiur Rahman  
**Context:** Research Assistant (RA) Literature Synthesis — North South University (NSU)  
**Scope:** Integrative synthesis of five peer-reviewed studies (2026) spanning pulpal/periapical proteomics, ferroptosis, SIBLING extracellular matrix mineralization, single-cell odontogenesis, and noncoding RNA (ncRNA) exosomal therapeutics.

---

## 1. Introduction
Pulpal and periapical diseases—spanning reversible pulpitis, irreversible pulpitis, pulp necrosis, and acute or chronic apical periodontitis (AP)—stem from complex interactions between polymicrobial root canal biofilms, host immune cascades, and the anatomical confinement of the dentin–pulp complex (Rai et al., 2026; Parviainen et al., 2026). While conventional nonsurgical root canal treatment (RCT) effectively eliminates microbial infection and promotes periapical healing, it replaces vital tissue with inert obturation materials, failing to restore physiological pulp immunity, sensory innervation, or continued root maturation (Pandey & Kharche, 2026; Liao et al., 2026). Furthermore, clinical diagnostics remain heavily reliant on subjective symptom assessment, sensibility testing, and two-dimensional radiography, which cannot reliably distinguish reversible from irreversible pulpal inflammation or predict post-treatment healing outcomes (Rai et al., 2026).

Recent breakthroughs in high-throughput multi-omics—specifically mass spectrometry-based proteomics, single-cell RNA sequencing (scRNA-seq), spatial transcriptomics, and noncoding RNA (ncRNA) profiling—have begun bridging the gap between molecular pathogenesis and precision regenerative endodontics (Liao et al., 2026; Pandey & Kharche, 2026). This literature review synthesizes five contemporary studies (published in 2026) to establish an integrated molecular framework spanning tissue destruction, regulated cell death, biomineralization, and stem cell-driven regeneration.

---

## 2. Proteomic Signatures & Host–Pathogen Dynamics in Endodontic Disease
Mass spectrometry-based proteomics directly interrogates functional protein effectors across biological specimens—including dental pulp tissue, dentinal fluid, root canal exudates, and periapical biopsies (Rai et al., 2026). In a PRISMA-guided systematic review of 11 human proteomic studies ($n = 577$ participants) employing LC-MS/MS, MALDI-TOF MS, and 2D-DIGE, Rai et al. (2026) identified over 1,800 human proteins and 720 microbial proteins across the endodontic disease spectrum:

* **Pulpitis Progression to Necrosis:**
  * **Hornerin (HRN):** Emerged as a novel, stage-dependent biomarker in dentinal fluid that escalates with pulpitis severity, offering strong potential as a chairside diagnostic indicator to differentiate reversible from irreversible pulpitis.
  * **Vascular & Oxidative Stress Markers:** Inflamed pulp exhibits a 100-fold upregulation of hemoglobin subunits (reflecting vascular disruption and extravasation), a 20-fold increase in antioxidant peroxiredoxins (`PRDX1`, `PRDX2`), and marked elevation of calprotectin subunits (`S100-A8`/`S100-A9`) driven by neutrophil infiltration.
  * **Necrotic Transition:** Progression to necrosis is marked by the depletion of metabolic enzymes and cytoskeletal proteins (tubulin isoforms, desmin) alongside the accumulation of keratins and proteolytic degradation products.
* **Symptomatic vs. Stable Apical Periodontitis:**
  * **Acute/Symptomatic AP:** Characterized by elevated myeloperoxidase (`MPO`)—which generates hypochlorous acid that directly sensitizes nociceptors—alongside `S100-A8`, lactotransferrin, and alpha-1-antitrypsin, accompanied by a depletion of neutrophil defensins 1 and 3 due to bacterial proteolysis.
  * **Chronic/Stable Lesions:** Exhibits significant upregulation of heat shock protein 27 (`HSP27`; 3.79-fold) and `SERPINB1` (1.93-fold), which inhibit apoptosis and neutralize neutrophil-derived serine proteases (elastase, cathepsin G), promoting lesion containment.
* **Post-Treatment Disease & Metaproteomics:**
  * Persistent endodontic infections harbor synergistic polymicrobial communities dominated by *Enterococcus faecalis*, *Porphyromonas gingivalis*, *Fusobacterium nucleatum*, and *Tannerella forsythia*.
  * Microbial virulence proteins—including *E. faecalis* adhesins (`Ace`, `EfaA`), gelatinase (`GelE`), and cytolysin (`CylA`), alongside *P. gingivalis* gingipains—degrade host complement proteins and neutrophil extracellular traps (NETs).
  * Detection of antimicrobial resistance proteins (`TetM`, `VanSG2`, beta-lactamases) provides molecular validation for the limited efficacy of systemic antibiotics, while host expression of the BMP antagonist **Gremlin-1** explains persistent periapical osteolysis (Rai et al., 2026).

---

## 3. Regulated Cell Death Networks: Emerging Role of Ferroptosis
Beyond inflammasome-driven pyroptosis (caspases-1/-4/-5, gasdermin D, and IL-1$\beta$) and apoptosis (Rai et al., 2026), **ferroptosis**—an iron-dependent, non-apoptotic form of regulated cell death driven by phospholipid peroxidation—has emerged as a key pathogenic contributor in endodontic inflammation (Parviainen et al., 2026).

Because the dental pulp is encased within a rigid dentin chamber, inflammatory vasodilation and edema rapidly induce focal ischemia, hypoxia, labile ferrous iron ($\text{Fe}^{2+}$) accumulation, and reactive oxygen species (ROS) overload—creating a microenvironment highly susceptible to ferroptotic injury (Parviainen et al., 2026):

* **Ferroptosis in Active Pulpitis:**
  * Single-cell transcriptomic and biochemical analyses of human pulpitis confirm elevated $\text{Fe}^{2+}$, lipid ROS, and prostaglandin-endoperoxide synthase 2 (`PTGS2`), accompanied by suppression of the classical cystine/glutamate antiporter (`SLC7A11`)–glutathione–`GPX4` antioxidant defense axis.
  * **Dental Pulp Fibroblasts:** Lipopolysaccharide (LPS) triggers `ZBP1`/`NLRP3`-mediated PANoptosis and ferroptosis, amplifying IL-1$\beta$ and IL-6 secretion.
  * **Dental Pulp Stem Cells (DPSCs):** Activation of the `TREM1`/`DRP1`–`cGAS-STING` pathway induces mitochondrial stress and ferroptosis, directly impairing odontoblastic differentiation and reparative dentinogenesis.
* **Macrophage Ferroptosis in Apical Periodontitis:**
  * In chronic AP lesions, ferroptosis localizes predominantly to infiltrating macrophages, driven by `JNK`/`JUN`/`NCOA4`-mediated ferritinophagy and loss of `NRF2`/`FSP1` antioxidant protection.
  * Ferroptotic macrophages release TNF-$\alpha$ and ROS in an autocrine–paracrine loop that suppresses osteogenic differentiation in bone marrow stromal cells and accelerates osteoclastic bone resorption.
* **Therapeutic & Antimicrobial Modulation:**
  * Preclinical interventions using radical-trapping agents (**liproxstatin-1**), **thymosin $\alpha 1$**, or `JNK` inhibitors restore `GPX4`/`SLC7A11` expression and attenuate periapical bone loss.
  * Conversely, inducing ferroptosis-like cell death selectively in *E. faecalis* biofilms using Prussian blue-loaded mesoporous calcium-silicate nanoparticles represents a promising antimicrobial root canal disinfection strategy (Parviainen et al., 2026).

---

## 4. Extracellular Matrix Mineralization & Bone Remodeling (BSP/SIBLING Axis)
Effective regeneration of dentin and periapical bone relies on extracellular matrix (ECM) proteins capable of nucleating hydroxyapatite (HA) and orchestrating cell–matrix signaling. **Bone sialoprotein (BSP/`IBSP`)**, a core member of the SIBLING (*Small Integrin-Binding Ligand, N-linked Glycoprotein*) family alongside osteopontin (`OPN`), `DMP-1`, and `DSPP`, serves as a master regulator of mineralized tissue remodeling (Kottmann et al., 2026).

* **Structural Architecture & Post-Translational Modifications (PTMs):**
  * Encoded by the `IBSP` gene on human chromosome 4q21.1, native BSP has a core mass of $33.6\ \text{kDa}$ that increases to $70\text{–}80\ \text{kDa}$ following extensive PTMs (*N*/*O*-linked glycosylation, serine/threonine phosphorylation, and tyrosine sulfation).
  * Its N-terminal and central domains house collagen-binding motifs and polyglutamic acid-rich sequences that nucleate HA crystals, while its conserved C-terminal **Arg-Gly-Asp (RGD)** motif binds cell-surface integrins (predominantly $\alpha\text{v}\beta 3$ and $\alpha\text{v}\beta 5$).
* **Dual Role in Bone Formation vs. Resorption:**
  * **Osteogenesis & Mineralization:** Unlike `OPN`—which inhibits HA crystal growth and drives disuse-induced resorption—BSP is essential for late-stage osteoblast differentiation, matrix mineralization, and cortical bone regeneration via `ERK1/2` (MAPK) and `PI3K/Akt` signaling (upregulating `Runx2`, `Osterix`, `ALP`, and `OCN`).
  * **Angiogenic–Osteogenic Coupling:** Through RGD–$\alpha\text{v}\beta 3$ binding and `MMP-2` activation, BSP promotes endothelial migration and neovascularization alongside bone formation.
  * **Osteoclast Synergy:** In a context-dependent manner, BSP synergizes with `RANKL` via calcium/calcineurin/`NFATc1` and $\alpha\text{v}\beta 3$–`Src` pathways to promote osteoclast differentiation and resorption pit formation. *(Note: Outside physiological remodeling, aberrant BSP overexpression in osteotropic malignancies—such as breast, prostate, and lung cancers—drives skeletal metastasis via `FAK/Src` signaling, `MMP-14`-mediated EMT, and Factor H-dependent complement evasion; Kottmann et al., 2026).*

---

## 5. Single-Cell Resolution of Odontogenesis & Tissue Engineering
Conventional bulk transcriptomics obscures cellular heterogeneity during tooth organogenesis. Recent scRNA-seq and spatial transcriptomic atlases of embryonic and postnatal dental tissues have decoded the lineage hierarchies and epithelial–mesenchymal crosstalk required for whole-tooth and partial tissue regeneration (Liao et al., 2026):

* **Epithelial Hierarchies & Enamel Regeneration:**
  * Single-cell profiling of human fetal tooth germs (9–24 gestational weeks) identified 13 epithelial subpopulations, establishing the **enamel knot (EK)** as the primary signaling center secreting `SHH`, `WNT10A`, and `WNT10B`. Canonical WNT signaling induces the transcription factor `SP6`, which translocates to the nucleus to activate ameloblast matrix genes (`AMELX`, `AMBN`).
  * Unlike continuously growing mouse incisors—which retain a lifelong `Sox2+`/`Lgr5+` cervical loop stem cell niche—human teeth lose their `LGR6+` cervical loop niche postnatally, precluding natural enamel repair.
  * Guided by single-cell signaling cues, human iPSC-derived ameloblast organoids and elastin-like recombinamer biomimetic matrices have successfully directed epitaxial fluorapatite nanocrystal growth that replicates the prismatic architecture and mechanical hardness of native enamel.
* **Mesenchymal Progenitors for Pulp–Dentin & Periodontal Regeneration:**
  * Within human dental mesenchyme (`PRRX1+` ectomesenchyme), sequential **WNT** (early specification) followed by **NOTCH** (late maturation) signaling directs `DLX6-AS1+` dental papilla (DP) progenitors to form well-organized, tubular dentin *in vivo*.
  * Three-dimensional spheroid cultures of `Cd24a+` multipotent dental pulp regenerative stem cells (MDPSCs) regenerate vascularized and innervated pulp–dentin complexes, while postnatal human `DIO2+` DP subpopulations exhibit potent osteogenic potential.
  * In the periodontium, postnatal human `SPARC+`/`POSTN+` and `PDGFRA+` dental follicle stem cells (DFSCs)—regulated by endothelial `PDGF-BB` signaling and murine `Gli1+`/`Lepr+`/`PTHrP+` progenitors—couple `CD31+`/`EMCN+` angiogenesis with cementum, periodontal ligament, and alveolar bone regeneration (Liao et al., 2026).

---

## 6. Noncoding RNA Networks & Cell-Free Translational Platforms
Upstream of protein translation, noncoding RNAs (**ncRNAs**)—including microRNAs (miRNAs), long noncoding RNAs (lncRNAs), and circular RNAs (circRNAs)—function as master epigenetic, transcriptional, and post-transcriptional regulators governing DPSC differentiation, immunomodulation, and neurovascular coupling (Pandey & Kharche, 2026):

* **Competing Endogenous RNA (ceRNA) Circuits in Odontogenesis:**
  * lncRNAs and exonuclease-resistant circRNAs act as molecular sponges that sequester inhibitory miRNAs (`hsa-miR-140-5p`, `miR-143`, `miR-218`) to activate pro-odontogenic signaling.
  * Specifically, `lncRNA H19` sponges `miR-140-5p` to activate the `BMP-2`/`FGF9` axis, while `lncRNA SNHG1` and `SNHG7` stimulate `Wnt/β-catenin`, `PI3K-Akt`, and `TGF-β` cascades, upregulating `DSPP`, `DMP1`, `ALP`, and `RUNX2`.
* **Immunomodulation & Neurovascular Coupling:**
  * `miR-200c` suppresses pro-inflammatory cytokines while promoting odontogenic differentiation in inflamed pulp, whereas `miR-146a` (via `IRAK1`/`TRAF6` inhibition) counterbalances pro-inflammatory `miR-155` to induce pro-healing macrophage polarization.
  * Hypoxia-responsive `miR-126` and `miR-210` promote `VEGF`-mediated microvascularization and neurotrophic nerve regeneration.
* **Cell-Free Exosomes & Smart Biomaterial Delivery:**
  * To overcome the regulatory, ethical, and viability limitations of direct stem cell transplantation (as well as the cytotoxicity of high-concentration triple antibiotic pastes compared to biocompatible calcium hydroxide), exosome-mediated ncRNA delivery offers a safe, cell-free alternative.
  * DPSC- and MSC-derived exosomes enriched with `lncRNA-Ankrd26` (modulating the `miR-150`/TLR axis), `CD73` (activating `AKT/ERK`), or angiogenic miRNAs (`miR-21`, `miR-26a`, `miR-125a`) induce dentin-bridge formation and pulp recellularization comparable to mineral trioxide aggregate (MTA).
  * Advanced delivery scaffolds—including **DNA tetrahedral nanostructures** and **injectable hydrogels**—protect ncRNAs from enzymatic degradation and enable controlled, localized release within the root canal microenvironment (Pandey & Kharche, 2026).

---

## 7. Cross-Study Integrative Matrix

| Research Domain | Primary Molecular Regulators / Biomarkers | Core Signaling Pathways & Mechanisms | Translational & Clinical Applications | Key Reference |
| :--- | :--- | :--- | :--- | :--- |
| **Pulpal & Periapical Proteomics** | Hornerin (`HRN`), `S100-A8/A9`, `PRDX1/2`, `MPO`, `HSP27`, `SERPINB1`, Gremlin-1 | Neutrophil degranulation, NETosis, Nrf2 oxidative stress, `RANKL/OPG` & BMP antagonism | Chairside diagnostics (pulpitis staging), pain/prognosis prediction, anti-Gremlin-1 bone repair | Rai et al. (2026) |
| **Ferroptosis & Regulated Cell Death** | `GPX4`, `SLC7A11`, `ACSL4`, `NCOA4`, `FSP1`, `TREM1/DRP1`, `ZBP1/NLRP3` | Iron-dependent lipid peroxidation, ferritinophagy, `cGAS-STING`, PANoptosis crosstalk | Liproxstatin-1, thymosin $\alpha 1$, and `JNK/NCOA4` inhibitors to preserve DPSCs & prevent bone loss | Parviainen et al. (2026) |
| **ECM Mineralization (BSP/SIBLING)** | Bone Sialoprotein (`IBSP`), RGD motif, $\alpha\text{v}\beta 3$ integrin, `MMP-2`, `Runx2`, `Osx` | `ERK1/2`, `PI3K/Akt`, HA crystal nucleation, `RANKL–NFATc1` synergy | Biomimetic scaffolds for dentin/bone regeneration; targeted anti-BSP therapy in osteolytic disease | Kottmann et al. (2026) |
| **Single-Cell Odontogenesis** | `LGR6+`, `SP6`, `DLX6-AS1+`, `Cd24a+`, `DIO2+`, `SPARC+/POSTN+`, `PDGFRA+` | Sequential `WNT–NOTCH` relay, `SHH`, `BMP/FGF`, `PDGF-BB` angiogenic–osteogenic coupling | iPSC ameloblast organoids, tubular dentin engineering, vascularized pulp–periodontal regeneration | Liao et al. (2026) |
| **ncRNA & Exosome Networks** | `miR-200c`, `miR-146a`, `miR-126`, `miR-210`, `lncRNA H19`, `SNHG1/7`, `lncRNA-Ankrd26` | ceRNA molecular sponging, `Wnt/β-catenin`, `PI3K-Akt`, `NF-κB`, `VEGF/AKT/ERK` | Cell-free exosomal therapeutics, DNA tetrahedral nanostructures, hydrogel scaffolds | Pandey & Kharche (2026) |

---

## 8. Critical Research Gaps & Future Translational Directions
Despite substantial progress in elucidating the molecular landscape of endodontic disease and regeneration, five major translational bottlenecks remain:

1. **Lack of Pre-Analytical & Bioinformatic Standardization:** High variability in specimen collection (dentinal fluid vs. pulp tissue vs. exudate), protein/RNA extraction, high-abundance protein depletion (e.g., albumin masking low-abundance cytokines), and sequencing normalization limits cross-study reproducibility (Rai et al., 2026; Pandey & Kharche, 2026). Consensus Standard Operating Procedures (SOPs) and expanded oral microbial genome databases for metaproteomics are urgently required.
2. **Limitations of Preclinical Models & Species Disparities:** Most mechanistic data on ferroptosis, BSP remodeling, and odontogenesis rely on rodent models (which possess continuously erupting incisors absent in humans) or simplified monocultures stimulated with purified LPS rather than complex polymicrobial biofilms on infected dentin (Liao et al., 2026; Parviainen et al., 2026). Furthermore, the functional impact of human post-translational modifications (such as BSP glycosylation and phosphorylation) remains poorly defined (Kottmann et al., 2026).
3. **Incomplete Recapitulation of the Regenerative Niche:** Current organoids, spheroids, and scaffolds struggle to simultaneously integrate vascularization, sensory innervation, immune resolution (e.g., macrophage efferocytosis), and mineralized tissue attachment (Liao et al., 2026; Parviainen et al., 2026).
4. **Balancing Host Defense vs. Cytoprotection:** Because labile iron and ROS also mediate antimicrobial host defense, therapeutic inhibition of pathways like ferroptosis must be precisely titrated and locally delivered so that preserving DPSCs does not inadvertently impair bacterial clearance (Parviainen et al., 2026).
5. **Need for Multi-Omics Integration & Prospective Clinical Trials:** Single-layer omics datasets cannot capture the full regulatory hierarchy of tissue healing. Future research must combine single-cell multi-omics (scRNA-seq, single-cell proteomics, metabolomics) with spatial transcriptomics and AI/machine learning frameworks to map cell-type-specific interactions *in situ*, followed by prospective randomized controlled trials (RCTs) using orthogonal validation (SRM/PRM mass spectrometry and chairside immunoassays) (Rai et al., 2026; Pandey & Kharche, 2026; Liao et al., 2026).

---

## 9. References
* Kottmann, V., Drees, P., Gercek, E., & Ritz, U. (2026). Bone sialoprotein: a multifunctional regulator of bone remodelling and tumour progression. *Bone Research*, 14, 11. https://doi.org/10.1038/s41413-025-00490-5
* Liao, C., Cai, J., Liu, Y., Xiao, L., Xiang, M., Qu, M., Long, Q., Xiang, M., Long, S., Peng, H., Liu, J., & Guan, X. (2026). Resolving tooth development at single-cell resolution: advancing dental regeneration. *Frontiers in Cell and Developmental Biology*, 14, 1785805. https://doi.org/10.3389/fcell.2026.1785805
* Pandey, R., & Kharche, P. (2026). Noncoding RNA networks in endodontic regeneration: Current evidence and future directions. *Journal of Conservative Dentistry and Endodontics*, 29(9), 968–978. https://doi.org/10.4103/JCDE.JCDE_316_26
* Parviainen, A., Tay, F., & Li, Y. Y. (2026). Ferroptosis in Endodontic Pathobiology: Emerging Evidence, Mechanistic Rationale, and Translational Uncertainties. *Journal of Endodontics*, 1–13. https://doi.org/10.1016/j.joen.2026.06.013
* Rai, A. S., Iype, A. M., Bhat, R., & Shetty, P. (2026). Proteomic profiling of pulpal and periapical diseases: a systematic review. *Frontiers in Dental Medicine*, 1923261. https://doi.org/10.3389/fdmed.2026.1923261
