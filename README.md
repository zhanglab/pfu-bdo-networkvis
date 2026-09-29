# P. furiosus 2,3-BDO Metabolic Network Visualization

Interactive network visualization accompanying the publication on engineered
*Pyrococcus furiosus* strains for 2,3-butanediol production.

🔗 **[View the interactive figure](https://zhanglab.github.io/pfu-bdo-networkvis/)**

**Model repository:** [zhanglab/GEM-iPfu](https://github.com/zhanglab/GEM-iPfu)

## Citations
* O’Quinn, Hailey, Jason Vailionis, Katherine Holandez-Lopez, Meghana Faltane, Tania N. N. Tanwee, Kathryne Ford, Farris L. Poole, Katherine B. Louie, Benjamin P. Bowen, Ying Zhang, Robert M. Kelly, and Michael W. W. Adam. 2026. "Engineering the Hyperthermophilic Archaeon Pyrococcus furiosus for 2,3-Butanediol Production Informed by Metabolic Modeling and Metabolomics". (Submitted to AEM)
* Vailionis, Jason L., Hailey C. O’Quinn, Katherine S. Holandez-Lopez, Meghana Faltane, Tania N. N. Tanwee, Kathryne C. Ford, Farris L. Poole, Katherine B. Louie, Benjamin P. Bowen, Robert M. Kelly, Michael W. W. Adams, and Ying Zhang. 2026. "Targeted and untargeted metabolomics with absolute quantification of intracellular metabolites in the hyperthermophilic archaeon Pyrococcus furiosus during 2,3-butanediol production". (Submitted to MRA)

## Running the Live App Locally
The version above only supports the default view: BDO-ALS vs Parent-COM, no normalization. To explore other strain comparisons and normalization schemes, launch the full Dash app via Docker:

```bash
docker pull jvjvjvjv/pfu-bdo-networkvis
docker run -p 8050:8050 jvjvjvjv/pfu-bdo-networkvis
```
Then open http://localhost:8050 in your browser.
