---
layout: project
title: Harvest Gondola Sifter Prototype
description: Class project on client outline for design
#image: /assets/images/PosterSketch.png
image:
thumbnail: /assets/images/final_prototype.png
#thumbnail: /fa25-portfolio-kam528-ai/assets/images/PosterSketch.png
---

## Project Navigation

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)

---

<a id="client-pitch"></a>
<h1>Client Pitch</h1>

**Team:** Tree of Hell. 
**Client(s):** Cornell CALS Extension/E&J Gallo Winery/National Grape

## Problem statement:

Currently for growers in upstate NY during the harvest process of vineyards, **Spotted Lanternfly (SLF) presence in grapes during the mechanical harvesting process** is contaminating the product. Trivial solutions are ineffective due to harvested grapes being partially liquified during collection and high quality standards of product. 

## Impact:
We address the problem at a single point in the harvest process. The single modular attachment lowers cost and enables more efficient harvest by minimizing wasted and dumped product. 

## Proposed direction:
During the harvest process before collection, separate juice from the grape-bug mixture, then separate bugs from grapes. Then, combine the grapes and juice once again in the collection. 

### Primary Concept:
**What it is:** Pressurized water tunnel to separate grapes and SLFs. Can use water pressure **(Figure 1)** or centrifugal force **(Figure 2)**. Filter juice, then filter SLFs, then remix juice/grapes.

**How it would be used:** Apparatus placed in-line between harvester and collection systems.

**Why it’s better than the status quo:** Prevents any SLFs from entering the final harvest collection and saves any excess or needed grape juice for product production.

**End-of-semester proof-of-concept:**
Prototype of water tunnel with filters. Grapes flow through and SLFs are successfully separated.

## Key risks / unknowns:
- Altering safety/functionality of the harvesters - We will research rules and regulations for harvesters, and create a modular design that fits without interfering with the harvester.
- Buildup of grapes during filtration process - We’ll ensure the prototype can manage the upper limit of the harvester’s collection rate and/or have a staging area so that it meets that standard.
- Growers are not willing or able to install our design. We will ensure grower feedback is incorporated and maximize user-friendliness by testing ease of use with strangers.

## Questions for the client:
1. **Precisely when and where are grapes partially liquified during the harvest process?**  
   We need to know when liquid is present and the state of the grapes in the grape mixture throughout the harvest to determine the best way to filter SLF out.
2. **Which harvesters (models) and designs are frequently used in upstate NY?**  
    We need to know harvester designs to decide where in the process to insert our product. Is harvesting and containing done by two different vehicles or trailers, or by one unit?
3. **How willing and able are farmers to implement new technology in harvest?**
     Rank the importance of efficiency, reliability, repairability, durability, and ease of use for the end user (1 through 5). Add any other attributes deemed critical for grower-friendly design. 

## Figure

<figure style="text-align: center; width: 100%;">
  <img src="{{ '/assets/images/PosterSketch.png' | relative_url }}" 
       alt="Preliminary sketches of prototype ideas developed so far."  
       style="width: 100%;">
  <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>Preliminary sketches of prototype ideas developed so far.</strong>
  </figcaption>
</figure>


<a id="functional-prototype"></a>
<h1>Functional Prototype</h1>

<h3>Overview</h3>

<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/prototype-main.png"
       alt="Prototype Setup"
       style="width:100%; max-width:420px; border-radius:8px;">
</figure>

<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/prototype-sketch.png"
       alt="Concept Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
</figure>

<p>The design consists of a perforated tray supported by an adjustable aluminum frame and stabilized using a cable suspension system. The perforated PVC sheet acts as the filtration surface, allowing grape juice to pass through while retaining larger solids. This sheet is supported by aluminum rods which distribute the load and prevent excessive sagging. The rods are connected to a vertical frame constructed from aluminum rectangular tubes, which provide structural support and allow for height adjustability. The height adjustment mechanism is achieved by drilling multiple holes into the vertical tubes and inserting dowel pins through aligned holes to lock the structure at different positions. This enables adaptability to different gondola heights and working conditions in the field. Aluminum edge trim is used as an interface to attach the system to a gondola, ensuring that the prototype can be integrated into a real harvesting setup.</p>

<p>The cable system plays a critical role in both load distribution and motion control. Cables connect the tray to the frame, introducing tension-based support that reduces bending stress on the rods and allows for slight compliance under load. This compliance is beneficial, as it absorbs shock when grapes are dumped onto the tray and prevents sudden structural loading. The combination of rigid members (rods and frame) and flexible members (cables) creates a hybrid structure that efficiently manages forces.</p>


<h3>Components</h3>
<br>
- PVC Perforated Sheet (24” x 24”; 0.188” Diameter Hole to Hole Center)  
  McMaster Code: 92985T53
  <br>
- luminum Rods (½” Diameter; 8’ Length); McMaster Code: 8974K28
<br>
- Aluminum Rectangular Tubes  
<br>
- Inner Tube: 1 ⅛” Height and Width; McMaster Code: 6546K5 
<br> 
- Outer Tube: 1 ⅜” Height and Width; McMaster Code: 6546K1 
<br>
- Cables (found in the lab)

<h3>Fabrication</h3>

<p>The aluminum rectangular tubes were drilled to create holes for the adjustable height mechanism, ensuring proper alignment for dowel pins. The aluminum rods and rectangular tubes were cut to size to form the tray supports and future dowel pins.</p>

<h3>Mechanical Functionality</h3>

<p>The system exhibits both vertical and lateral motion characteristics due to its partially suspended design. In the vertical direction, the tray supports the applied load through a combination of bending in the aluminum rods and tension in the cables. The cables reduce the effective load on the rods by redistributing forces to the frame, allowing the system to support higher loads without excessive deformation. Future modifications will allow an adjustable height of basket. In the lateral direction, small oscillations occur when the tray is loaded, but these are limited by the tension in the cables and the stiffness of the frame. This slight movement is beneficial, as it prevents stress concentration and allows the system to dynamically respond to uneven loading.</p>

<p>Load transfer occurs through multiple paths: the applied load is first carried by the perforated sheet, then transferred to the aluminum rods, which experience bending. From there, forces are shared between the cables (tension) and the frame (compression). This multi-path load distribution improves overall structural performance and reduces the likelihood of failure in any single component. The system is self-supporting, with the frame providing a stable base and the cables enhancing load distribution and stability.</p>

<h3>Assembly</h3>

<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/assembly-sketch.png"
       alt="Assembly Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
</figure>


<p>The assembly of the prototype was designed to be modular, adjustable, and easy to reconfigure. The primary structure consists of a telescoping frame made from aluminum rectangular tubes, where a smaller tube is inserted inside a larger tube. This nested configuration allows the inner tube to slide vertically, enabling height adjustment of the system. Once the desired height is reached, aligned holes in both the inner and outer tubes are secured using aluminum dowel pins, locking the frame in place and preventing unintended movement. After establishing the frame height, aluminum rods are positioned horizontally to support the perforated PVC tray, which is cut to size and aligned with the structure. Cables are then attached from the tray corners to the upper portions of the frame, creating a tension-based support system that helps distribute load and stabilize the tray while still allowing slight compliance. Finally, aluminum edge trim is attached to provide an interface for mounting the system onto a gondola. This assembly approach allows for quick adjustments, secure locking, and efficient setup, making it well-suited for both testing and real-world application.</p>

<h3>Design Tests</h3>

<p>To evaluate the structural performance of the prototype, a load-bearing test was conducted by distributing various weights evenly across the tray to simulate the weight of a grape harvest. Under this loading condition, the system demonstrated high strength and reliability, with minimal deflection observed in the aluminum rods and no signs of failure in the cables or frame. The load was effectively distributed through the combined action of the rods in bending and the cables in tension, confirming that the hybrid support system is capable of handling realistic operating conditions. This will continue to be used for future iterations of our prototype.</p>

<p>In addition to static loading, a forced swinging test was performed by manually displacing the tray and allowing it to oscillate. This test evaluated the system’s dynamic stability and response to sudden movements, such as those that might occur during harvesting or transport. The tray exhibited controlled oscillations without excessive amplitude, and the motion gradually damped due to cable tension and structural resistance. The oscillations were easily allowed in the desired direction and restricted in the other due to the cable design. No loosening, detachment, or instability was observed, indicating that the system maintains integrity under both static and dynamic conditions. This dynamic system will continue to be used for future iterations of our prototype.</p>

<p>The dowel system showed promise in the strength tests. However, there was some difficulty fitting the planned aluminum dowels into the slot, so pencils had to be used instead for now. This test showed us that in future iterations the dowels will need to be machined down on the lathe to have a cap and a slightly thinner diameter.</p>

<h3>Success Criteria</h3>

<p>The primary success criterion is filtration effectiveness, defined as the ability to separate at least 80% of the liquid from solid material, which can be measured by comparing the volume of collected juice to the initial mass of crushed grapes. Another key criterion is load capacity, where the system must support at least 15 kg without structural failure or excessive deformation, verified through incremental loading tests such as the rock distribution experiment. Stability is also important, with the requirement that the system does not tip or excessively shift under uneven loading conditions. Adjustability is evaluated based on the ability to change the height of the tray within one minute using the dowel pin system. Finally, ease of integration is measured by how quickly and securely the system can be attached to a gondola, with a target time of under two minutes.</p>

<p>For demonstration purposes, the prototype can be evaluated by pouring a grape-like mixture including SLF models onto the tray and visibly observing the separation of liquid through the perforated sheet. The effectiveness can be quantified by measuring the volume of liquid collected within a fixed time interval, such as 30 seconds, and by ensuring no SLF models make it through and thus contaminating the juice with the quassinoids.</p>

<h3>Future Improvements / Conclusion</h3>

<p>The prototype successfully demonstrates a functional and mechanically sound approach to separating grape juice from solids. The system is strong, adjustable, and capable of supporting realistic loads, as evidenced by the rock distribution tests. The use of a hybrid structure combining rigid and flexible elements provides effective load distribution and resilience. Our final design will incorporate an integrated motor system to actively generate controlled oscillations in the tray, enhancing the sifting behavior and improving the separation efficiency between grape juice and solids. By introducing consistent, tunable vibrations, the system will promote faster liquid flow through the perforations while preventing clogging from skins and stems. In addition, the final iteration will utilize aluminum edge trim to securely attach the structure to the field gondola. This will improve overall stability, ensure proper alignment during operation, and make the system more practical for real-world vineyard integration.</p>


<a id="client-report"></a>
<h1>Client Report</h1>

<h3>Context and Problem Statement</h3>

<p>The goal of this project is to preserve usable grape juice during harvesting by reducing contamination from spotted lanternflies (SLF). When SLF are collected along with grapes, they vintroduce contamination through the production of honeydew, a sugary waste product that coats fruit and promotes the growth of sooty mold. This contamination can make grapes unsuitable for processing, as affected fruit becomes unmarketable and cannot be used for winemaking (Ambrose and Patel).</p>

<p>As a result, vineyards experience a direct loss of usable product when contaminated grapes must be discarded. In addition, grapes and juice are measured and sold by weight, meaning that every ounce of usable product contributes directly to revenue. Any contamination that reduces the amount of usable fruit therefore results in a measurable financial loss. This issue is significant because SLF infestations have already caused major economic problems for growers by damaging crops and reducing the amount of marketable yield (Ambrose and Patel).</p>

<p>Because of this, improving separation is not just a quality issue, but also an economic one. The key challenge is to separate liquid from solid material in real time while preventing SLF and other contaminants from entering the collected juice. Our team focused on designing a system that performs this separation efficiently while operating under real field constraints. The system must support significant loads, keep up with harvesting rates, be adjustable to different setups, and integrate with a collection gondola. These requirements guided our design and testing approach.</p>

<h3>Final Prototype and Application</h3>

<p>The final prototype consists of a perforated PVC tray supported by an adjustable aluminum frame and stabilized using a cable suspension system, and enhanced with a motor-driven linkage that generates controlled vibrations. The perforated tray acts as the filtration surface, allowing grape juice to pass through while retaining larger solids, including SLF material. The tray is supported by aluminum rods that distribute the load and reduce bending under weight. These rods are connected to a vertical telescoping frame made from aluminum rectangular tubing. The height of each hook can be adjusted using a pin-based locking mechanism, allowing it to adapt to different harvesting setups. A cable system connects the tray to the upper frame, providing tension-based support. This reduces stress on the rods and allows slight controlled motion when the system is loaded. This motion helps absorb impact and improves durability when grapes are dumped onto the tray. The motor linkage system induces controlled vibrations in the tray during operation. These vibrations help prevent grape skins and other solids from clogging the perforations, allowing liquid to pass through more efficiently. This improves filtration performance and increases the amount of usable juice collected. In application, the system is mounted onto a gondola during harvesting. Grapes and SLF are deposited onto the tray, where the vibrating filtration surface allows juice to pass through while retaining grapes and contaminants. This improves both product quality and total usable yield</p>


<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/gondola.png"
       alt="Assembly Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
  <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>Harvester and Field Gondola</strong>
  </figcaption>
</figure>


<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/prototypefinal.png"
       alt="Assembly Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
    <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>Left: Prototype mounted in mock gondola; Right: view of tray</strong>
  </figcaption>
</figure>

<h3>Conclusion and Recommendation</h3>

<p>The final prototype demonstrates a functional and effective approach to reducing contamination and preserving usable grape juice during harvesting. The testing results support the performance of the system across multiple success criteria. The draining flow rate test showed that the perforated tray is capable of 3.26 ounces per second per square inch of liquid to pass through while retaining solids, confirming our first success criteria of fluid-solid separation. The static load test, which supported up to 100 pounds, and the dynamic load test, which supported the impact of 40 bolts each weighing 14.3 gram from a height of 1 meter, both demonstrated the second success criteria of supporting various harvesting loads. In addition, the measured oscillation amplitude of 2 cm and frequency of 1.11 Hz confirmed that the vibration system could reasonably satisfy the final success criteria of achieving a sieving motion in order to better separate fluids and solids and prevent clogging.</p>

<p>Together, these results indicate that the prototype is structurally reliable, stable, and capable of improving filtration efficiency, which directly increases the amount of usable juice collected. Because harvested product is measured by weight, this improvement translates to a clear economic benefit by reducing product loss caused by contamination. While the prototype performs well mechanically, further validation is needed to confirm its effectiveness in removing chemical contamination from SLF. An important next step before full implementation would be chemical testing of the collected juice to verify that contamination has been reduced to acceptable levels.</p>

<p>Based on these results, we recommend continuing development of the design with a focus on improving and refining the vibration system. One key improvement would be integrating a more controlled mechanical actuation system, such as an adjustable motor or linear actuator, to better regulate the amplitude and frequency of oscillation. This would allow the system to adapt to different grape mixtures and moisture conditions, ensuring consistent performance while preventing over- or under-vibration. Improving the actuation mechanism would also increase reliability and allow for more precise tuning of the system in real harvesting environments.In addition, longer-term field testing in vineyard conditions is recommended to evaluate durability, performance consistency, and overall effectiveness during extended use.</p>

<h3>Detailed Testing Methodology and Outcome:</h3>
<h3>Draining Flow Rate:</h3>
<p>To evaluate how efficiently liquid could pass through the filtration surface, draining flow rate was tested under two input conditions. In the first test, a water bottle was held directly above the sheet so that the surface stayed flat and the water flowed vertically through the holes. This test measured a flow rate of 3.26 ounces per second per square inch. In the second test, water was poured several inches above the sheet, allowing the flow to spread across the surface more like it would during harvesting. These tests showed that the perforated tray allows liquid to drain while keeping larger solid material on top of the surface. The results support the goal of preserving usable juice while separating out solids and possible SLF contamination.</p>


<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/watertest.png"
       alt="Assembly Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
  <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>Left: view of first test; Right: View of second test</strong>
  </figcaption>
</figure>

<h3>Static Load Capacity:</h3>
<p>To test whether the prototype could support the weight of harvested material, a static load test was conducted. Weight was added to the straining surface until the prototype reached the maximum tested load of 100 pounds. During this test, the system remained structurally sound and did not show failure under the applied load. This result shows that the frame and tray are capable of supporting a significant amount of material, which is important because the device must operate inside a gondola during harvesting.</p>

<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/statictest.png"
       alt="Assembly Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
  <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>View of capacity test at maximum weight.</strong>
  </figcaption>
</figure>

<h3>Dynamic Load:</h3>
<p>To simulate grapes falling onto the straining surface during harvesting, a dynamic load test was performed by dropping bolts from a height of 1 meter onto the tray. Each bolt weighed 14.3 grams, and 40 bolts were dropped during each trial. The bolts were used to approximate impact loading from falling grapes, which are about 5 grams each. The prototype withstood the repeated impacts without visible failure, showing that the tray and support structure can handle sudden loading during use.</p>

<div style="display:flex; gap:16px; justify-content:center; align-items:flex-start; flex-wrap:wrap; margin: 16px 0;">
  <figure style="margin:0; text-align:center; max-width:420px; width:100%;">
  <img src="/fa25-portfolio-kam528-ai/assets/images/dynamictest.png"
       alt="Assembly Sketch"
       style="width:100%; max-width:420px; border-radius:8px;">
  <figcaption style="text-align: center; font-size: 0.9em; color: #2b2b2bff;">
    <strong>View of Dynamic Load Test.</strong>
  </figcaption>
</figure>

<h3>Oscillation Amplitude and Frequency:</h3>
<p>The vibration system was tested by measuring the motion created by the motor-driven linkage. The prototype produced an oscillation amplitude of 2 cm and a frequency of 1.11 Hz. This vibration is important because it helps prevent grape skins and other solids from clogging the holes in the tray. By keeping the surface moving, the system allows juice to continue flowing through the perforations more effectively during harvesting.</p>

<h3>References</h3>

<p>Ambrose, Kevin, and Kasha Patel. “Invasive Spotted Lantern Fly Spreads Across Mid-Atlantic.” The Washington Post, 17 Sept. 2021, p. B2</p>


---