# Master's-thesis-of-Meng  

[简体中文](README.md) | English  

Ensemble-based data assimilation algorithms are among the most favored techniques
for aquifer parameter identification due to their widespread application across various
hydrogeological challenges. Nonetheless, the intrinsic assumptions of linear systems and
Gaussian-distributed variables often fall short in practical hydrogeological scenarios.
Addressing the deficiencies of data assimilation within non-Gaussian contexts and aiming
to accurately delineate aquifer media connectivity alongside historical contaminant
dissemination, this investigation innovates by amalgamating Normal Score
Transformation (NST) with Ensemble Smoother with Multiple Data Assimilation (ESMDA),
thus introducing the advanced NS-ESMDA methodology. This novel approach
adeptly converts variables with non-Gaussian distributions into a Gaussian framework
prior to updating, and subsequently reverts to the original distribution, effectively
retaining the authentic non-Gaussian characteristics of aquifer probability distributions
post-update—a challenge unmet by traditional ES-MDA. Building upon this foundation,
the research further integrates hyperparameterization to surmount the limitations of NSESMDA
in conserving prior spatial attributes. By employing a field generator for
hyperparameterization of the permeability field, it restrains hyperparameters to Gaussian
confines. This ensures the subsequent full-dimensional parameter fields align consistently
with established aquifer traits through the application of predetermined guidelines.
Advancing the research, the study leverages a deep generative model (DGM) as a field
generator in tandem with ES-MDA, elaborating the ES-DGM (Ensemble Smoother with
Deep Generative Models) technique. The ES-DGM framework skillfully integrates a
distance-based localization approach, bolstering the model's robustness in scenarios with
smaller ensembles. <br>
Empirical conclusions drawn from this research are threefold: <br>
(1) Relative to the restart Normal Score Ensemble Kalman Filter (rNS-EnKF), NSESMDA
exhibits a 35% increase in parameter estimation precision and a 24% gain in
computational efficiency after data ingestion. Moreover, the NS-ESMDA method is less
affected by equifinality and has a stronger updating capability, ensuring more accurate
parameter estimation values. <br>
(2) Through inversion analysis stemming from both two-dimensional prototypical
assessments (permeability field determination) and three-dimensional site-specific
evaluations (pollutant source parameters and permeability field recognition), ES-DGM
has been corroborated to precisely discern non-Gaussian aquifer parameters and recreate
contaminant release history, eclipsing NS-ESMDA especially in curtailing equifinality
and upholding pre-existing aquifer features. <br>
(3) The proposed localization technique, implicit in hyperparameterization, showcases
exceptional efficacy in small ensemble contexts and, when coupled with ES-DGM,
substantially curtails the requirement of computational assets.
This study proposes an efficient solution method for estimating non-Gaussian aquifer
parameters, which is expected to substantially improve the accuracy of parameter
estimation in non-Gaussian distributed aquifers, providing accurate and reliable
parameter support for numerical simulations of groundwater flow and contaminant
transport in aquifers with non-Gaussian parameter distributions.
