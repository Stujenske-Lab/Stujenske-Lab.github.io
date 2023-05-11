---
title: Projects
nav:
  order: 2
  tooltip: Research Questions
---
# {% include icon.html icon="fa-solid fa-microscope" %}Projects
## The cognitive regulation of internal states

A prevailing view is that fear is an internal brain state underlying observable manifestations including defensive behavior and somatic responses (e.g., pupil dilation)
([Review by Anderson & Adolphs, 2014](https://www.cell.com/fulltext/S0092-8674(14)00292-X){:target="_blank"}{:rel="noopener noreferrer"}). The neural mechanisms by which such internal states are generated and controlled are not well-understood. Fear is well-conserved across species and provides a tractable model for understanding how internal states are regulated. A circuit understanding of Internal state control is relevant to the relationship between arousal and emotion, about which multiple competing theories exist; for instance, James-Lange theory proposes that bodily responses trigger emotions, implying that regulation of somatic response is critical for top-down control. These circuits are also therapeutically relevant, as spatial localization of internal state regulators may allow for targeting with trans-magnetic stimulation, while physiological treatments like vagus nerve stimulation and biofeedback treatments may be optimized based on circuit logic. Relevant microcircuits may also contain novel pharmacological targets.

{% capture content %}
{% include figure.html image="images/Internal_State_Assessment.jpg" caption="**Figure 1. Simultaneous two-photon imaging, behavior, and physiology measurements.**
**A.** Schematic of non-invasive physiology monitoring during behavior. Respirations are imaged with a thermal camera (see C) and heart rate is captured using a pulse oximeter (MouseOx) on the tail.
**B.** Average fear responses exhibit distinct dynamics (5 trials each, n=12 mice). HRV, heart rate variability.
**C.** Example pupil (left) and thermal imaging (right).
**D.** Fear retrieval session of a water-restricted mouse. The fear conditioned cue (CS+) leads to decreased licking and tachypnea. As shown, trial-by-trial HR, RR, and pupil size exhibit periods of uncorrelation.
**E.** Deep layer mPFC cells expressing jGCaMP8s were imaged and have event-locked activations." width="100%" %}
{% endcapture %}
{% include float.html content=content width="200px" flip=true text=text%}
The psychotherapeutic treatment of psychiatric disorders strongly suggests that individuals can learn to exert cognitive control over internal states. The Stujenske Lab aims to test the overarching hypothesis that the medial prefrontal cortex mediates top-down regulation internal states via outputs to subcortical structures. In particular, the Stujenske Lab focuses on the cognitive regulation of fear by studying the process of discrimination between aversive and non-aversive stimuli.

Overgeneralization, in which negative affect states are triggered in both dangerous and safe situations, is a trans-diagnostic phenomenon affecting patients with anxiety disorders, OCD, and PTSD ([Dymond et al., 2015](https://doi.org/10.1016/j.beth.2014.10.001){:target="_blank"}{:rel="noopener noreferrer"}), which are very prevalent but often refractory to treatment ([Bystritsky, 2006](https://doi.org/10.1038/sj.mp.4001852){:target="_blank"}{:rel="noopener noreferrer"}). Striking a trade-off between discrimination and generalization is critical for avoiding danger without excessively forgoing exploration and reward-seeking ([Dunsmoor and Paz, 2015](https://doi.org/10.1016/j.biopsych.2015.04.010){:target="_blank"}{:rel="noopener noreferrer"}). Preventing overgeneralization requires circuits that constrain fear responses ([Reviewed by Korzus, 2015](https://doi.org/10.4137/jen.s26227){:target="_blank"}{:rel="noopener noreferrer"}), in a process that is distinct from fear extinction, during which conditioned aversive stimuli are learned to be non-aversive. While fear extinction circuits have been extensively studied, the cognitive control of fear discrimination is not well understood([Dymond et al., 2015](https://doi.org/10.1016/j.beth.2014.10.001){:target="_blank"}{:rel="noopener noreferrer"}). Extinction-based treatments for PTSD and anxiety disorders are effective but difficult to tolerate, and cognition-based treatments are evidence-based alternatives ([Schnurr et al., 2022](https://doi.org/10.1001/jamanetworkopen.2021.36921){:target="_blank"}{:rel="noopener noreferrer"}); thus, cognitive control circuits are clinically relevant.

Overgeneralization is associated with abnormal reactivity in the medial prefrontal cortex (mPFC) ([Greenberg et al., 2013](https://doi.org/10.1002/da.22016){:target="_blank"}{:rel="noopener noreferrer"}), and patients with mPFC damage exhibit both abnormal behavioral inhibition and altered autonomic responses that perturb decision-making and learning about risk ([Bechara et al., 1997](https://doi.org/10.1126/science.275.5304.1293){:target="_blank"}{:rel="noopener noreferrer"}; [McKlveen et al., 2015](https://doi.org/10.1111/jne.12272){:target="_blank"}{:rel="noopener noreferrer"}). The Stujenske lab aims to develop an integrated understanding of parallel manifestations of fear states (behavioral and somatic) and link them to prefrontal cognitive microcircuits that discriminate between fear and safety. In doing so, we aim to clarify how fear states are bidirectionally regulated to support adaptive decision-making.

Our lab uses computational methods and multiple complementary system neuroscience techniques to pursue this goal. To investigate the relationship of defensive behavior and somatic response, Dr. Stujenske developed a way to non-invasively monitor behavior, respiration rate, heart rate, and pupil size in head-fixed mice (Fig 1A). Mice freely lick for water, but after differential fear conditioning, in which one tone is paired with a shock (CS+) and another tone is explicitly unpaired (CS-), the CS+ triggers mice to immobilize and stop licking (Fig 1B-D). Notably, this occurs with changes typically associated with sympathetic activation (Fig 1B).

{% include float.html clear=true %}

## The spatial topography of medial prefrontal cortical encoding

{% capture content %}
{% include figure.html image="images/prism_figure.png" caption="**Figure 2. Microprism imaging enables investigates of spatial topography in mPFC**
**A.** Schematic of microprism surgeries for imaging across layers (left) or rostrocaudal in layer 2 (right)
**B.** Representative histology of microprism implantation (as for Aim 2), with virally-expressed jGCaMP6s. White box indicates the imaged plane.
**C.** Average projection of calcium imaging session from a single SOM-IRES-cre mouse expressing AAV:FLEX-tdTomato and AAV:syn-jGCamp6s. Inset: co-labeled cells (arrow heads). PL, prelimbic cortex; IL, infralimbic cortex; ACC, anterior cingulate
" width="100%" %}
{% endcapture %}
{% include float.html content=content width="200px" flip=true text=text%}
The medial prefrontal cortex (mPFC) has been primarily subdivided along its dorsal-ventral axis. In the mouse, the main dorsal and ventral mPFC regions are called the prelimbic cortex (PL) and infralimbic cortex (IL), respectively. Many groups have described differences in the function of these regions for regulating defensive behavior related to feared outcomes. The PL has been primarily implicated in the expression of defensive behavior after learning, while the IL is involved in the extinction of learned aversive associations, through repeated experiences of a feared stimuli without the anticipated threat occurring ([Review by Giustino & Maren, 2015](https://www.frontiersin.org/articles/10.3389/fnbeh.2015.00298/full){:target="_blank"}{:rel="noopener noreferrer"}).

In his postdoctoral work, Dr. Stujenske found that the dorsomedial prefrontal cortex prevents overgeneralization of fear responses, via gating of dendritic input by amygdala somatostatin-positive interneurons ([Stujenske*, O'Neill* et al., 2022](https://doi.org/10.1016/j.neuron.2022.03.020){:target="_blank"}{:rel="noopener noreferrer"}), demonstrating a pathway for prefrontal cognitive control of fear. Given that dmPFC also supports fear expression (Giustino and Maren, 2015), my findings suggest that dmPFC bidirectionally regulates fear. In rodents, defensive behavior has been used as a proxy for internal fear state, but many somatic changes occur simultaneously. The mPFC is a critical region regulating both defensive behavior and autonomic reactivity during fear ([McKlveen et al., 2015](https://doi.org/10.1111/jne.12272){:target="_blank"}{:rel="noopener noreferrer"}). How these prefrontal regulatory functions (behavioral and somatic) relate is unknown.

A key aim of the lab is to characterize the spatial topography of fear state encoding within the mPFC, not only again its dorsoventral axis, but also along its laminar (mediolateral) and anteroposterior axes. Preliminary data from the lab suggests that there are meaningful distinctions along these axes with regards to information encoding and regulation of fear response.

{% include float.html clear=true %}

