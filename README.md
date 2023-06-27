# Counting operators in Effective Field Theories

I wrote my bachelor thesis at Charles University (for additional information see [thesis information](#thesis-information)).\
It can also be found on $\textsf{arXiv}$ [2211.05759 [hep-th]](https://arxiv.org/abs/2211.05759), and $\textsf{inSpire-HEP}$ [2180439](https://inspirehep.net/literature/2180439).

The main purpose of this repository is to provide the [accompanying Mathematica notebook](#accompanying-texttt-mathematica-notebook). 

More convenient links to view (and download) the PDF files: 
- the revised version of the thesis — [CountingInEFT.pdf](https://jdujava.github.io/CountingInEFT/CountingInEFT.pdf)
- the original version of the thesis — [CountingInEFT_original_version.pdf](https://jdujava.github.io/CountingInEFT/CountingInEFT_original_version.pdf)
- the presentation for the seminar — [CountingInEFT_presentation.pdf](https://jdujava.github.io/CountingInEFT/CountingInEFT_presentation.pdf)

## Quick preview
![dual1](https://user-images.githubusercontent.com/19737748/185472953-90eb8a5b-f098-4be4-9ea7-86a7dfe70dba.png)
![dual2](https://user-images.githubusercontent.com/19737748/185472956-4e6b1275-c334-40f9-9672-73aa4a815fb2.png)
![dual3](https://user-images.githubusercontent.com/19737748/185472960-1698f524-f867-430a-ad3a-455973a7588c.png)
![dual4](https://user-images.githubusercontent.com/19737748/185472963-b27635fe-110e-4c26-b1bf-27c4020d156d.png)

## Thesis information

**Title**: Counting operators in Effective Field Theories

**Author**: Jonáš Dujava

**Institute**: Institute of Particle and Nuclear Physics

**Supervisor**: Mgr. Petr Vaško, Ph.D., Institute of Particle and Nuclear Physics

**Abstract**: When applying physical calculations to the real world, it is always necessary to make some approximations. In the context of field theories, in particular the quantum field theories used in particle physics, a systematic treatment of this problem is provided by the framework of Effective Field Theories. Working in a given energy range, it is enough to consider only a couple of particles, while the existence of the rest only contributes some corrections. This is reflected in the structure of Effective Field Theory Lagrangians given as perturbation series, which are in general composed of all possible operators consistent with locality, unitarity, and symmetry assumptions. Obviously, it is advantageous to work with a minimal set of operators covering all physical phenomena, however the construction of the operator basis is very hard in general. Simpler step is to at least count all independent operators with a given number of derivatives and particle fields. To this end, the generating function (termed the Hilbert series) is introduced, with coefficients precisely being the number of independent operators of a given type. One can consider only scalar operators, that is Lorentz and gauge invariant operators, moreover consistent with other additional symmetries. To count independent operators it is furthermore necessary to handle various relations between them, induced namely by equations of motion, integration by parts, and finite-dimensionality conditions. It turns out that by virtue of understanding the transformation properties of operators, group theory together with the representation theory provide useful tools to calculate the Hilbert series. The main idea is to construct all possible operators along with corresponding group characters (which characterize their transformation properties), and project out only independent scalar operators using the character orthogonality. Big part of this thesis is focused on developing the important theory of Lie group representations, which is later necessary to derive the formula for the Hilbert series. Finally, the group theoretical formalism is applied to count operators for a single scalar field, and also a more complex case of the electromagnetic field.

**Keywords**: Classical field theory, Effective field theory, Group theory, Lie groups,
Representation theory, Schur character orthogonality relations, Hilbert series

## Accompanying $\texttt{ Mathematica notebook}$

The actual computations of Hilbert series are usually *gigantic*, and can be found in the notebook `CountingInEFT.nb`, written using `Mathematica 13.2`. It is featured in [Wolfram Community](https://community.wolfram.com/) forum, see [Counting operators in Effective Field Theories](https://community.wolfram.com/groups/-/m/t/2757059), but it is better to download it and view it locally.
