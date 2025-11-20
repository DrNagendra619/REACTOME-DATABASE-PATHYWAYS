# REACTOME-DATABASE-PATHYWAYS
REACTOME DATABASE PATHYWAYS
⚛️ Reactome Pathway Analysis Repository

This repository contains a curated collection of key biological pathway diagrams derived from the Reactome Knowledgebase. These pathways were selected to highlight the complex interconnections between cell signaling, metabolism, cellular stress responses, and their involvement in diseases, particularly Alzheimer's Disease (AD).

The diagrams include overlay data (indicated by the heatmap scale on the right, typically representing statistical significance like FDR or hit counts, though the specific analysis context is external) for rapid visual interpretation.

📁 Included Pathways

The following six Reactome diagrams are included in this analysis:
Filename,Reactome Pathway Title,Core Biological Theme,Reactome ID (Approximate)
ALZHEMEIRS DISEASE R-HSA-1643685 disease .jpg,Disease,"General overview of human diseases originating from various cellular dysfunctions (DNA repair, metabolism, immune system) linked by shared pathological features (e.g., stress, mitotic cycle).",R-HSA-1643685
ALZHEMEIRS DISEASE R-HSA-392499 proten metabolism .jpeg,Protein Metabolism (AD Context),"Focuses on protein fate: translation, folding, degradation (LONP1), and the production of specific disease-associated proteins like APP (Amyloid Precursor Protein).",R-HSA-392499
GYYCOLYIS R-HSA-1430728 GLYCOLYSIS METABOLISM PATHWAY .jpg,Metabolism,"Comprehensive map of Glycolysis, the TCA cycle (via Ac-CoA), and the central role of Pyruvate in linking carbohydrate, lipid (Fatty Acids, CHOL), and amino acid metabolism.",R-HSA-1430728
GYYCOLYIS R-HSA-2262752 PATHYWAY ANALYSIS(CELLULAR RESPONSE) .jpg,Cellular Response to Stress,"Details multiple stress responses: Hypoxia (HIF1A), Mitochondrial Stress, Heat Shock (HSF1/HSP), and the Unfolded Protein Response (UPR) in the ER.",R-HSA-2262752
GYYCOLYIS R-HSA-162582 SIGNAL TRANSUCTION.jpg,Signal Transduction,"Global view of cell signaling including RTK, GPCR, WNT, Hedgehog, Hippo, PI3K-Akt (AKT1), and MAPK pathways, all converging on Gene Expression, Cellular Metabolism, and Apoptosis.",R-HSA-162582
ALZHEMEIRS DISEASE R-HSA-162582 signal transduction alzheimer's diease .jpg,Signal Transduction (AD Context),"(Note: This is a duplicate of R-HSA-162582, reinforcing its central importance in disease context.)",R-HSA-162582
🧠 Pathway Interconnections & Biological Links

This collection highlights a crucial synergy between cell signaling, stress, and metabolism, which is particularly relevant to the pathogenesis of Alzheimer's Disease (AD):

1. Signal Transduction and Metabolism

    Central Signaling Hubs: The Signal Transduction pathway (R-HSA-162582) features key modules like PI3K → AKT1 → mTOR.

    Metabolic Regulation: mTOR signaling is a central regulator that links nutrient availability to Cellular Metabolism and Protein Synthesis. Changes in glucose availability (from the Metabolism pathway R-HSA-1430728) directly influence AKT1 and mTOR activity.

    Insulin Resistance Link: The Protein Metabolism pathway (R-HSA-392499) explicitly shows the involvement of INSULIN and IGF transport/uptake, linking the metabolic dysfunction (insulin resistance) often observed in AD back to Aβ Amyloid Fiber Formation.

2. Stress Responses and Protein Fate

    Protein Misfolding in AD: The Protein Metabolism pathway (R-HSA-392499) shows the generation of the APP peptide and its aggregation into Amyloid Fibers, a hallmark of AD.

    Cellular Stress and UPR: Protein Folding is directly regulated by the Cellular Response to Stress pathway (R-HSA-2262752). Unfolded Proteins trigger the UPR (Unfolded Protein Response) via factors like PERK, Heme, and HSPA5 in the Endoplasmic Reticulum (ER). Chronic ER stress contributes to neuronal damage.

    Mitochondrial Degradation: The pathway also shows Mitochondrial Protein Degradation by LONP1, linking proteostasis defects to mitochondrial dysfunction, a key factor in both aging and neurodegeneration.

3. Disease Context

    The Disease overview (R-HSA-1643685) places AD-related mechanisms (Mutant Protein, Aberrant Chromosome) within the broader context of Disorders of Metabolism, Cellular Stress, and Programmed Cell Death, suggesting that AD is a systemic pathology with inputs from multiple regulatory failures.

💻 Usage and Citation

Viewing the Pathways

The original pathway files are provided as .jpg images. For the best viewing experience, please view them directly on GitHub or download them to use an image viewer.

Citing the Source

These diagrams are generated from the Reactome Knowledgebase. If you use or reference these files in your own work, please ensure you cite the official Reactome publication(s):

    Jassal, B., et al. (2024). The Reactome Pathway Knowledgebase. Nucleic Acids Research, 52(D1), D689-D699.

License

This repository is shared under the MIT License.
