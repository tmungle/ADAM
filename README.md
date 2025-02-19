# Automated Dose Advice Method (ADAM)
Clinical decision support system prototype for dosing 6-MP and MTX during maintenance therapy phase of acute lymphoblasitc leukemia treatment.

## Summary

Acute lymphoblastic leukemia (ALL) studies across the globe have shown
that delivering optimal maintenance therapy (MT) is crucial to achieve
better treatment outcomes [\[1\]](#ref-schmiegelow2014mercaptopurine).
Delivering optimal MT includes prescribing maximum tolerated doses of
6-mercaptopurine (6MP) and methotraxate (MTX) based on patient’s blood
counts (absolute neutrophil count (ANC), platelet count (PLT) and
hemoglobin (HB)). In view of this, the ADAM was developed to
analyse and visualize the MT data (ANC/PLT/HB/6MP/MTX) for a given patient at any center[^1] and suggested doses. This work was part of my PhD thesis [\[2\]](#ref-mungle2020modelling). It was developed considering the ICiCLe-ALL-14 protocol [\[3\]](#ref-das2022protocol) as default wherein the dosing rule were modified acorss the year as per the clinical needs. 

## References

<div id="refs" class="references csl-bib-body">

<div id="ref-schmiegelow2014mercaptopurine" class="csl-entry">

<span class="csl-left-margin">\[1\] </span><span
class="csl-right-inline">K. Schmiegelow, S. N. Nielsen, T. L. Frandsen,
and J. Nersting, “Mercaptopurine/methotrexate maintenance therapy of
childhood acute lymphoblastic leukemia: Clinical facts and fiction,”
*Journal of pediatric hematology/oncology*, vol. 36, no. 7, p. 503,
2014.</span>

</div>

<div id="ref-mungle2020modelling" class="csl-entry">

<span class="csl-left-margin">\[2\] </span><span
class="csl-right-inline">T. D. Mungle, “Modelling clinical decision
processes to optimise maintenance chemotherapy in children with acute
lymphoblastic leukaemia,” [PhD thesis](https://github.com/tmungle/allMT/blob/master/PhD_Thesis_14MM91R12.pdf), IIT Kharagpur, 2020.</span>

</div>

<div id="ref-das2022protocol" class="csl-entry">

<span class="csl-left-margin">\[3\] </span><span
class="csl-right-inline">N. Das *et al.*, “Protocol for ICiCLe-ALL-14
(InPOG-ALL-15-01): A prospective, risk stratified, randomised,
multicentre, open label, controlled therapeutic trial for newly
diagnosed childhood acute lymphoblastic leukaemia in india,” *Trials*,
vol. 23, no. 1, pp. 1–20, 2022.</span>

</div>

</div>

[^1]: The thesis work [\[2\]](#ref-mungle2020modelling) was then continued at
    TTCRC, Tata Medical Center, Kolkata by me as postdoctoral scholar till March 2023. During this time, we partnered with Tata Consultancy Services, India at TTCRC to rebuild the ADAM. I had opportunity to work with a great team - TTCRC- Dr. Shekhar Krishnan, Ananya Mahadevan, Manash Gogoi, Dr. Vaskar Saha; TMC - Dr. Niharendu Ghara; TCS: Amit Misra, Sayam Kundra, Anju Goel, Amit Saxena.
