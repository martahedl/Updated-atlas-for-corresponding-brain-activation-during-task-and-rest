# Updated-atlas-for-corresponding-brain-activation-during-task-and-rest
Updated and extended atlas from the ICA template suggested by Smith et al. 2009 (PNAS, https://doi.org/10.1073/pnas.0905267106). Additionally, a version of the atlas in the CIFTI file format is provided.


The complexity of our actions and thinking is likely reflected in functional brain networks. Independent component analysis (ICA) is a popular data-driven method to compute group differences between such networks. To aid interpretation of functional network analyses, Smith and colleagues proposed a template of ten functional networks identified in 36 healthy participants. They labeled them those components according to their similarity with statistical parameter maps from a metaanalysis of task-based functional magnetic resonance imaging studies (Smith et al., 2009).  However, those original templates show substantial distortion with respect to what up-to date correction methods can achieve, such that trying to capture relevant effects within several cortical regions, especially the sensorimotor and orbitofrontal cortices, as well as the cerebellum may yield suboptimal results. Here, we provide a technical update and extension to the original templates. Using correlation analyses, we identified the best matching maps of each of the original ten templates to ICA maps from the Human Connectome Project (HCP). The HCP provides group-parcellations of a large dataset (n = 1003) with high-quality data. This approach yields a better fit of spatial component maps with anatomical borders and gray-/white-matter-boundaries. Additionally, we provide a version of the updated templates in CIFTI   file-format, an emerging format in the neuroimaging community that combines surface-based data with subcortical/cerebellar data in volumetric space. The two formats we provide here offer an improvement on the templates by Smith et al., which should enhance sensitivity and interpretability of future research that compares functional networks between groups.