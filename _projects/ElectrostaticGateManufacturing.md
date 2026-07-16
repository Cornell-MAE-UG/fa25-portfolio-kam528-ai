---
layout: project
title: Electrostatic Gate Design
description: 
technologies: [Fusion360, CNC Machining, Milling, Laser Cutting, Manual Machining, Assembly]
image: 
thumbnail: /assets/images/full_gate.png
---
## Project Navigation

- [Project Overview](#project-overview)
- [Problem](#problem)
- [Design Requirements](#design-requirements)
- [Design Process](#design-process)
- [Engineering Analysis](#engineering-analysis)
- [Manufacturing](#manufacturing)
- [Results](#results)

---

<a id="project-overview"></a>
<h1>Project Overview</h1>

<figure style="text-align: center; width: 100%;">
  <img src="{{ '/assets/images/full_gate.png' | relative_url }}" 
       alt="Image of Electrostatic Gate for Time-of-Flight Diagnostics"  
       style="width: 100%;">
  <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>Electrostatic Gate for Time-of-Flight Diagnostics</strong>
  </figcaption>
</figure>

Designed and manufactured a custom electrostatic gate
to improve the accuracy and repeatability of Time-of-
Flight diagnostics for electrospray propulsion research.


<div style="float:right; width:275px; border:1px solid #d0d7de; border-radius:8px; padding:16px; margin:0 0 20px 20px; background:#f8f9fa; font-size:0.95em;">

<h3 style="margin-top:0;">Project Details</h3>

<table style="width:100%; border-collapse:collapse;">
<tr>
<td><strong>Role</strong></td>
<td>Mechanical Design Engineer</td>
</tr>

<tr>
<td><strong>Software</strong></td>
<td>Fusion 360</td>
</tr>

<tr>
<td><strong>Manufacturing</strong></td>
<td>CNC Machining<br>
Milling<br>
Laser Cutting<br>
Manual Machining<br>
Assembly</td>
</tr>

<tr>
<td><strong>Materials</strong></td>
<td>Aluminum<br>PEEK</td>
</tr>

<tr>
<td><strong>Duration</strong></td>
<td>Spring 2026<br>1 Semester</td>
</tr>

</table>

</div>


The purpose of this project was to design and manufacture a new electrostatic gate for a Time-of-Flight (TOF) diagnostic system used to characterize the ionic species produced by an electrospray propulsion source. TOF diagnostics measure the flight time of charged particles traveling to a microchannel plate (MCP) detector, allowing researchers to identify and quantify monomers, dimers, and other charged droplets that contribute to propulsion.

The previous electrostatic gate introduced uncertainty into these measurements because particles could bypass the active gating region before entering the TOF tube. This reduced the accuracy and repeatability of the collected data, making it more difficult to characterize the performance of the electrospray thruster.

To address this issue, I independently designed, manufactured, and assembled a completely new electrostatic gate that improves particle confinement, alignment with the TOF tube, and experimental flexibility while integrating directly into the laboratory's existing vacuum chamber. This project combined mechanical design, precision manufacturing, electrical isolation, and experimental hardware integration to create a more reliable diagnostic system for electrospray propulsion research.


<a id="problem"></a>
<h1>Problem</h1>

<figure style="text-align: center; width: 100%;">
  <img src="{{ '/assets/images/TOF_system_diagram.png' | relative_url }}"
       alt="Time-of-Flight Diagnostic System Diagram"
       style="width: 100%; max-width: 1200px; height: auto;">

  <figcaption style="text-align: center; font-size: 0.9em; color: #666;">
    <strong>Figure 1.</strong> Simplified Time-of-Flight (TOF) diagnostic system showing the electrospray source, electrostatic gate, flight tube, and microchannel plate (MCP) detector.s
  </figcaption>
</figure>

The performance of an electrospray propulsion system depends on accurately measuring the ionic species it produces. Using a Time-of-Flight (TOF) diagnostic system, researchers determine the mass-to-charge ratio of charged particles by measuring the time required for them to travel from the electrostatic gate to a microchannel plate (MCP) detector.

The original electrostatic gate limited the accuracy of these measurements because its open geometry allowed charged particles to travel around the active gating region and still reach the detector. These unwanted particles introduced additional signals that reduced measurement accuracy and made it more difficult to distinguish between monomers, dimers, and other ionic species.

<figure style="text-align: center; width: 100%;">
  <img src="{{ '/assets/images/OG_gate.png' | relative_url }}"
       alt="Original Electrostatic Gate"
       style="width: 80%; height: auto;">

  <figcaption style="text-align: center; font-size: 0.9em; color: #666;">
    <strong>Figure 2.</strong> Original electrostatic gate used for Time-of-Flight (TOF) diagnostics.
  </figcaption>
</figure>

Because the electrostatic gate establishes the starting point of every TOF measurement, improving its design was essential for producing more reliable, repeatable, and accurate experimental data.
### Picture of the original gate, Annotated picture showing where particles could escape, Simple TOF system diagram, Optional comparison: Old Gate vs. New Gate



<a id="design-requirements"></a>
<h1>Design Requirements</h1>
The redesigned electrostatic gate was developed to satisfy several mechanical, electrical, and experimental requirements.

- Prevent particles from bypassing the active gating region.
- Produce a precise and repeatable starting point for Time-of-Flight measurements.
- Improve alignment between the gate, TOF tube, and MCP detector.
- Electrically isolate the high-voltage electrodes from the aluminum housing.
- Allow precise adjustment of gate position inside the vacuum chamber.
- Support interchangeable gate assemblies for future experimental configurations.
- Integrate with the laboratory's existing vacuum chamber and diagnostic hardware.
- Be manufacturable using available machine shop equipment while maintaining tight dimensional tolerances.
# Requirement table, Labeled CAD model, Cross-section of gate


<a id="design-process"></a>
<h1>Design Process</h1>
The design process began by evaluating the shortcomings of the previous electrostatic gate and identifying the primary sources of measurement uncertainty. The largest issue was that charged particles could bypass the electric field by traveling around the open sides of the gate before entering the Time-of-Flight tube.

To eliminate this problem, I designed a completely new electrostatic gate assembly in Fusion 360. The redesigned system features an enclosed aluminum electrode housing connected directly to a cylindrical tube leading into the TOF chamber. This enclosed geometry forces particles to pass through the active gating region before entering the detector, greatly reducing unwanted signals.

The entrance aperture was reduced and the spacing between the electrodes was optimized to improve electric field control. During operation, voltage applied across the electrodes creates an electric field that deflects incoming charged particles away from the detector. When the voltage is switched off, particles are allowed to pass through the aperture, creating a well-defined starting point for Time-of-Flight measurements.

To improve flexibility for future experiments, the gate was designed as a modular assembly. The front electrode housing can be replaced with alternate designs while the entire system mounts to an adjustable optical post attached to an optical breadboard, allowing precise alignment with the TOF tube and MCP detector.
# CAD evolution (Version 1 → Version 2 → Final), Exploded assembly, Section view, Render of entire assembly, Sketches (if you have them)


<a id="engineering-analysis"></a>
<h1>Engineering Analysis</h1>
The electrostatic gate operates by controlling the motion of charged particles using an electric field generated between two closely spaced electrodes located at the entrance of the gate.

When voltage is applied, the electric field deflects ions away from the Time-of-Flight tube, preventing them from reaching the detector. Once the voltage is switched off, the particles are allowed to travel through the aperture and continue toward the microchannel plate (MCP) detector. This controlled transition establishes the precise starting time required for accurate TOF measurements.

Several geometric design decisions were made to improve the performance of the gate. Reducing the entrance aperture and decreasing the spacing between the electrodes concentrates the electric field within the active gating region, while the enclosed tube prevents particles traveling outside the intended trajectory from reaching the detector. Together, these features reduce background signals and improve the repeatability and accuracy of TOF measurements.

Future work will include mechanical fastener calculations, electric field characterization, and experimental validation of gate performance through comparison of TOF spectra before and after the redesign.
### Gate ON diagram (particles deflected), Gate OFF diagram (particles pass through), Electric field illustration, Future calculations, FEA or field simulation (if you perform one later)


<a id="manufacturing"></a>
<h1>Manufacturing</h1>
The electrostatic gate was manufactured using multiple precision fabrication techniques to produce a vacuum-compatible assembly.

The front electrode housing was CNC machined from aluminum to achieve the required dimensional accuracy and precise electrode alignment. The connecting tube was milled from aluminum stock before being integrated into the assembly. Additional structural components were produced using laser-cut aluminum or manufactured in the Cornell student machine shop.

To electrically isolate the high-voltage electrodes from the aluminum housing, custom PEEK insulating blocks were incorporated into the design. These insulators prevent electrical shorting while maintaining accurate electrode positioning inside the vacuum chamber.

After fabrication, I assembled the complete system and mounted it to an optical breadboard using an adjustable optical post. This mounting method allows precise alignment with the Time-of-Flight tube and MCP detector while also providing the flexibility to swap the front gate assembly for future experimental configurations.
##### CNC machining photos, Milling photos, Laser-cut part, Student machine shop, Assembly sequence, Finished assembly, PEEK insulators highlighted



<a id="results"></a>
<h1>Results</h1>
The electrostatic gate has been successfully designed, manufactured, and integrated into the laboratory's Time-of-Flight diagnostic system. Experimental testing is currently underway to evaluate its performance under operating conditions.

The redesigned enclosed geometry is expected to reduce particle leakage around the active gating region, improving signal quality and the repeatability of TOF measurements. By ensuring that only particles passing through the controlled electric field reach the detector, the new design aims to provide more accurate measurements of monomer and dimer populations generated by the electrospray propulsion source.

Future testing will compare the redesigned gate against the original design to quantify improvements in timing precision, signal quality, and overall measurement accuracy.
# TOF spectra (before vs. after), Final assembly in the chamber, Data plots, Oscilloscope traces, Experimental setup, Performance metrics

