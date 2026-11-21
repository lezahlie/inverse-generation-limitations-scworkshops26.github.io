
<h1 id="publication">Limitations of Generative Inverse Design for Scientific Simulations</h1>

<h2 id="links">Quick Links</h2>

- [Read the Paper](#read-paper)
- [Presentation Slides](#presentation)
- [Project Code](#project-code)
- [Citations](#citations)

<h2 id="read-paper">Read the Paper</h2>

> **Limitations of Generative Inverse Design for Scientific Simulations**  
> Leslie Horace, Vanessa Job, Sharmistha Chakrabarti, Nathan DeBardeleben  
> SC Workshops '26 | Chicago, IL, USA | November 15, 2026
> DOI: `TBA` | LA-UR: `LA-UR-26-26810`

- **IEEE DOI:** https://doi.ieeecomputersociety.org/10.1109/SCW72768.2026.00178


<h2 id="presentation">Presentation Slides</h2>

  - **SC Workshop: AI4S 2026 Presentation:** [Download Slides](./documents/horace-animated-presentation-scworkshops26.ppsx)
    > LA-UR: `LA-UR-26-30019`
  

<h2 id="project-code">Project Code</h2>

- **GitHub Repository:** Link will be added once available.

<h2 id="citations">Citations</h2>


<h3 id="acm-reference-format">IEEE Reference Format</h3>

> L. Horace, V. Job, S. Chakrabarti and N. DeBardeleben, "Limitations of Generative Inverse Design for Scientific Simulations," in SC26-W: Workshops of the International Conference for High Performance Computing, Networking, Storage and AnL. Horace, V. Job, S. Chakrabarti and N. DeBardeleben, "Limitations of Generative Inverse Design for Scientific Simulations," in SC26-W: Workshops of the International Conference for High Performance Computing, Networking, Storage and Analysis, Chicago, IL, USA, 2026, pp. 1404–1412, doi: 10.1109/SCW72768.2026.00178.


<h3 id="acm-reference-bibtex">IEEE Reference BibTeX</h3>

```bibtex
@inproceedings{Horace2026Limitations,
  author    = {Horace, Leslie and Job, Vanessa and Chakrabarti, Sharmistha and DeBardeleben, Nathan},
  title     = {Limitations of Generative Inverse Design for Scientific Simulations},
  booktitle = {SC26-W: Workshops of the International Conference for High Performance Computing, Networking, Storage and Analysis},
  year      = {2026},
  pages     = {1404--1412},
  publisher = {IEEE Computer Society},
  address   = {Los Alamitos, CA, USA},
  month     = nov,
  doi       = {10.1109/SCW72768.2026.00178},
  url       = {https://doi.ieeecomputersociety.org/10.1109/SCW72768.2026.00178},
  keywords  = {Computer simulation; generative AI; inverse design; scientific computing},
  abstract  = {Generative inverse design for scientific simulations addresses a many-to-one problem: generating distinct inputs whose forward simulations approximate a target output. Our prior work generated image-based initial conditions directly, but simulations often construct initial conditions at runtime from configuration variables. We shift the task upstream by generating variables whose effects propagate through intermediate representations before producing the final output. We use a deterministic heat-diffusion proxy with Cosine Phase and Perlin Noise geometry functions that create diverse material-layout patterns. Conditional normalizing flows generate input variables conditioned only on observed final states, and the resulting simulated outputs are evaluated against the corresponding targets. Variable-inclusion ablations isolate geometry and thermal variables, while posterior-factorization ablations compare full-joint, chained-joint, and disjoint decompositions. Results show error arises primarily when modeling geometry variables, whereas posterior factorization provides little improvement over baselines. These findings suggest the final outputs may not retain enough information about upstream variables and intermediate representations.}
}
```