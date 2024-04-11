# frameworks

This repository will be used to maintain a living spreadsheet that compares existing 
frameworks (simulation software packages) for Open Virtual Tissues. We welcome input and feedback from the community  via Issues, Pull requests, or email.

Some relevant publications that have compared frameworks include: 

* Hybrid Automata Library: A flexible platform for hybrid modeling with real-time visualization (2020).
Rafael R. Bravo, Etienne Baratchart, Jeffrey West, Ryan O. Schenck, Anna K. Miller, Jill Gallaher, Chandler D. Gatenbee, David Basanta, Mark Robertson-Tessi, Alexander R. A. Anderson. https://doi.org/10.1371/journal.pcbi.1007635

* A Review of Cell-Based Computational Modeling in Cancer Biology (2019).
    John Metzcar, Yafei Wang, Randy Heiland, Paul Macklin. https://doi.org/10.1200/CCI.18.00069
    
* Comparing individual-based approaches to modelling the self-organization of multicellular tissues (2017).
    James M. Osborne, Alexander G. Fletcher, Joe M. Pitt-Francis, Philip K. Maini, David J. Gavaghan. https://doi.org/10.1371/journal.pcbi.1005387


Abbreviations/definitions:<br>
* CA - Cellular Automata
* CP - Cellular Potts
* CB - Center Based
* VT - Voronoi Tessellation
* VM - Vertex Model
* Checkpointing - ability to save/reload state if a restart/continuation is needed

Note: we avoid the category of "extensible" until/unless we have an agreed upon definition. Obviously, any framework can be said to be extensible if a person is willing to write and integrate the necessary code.

<br>
<table>
  <tr>
    <td></td>
    <td colspan="5">Class</td>
    <td colspan="3">PDE</td>
    <td>Lng</td>
    <td>APIs</td>
    <td>GUI</td>
    <td>Web</td>
    <td colspan="2">Intracellular</td>
    <td>Checkpointing</td>
    <td colspan="3">Operating system</td>
    <td colspan="2">Parallelism</td>
  </tr>
  <tr>
    <td></td>
    <td>CA</td>
    <td>CP</td>
    <td>CB</td>
    <td>VT</td>
    <td>VM</td>
    <td colspan="2">Diffusion</td>
    <td>Advection</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>Boolean</td>
    <td>ODEs</td>
    <td></td>
    <td>Win</td>
    <td>Mac</td>
    <td>Linux</td>
    <td>OpenMP</td>
    <td>MPI</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>isotropic</td>
    <td>anisotropic</td>
  </tr>
  <tr>
    <td>CompuCell3D</td>
    <td></td>
    <td>&check;</td>
    <td></td>
    <td></td>
    <td></td>
    <td>&check;</td>
    <td></td>
    <td></td>
    <td>C++</td>
    <td>Python</td>
    <td>&check;</td>
    <td>*1</td>
    <td>&check;</td>
    <td>&check;</td>
    <td></td>
    <td>&check;</td>
    <td>&check;</td>
    <td>&check;</td>
    <td>&check;</td>
    <td></td>
  </tr>
    <tr>
    <td>PhysiCell</td>
    <td></td>
    <td></td>
    <td>&check;</td>
    <td></td>
    <td></td>
    <td>&check;</td>
    <td></td>
    <td></td>
    <td>C++</td>
    <td>C++</td>
    <td>&check;</td>
    <td>*2</td>
    <td>&check;</td>
    <td>&check;</td>
    <td></td>
    <td>&check;</td>
    <td>&check;</td>
    <td>&check;</td>
    <td>&check;</td>
    <td></td>
  </tr>
    <tr>
    <td>Morpheus</td>
    <tr>
    <td>Chaste</td>
    <tr>
    <td>Tissue Forge</td>
    <tr>
    <td>Artistoo</td>
    <tr>
    <td>HAL</td>
  </tr>
</table>

<br>
<ul>
<li> *1 - various models are available on https://nanohub.org </li>
<li> *2 - various models are available on https://nanohub.org </li>
</ul>

