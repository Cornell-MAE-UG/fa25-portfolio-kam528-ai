---
layout: project
title: Design of the Electrospray Emitter Geometries
description: Fall 2025 Research Report
technologies: [Microfabrication, TPMS Python, CAD (Blender, Fusion360)]
image: /assets/images/Image3.png
---
<h1>Design of the Electrospray Emitter Geometries</h1>

<h1>Abstract</h1>
<p>
This paper discusses the results of a study on the design and manufacture of electrospray
emitters for electrospray propulsion systems conducted at the ASTRA Lab at Cornell University.
It investigates both the design process and the physical outcomes of producing emitters using
high-resolution 3D microfabrication to create a variety of emitter geometries. The study
evaluated a range of design features, including multiple angled vertical capillaries, curved
capillaries, Triply Periodic Minimal Surfaces (TPMS), TPMS gradients, and hybrid designs that
combine these elements.
</p>

<h1>1. Introduction to Electrospray Propulsion</h1>
<p>
Electrospray propulsion is an electric propulsion technique in which a strong electric field is
applied to a conductive liquid propellant, deforming the liquid surface into a Taylor cone and
extracting charged ions or droplets that are then accelerated to generate thrust
(<a href="https://link.springer.com/article/10.1007/s44205-023-00066-7" target="_blank">Kunze et al., 2024</a>). The propulsion mechanism relies on forces
rather than chemical energy, allowing electrospray thrusters to achieve very high impulse with
low propellant consumption, which helps with long duration, precision maneuvers on small
spacecrafts (<a href="https://doi.org/10.1002/advs.202413706open_in_new" target="_blank">Kim and Velásquez-García, 2025</a>). Performance can
be scaled by operating many microscale emitters in parallel, enabling higher total thrust while
maintaining stable, uniform emission and low operating voltages, particularly when enabled by
advanced additive manufacturing techniques
(Kim and Velásquez-García, 2025). As a result, engineered
nanoscale emitter geometries are critical, as their smooth surfaces enable uniform propellant
distribution and stabilize emission.
</p>

<h1>2. Emitter Material</h1>
<p>
Electrospray emitters are commonly fabricated from materials that combine chemical stability,
thermal robustness, and compatibility with high electric fields while allowing precise microscale
shaping. Many modern designs use photo-patternable polymer resins printed via two-photon
polymerization to form smooth, high-aspect-ratio capillary emitters with well controlled
geometries (<a href="https://pubs.acs.org/doi/full/10.1021/acs.analchem.4c06537" target="_blank">Xing et al., 2023</a>; Kunze et al., 2024). Polymer precursors such as POSS-based
materials are thermally converted into silica-like glass, improving thermal and chemical
resistance while preserving the printed structure
(Xing et al., 2023). Photo-polymer and glass based materials are
particularly advantageous for emitter fabrication because they support high-resolution 3D
microfabrication, allowing complex geometries and smooth surfaces to be produced while
maintaining electrical insulation that promotes stable electrospray emission.
</p>

<h1>3. Design Process</h1>
<p>
As part of the research, I designed emitters of different geometries. These were printed and
then either microscopically or SEM imaged to evaluate how easily they would be manufactured.
Successful emitters were subsequently subjected to flow testing to determine which geometric
features provided the most stabilized flow through the emitter. Throughout this project, I used
Blender and Onshape, two 3D creation software programs to finalize each emitter design during
the process.
</p>

<h2 style="margin-top: 2.5rem;">3.1 Capillary Designs</h2>

<h3>3.1.1 Multiple Vertical Angled Capillaries</h3>
<p>
This design used eight symmetrical capillaries around the midpoint of the emitter tip. Each
capillary was designed to be 10μm in diameter and extended straight upward from the base to
an angled exit along the rounded top. Upon microscopic inspection, the capillaries were found to
be visible and clear through the glass emitter. However, it was determined that the entrances
and exits at the base of the emitter were too small to allow efficient flow to the tip.
</p>

<h3>3.1.2 Curved Capillaries</h3>
<p>
This design featured a single capillary with a wavy internal structure, with a ratio of 45μm to
10μm between the large and small radii of the wave. The aim of this design was to increase the
stability of flow through the emitter. Although this structure could not be printed, a testing box
was fabricated to simplify microscopic evaluation <strong>(Image 2)</strong>. It was predicted that the
wavy structure would slow fluid movement, increasing flow impedance and allowing a more
predictable flow rate. In the online 3D model, changes in diameter that were expected to
influence flow behavior were observed <strong>(Image 1)</strong>.
</p>

<!-- Images 1 & 2 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/Image1.png"
       alt="Whole single capillary wave structure"
       style="width:100%; max-width:420px; border-radius:8px;">
  <figcaption style="font-size:0.95rem; margin-top:8px;">
    <strong>Image 1.</strong> Whole single capillary wave structure
  </figcaption>
</figure>


  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image2.png"
         alt="Simplified testing box model for microscope testing"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 2.</strong> Simplified testing box model for microscope testing
    </figcaption>
  </figure>
</div>

<h2 style="margin-top: 2.5rem;">3.2 TPMS Design</h2>
<p>
Triply Periodic Minimal Surfaces (TPMS) are smooth, continuous three dimensional structures
that repeat in all directions and contain no sharp corners or edges. Their geometry spreads
electric emission over a large surface area, increasing total emission while helping to control
and reduce local electric field intensity rather than concentrating it into sharp spikes. At the
same time, the continuous structure is lightweight yet mechanically strong, making it well suited
for stable and durable electropropulsion emitter designs. To generate this structure in my own
designs, I used Bryce Kingsley’s code to output an STL file with the TPMS mesh integrated into
the emitter geometry.
</p>

<p>
For this design, structures with reduced material were tested by cutting a hollow cone within a
solid emitter. A full TPMS gradient with a nodal size of 10 μm was then applied across the entire
structure for flow control. After printing, the more concentrated and thicker solid regions yielded
significantly better results and were able to maintain their structural integrity <strong>(Image 4)</strong>. In contrast, thinner regions within the emitter that incorporated TPMS generation exhibited
increased breakage at their ends <strong>(Image 3)</strong>.
</p>

<!-- Images 3 & 4 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image3.png"
         alt="Structure showing less stability on thin ends"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 3.</strong> Structure showing less stability on thin ends
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image4.png"
         alt="Close up of thick TPMS emitter tip"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 4.</strong> Close up of thick TPMS emitter tip
    </figcaption>
  </figure>
</div>

<h2 style="margin-top: 2.5rem;">3.3 TPMS Hybrid Designs</h2>

<h3>3.3.1 Cutout Inner Cone</h3>
<p>
This design expanded on the previous hollow TPMS design by adding a solid cone inside to
create a thickened internal structure. During the printing of this design, it was hypothesized that
there was less strain on the emitter during manufacturing, resulting in reduced breakage in the
final printed structures <strong>(Images 5 and 6)</strong>.
</p

<!-- Images 5 & 6 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image5.png"
         alt="Close up stable of emitter tip"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 5.</strong> Close up stable of emitter tip
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image6.png"
         alt="Full hybrid cone emitter"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 6.</strong> Full hybrid cone emitter
    </figcaption>
  </figure>
</div>

<h3>3.3.2 Solid Shell with TPMS Cone Fill In</h3>
<p>
This design depicts a solid cone emitter with 10μm exit capillaries, filled with a cone of TPMS
featuring a 10μm nodal size. This design exhibited multiple cracks around the solid shell of the
emitter <strong>(Image 8)</strong>. It was hypothesized that these defects were due to a change in resin used for
this batch of emitters, as thermal heating induced strain in this material leading to cracking in
the final product.
</p>

<!-- Images 7 & 8 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image7.png"
         alt="Close up of 10μm exit capillaries"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 7.</strong> Close up of 10μm exit capillaries
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image8.png"
         alt="Cracks around the solid emitter shell"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 8.</strong> Cracks around the solid emitter shell
    </figcaption>
  </figure>
</div>

<h3>3.3.3 Single TPMS Core</h3>
<p>
This design incorporated one straight core through the cone emitter with a TPMS structure. It
was assumed that this emitter did not develop cracks due to the change in resin material used
during printing, allowing it to better withstand thermal heating during conversion to glass. This
design was intended to localize electrospray emission at the emitter tip while using the
impedance of the TPMS nodes to modulate flow. It was also observed that the previous large
base cutouts did not allow sufficient flow towards the main capillaries. As a result, the base
structure of the solid emitters was modified to a column structure designed by Bryce Kingsley, in
hopes to maximize flow up the capillaries <strong>(Image 10)</strong>.
</p>

<!-- Images 9 & 10 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image9.png"
         alt="Full TPMS core Emitter"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 9.</strong> Full TPMS core Emitter
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image10.png"
         alt="New column base structure designed by Bryce Kingsley"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 10.</strong> New column base structure designed by Bryce Kingsley
    </figcaption>
  </figure>
</div>

<!-- Image 11 -->
<p style="text-align:center; margin: 16px 0;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/Image11.png"
       alt="Close up of rounded TPMS core tip"
       style="max-width: 560px; width: 100%; border-radius: 8px;">
</p>
<p style="text-align:center; font-size:0.95rem; margin-top:-8px;">
  <strong>Image 11.</strong> Close up of rounded TPMS core tip
</p>

<h2 style="margin-top: 2.5rem;">3.4 TPMS Gradient Designs</h2>
<p>
This design focused on changing the gradient of the TPMS nodal sizing from the top to the
bottom of the emitter. Two different iterations were created. One used a TPMS gradient of (2,
0.5), producing a small to large gradient from the base upward, with the largest pore size being
10μm. The second used a gradient of (0.5, 2), producing a large to small gradient from the base
upward, also with a largest pore size of10 μm <strong>(Images 12–15)</strong>. After initial analysis, only the
small to large gradient was selected for printing, as it was expected to produce a more stable
flow as the fluid moved upward through progressively smaller TPMS nodes.
</p>

<!-- Images 12 & 13 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image12.png"
         alt="Full TPMS (.5,2) Gradient Design"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 12.</strong> Full TPMS (.5,2) Gradient Design
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image13.png"
         alt="Close-up of emitter tip with 6μm nodes (.5,2)"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 13.</strong> Close-up of emitter tip with 6μm nodes (.5,2)
    </figcaption>
  </figure>
</div>

<!-- Images 14 & 15 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image14.png"
         alt="Close- up of emitter base with 10μm nodes (.5,2)"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 14.</strong> Close- up of emitter base with 10μm nodes (.5,2)
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image15.png"
         alt="Close-up of column base designed by Bryce Kingsley"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 15.</strong> Close-up of column base designed by Bryce Kingsley
    </figcaption>
  </figure>
</div>

<h1 style="margin-top: 3rem;">4.0 Testing Results</h1>
<p>
While completing SEM imaging for each of the printed emitters, image analysis was performed
using ImageJ/FIJI to determine the actual capillary size after 3D printing. As a result, it was
found that there was at least a 1μm decrease in capillary diameter compared to the original
online 3D models created in advance. This information was then used to inform the design of
future emitters to more closely match the intended proportions.
</p>

<p>
To conclude physical testing, only emitters with the most promising predicted performance were
manually tested, specifically the TPMS gradient (0.5, 2) emitter and the single TPMS core
emitter. This testing involved placing the emitters under a microscope and using a micropipette
to inject food coloring at the base of the emitter in order to observe whether the fluid could reach
the emitter tip autonomously. <strong>Images 16 and 17</strong> show the emitters under the microscope during
testing. However, no liquid was observed to reach the top of the emitters. It was hypothesized
that residual resin remained within the TPMS nodes, blocking the flow pathway to the tip.
Additionally, for the gradient emitter, because fluid traveled only halfway through the structure, it
was assumed that the TPMS nodes near the tip were too small to allow fluid passage after
printing. Although fluid was not successfully passed through the emitters, it was concluded that
the TPMS nodal size must be significantly larger than initially anticipated to account for
shrinkage and ensure clear flow through pathways.
</p>

<!-- Images 16 & 17 -->
<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image16.png"
         alt="Gradient (.5,2) TPMS emitter"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 16.</strong> Gradient (.5,2) TPMS emitter
    </figcaption>
  </figure>

  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
    <img src="/fa25-portfolio-kam528-ai/assets/images/Image17.png"
         alt="Single TPMS core emitter"
         style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 17.</strong> Single TPMS core emitter
    </figcaption>
  </figure>
</div>

<p style="text-align:center;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/EmitterTesting.png"
       alt="Heat exchanger setup"
       style="max-width: 400px; width: 100%; border-radius: 8px;">
  <figcaption style="font-size:0.95rem; margin-top:8px;">
      <strong>Image 18.</strong> Emitter testing setup
    </figcaption>
  </figure>
</p>

<h1 style="margin-top: 3rem;">Conclusion</h1>
<p>
This research examined the process behind manufacturing electrospray emitters and the design
considerations involved in their development. Many emitter geometries were designed, and the
most promising configurations were printed to evaluate their physical performance. Through this
process, a variety of geometries were analyzed, including angled vertical capillaries, Triply
Periodic Minimal Surfaces (TPMS), TPMS gradients, and hybrid designs that combine these
elements. It was found that structural design significantly altered strain distribution in different
regions of the emitter and that the resulting behavior varied depending on the resin material
used for printing. Both factors contributed to various modes of failure throughout the design
process. As these issues were addressed through iterative design modifications, the printed
emitters demonstrated improved structural stability.
</p>

<p>
Final physical testing involved introducing food coloring at the base of well fabricated emitters;
however, the fluid did not reach the emitter tips. It was hypothesized that this was due to
residual resin remaining from the printing process or shrinkage of the emitters after fabrication.
Using ImageJ/FIJI to obtain precise measurements of post-printed nodes and capillaries
allowed future 3D models to be adjusted to account for emitter shrinkage during production.
While additional testing is required to determine optimal emitter design, this work demonstrated
that capillary diameter and internal structural features play a significant role in overall emitter
performance. Future studies will require systematic testing of printed diameters and impedance
structures across a wider range of values to identify optimal electrospray emitter configurations.
</p>