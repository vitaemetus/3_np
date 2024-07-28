This project is based on CHARMM36m and CHARMM-IFF force fields. GROMACS software was used for the simulation.

1. Retrieve the coordinate and topology files for 1,2-DCE through CHARMM GUI.

1.1 First of all we'll use [Ligand Reader & Modeler](https://www.charmm-gui.org/?doc=input/ligandrm) to yield all the files we need for the DCE model.
   We'll type "DCE" into "Load Ligand ID" box and the GUI will do the rest. Then we download the .tgz archive, it contains all the files we'll need further.

1.2 Now we need to convert the retrieved files to GROMACS format. For that porpose we'll use [Force Field Converter](https://charmm-gui.org/?doc=input/converter.ffconverter). We'll upload .psf and .crd files into the converter and since DCE is an unknown molecule to CHARMM-FF, we need to upload "Additional Topology and Parameter Files" (.str, .prm. and rtf, all at once). Here are the parameters we set on the next step: <img width="356" alt="image" src="https://github.com/user-attachments/assets/6e925830-bc85-449f-9f0b-bc2e77ece4ac">

