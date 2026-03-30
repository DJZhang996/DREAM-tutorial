Welcome to DREAM’s documentation!
===================================

DREAM links condition-specific microenvironments to clinical phenotypes via concept-driven spatial modeling 
------------------------------------------------------------------------------------------------------------------

( Document being updated... )

=====================================================================================================================================================

.. toctree::
   :maxdepth: 1

   RUN_Spleen
   RUN_CRCLM


Overview of DREAM
====================

.. image:: ../Figures/Fig1-f_new.jpg
   :width: 1400


The spatial organization of multicellular ecosystems underpins tissue homeostasis and disease progression. Given the high spatial heterogeneity of complex diseases, accurately identifying condition-specific microenvironments linked to clinical phenotypes is a prerequisite for uncovering disease-driving mechanisms and formulating precision medicine strategies. However, current spatial omics computational methods are largely limited to descriptive spatial clustering; they lack the interpretability required to explore pathological associations and struggle to map complex cellular states within microenvironments directly to macroscopic clinical outcomes. Here, we present DREAM (Dual-stream Representation & Explicit Attribution Modeling), a computational framework for interpretable attribution via concept-driven modeling. DREAM leverages context-aware semantic transfer to construct robust niche semantic representations, synergistically encoding intrinsic biological semantics and extrinsic spatial topology through a dual-stream architecture. By incorporating a concept bottleneck mechanism, the framework maintains a balance between clinical predictive accuracy and biological interpretability. Extensive benchmarking across five multi-scale spatial transcriptomic and proteomic datasets demonstrates DREAM’s superior performance in identifying highly reproducible tissue domains. Applied to clinical cohorts, DREAM accurately predicted slice-level disease states and explicitly identified the microenvironmental drivers of colorectal cancer metastasis by pinpointing the spatial convergence of tumor stemness and stromal remodeling. Furthermore, in liver cancer, the framework autonomously localized functional tertiary lymphoid structures (TLS) in a fully unsupervised manner, yielding a compact, highly prognostic spatial biomarker. Ultimately, DREAM demonstrates how concept-driven modeling can highlight potential pathological associations from complex spatial omics data, providing a novel computational perspective for understanding spatial heterogeneity in complex diseases.
