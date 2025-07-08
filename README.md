# OKT3-Antibody-Humanization
Wet lab protocol for transplant immunology using AHG-CDC assay
# Humanization of Anti-CD3 Antibody Using Protein Language Models

This project was undertaken during my M.Sc. Virology dissertation at Jamia Millia Islamia. The aim was to reduce the immunogenicity of murine OKT3 monoclonal antibody by computational humanization using protein language models.

## 🔧 Tools & Techniques Used
- MODELLER: Homology modeling of antibody structures
- AbRSA: Identification of CDR regions
- BIOPHI + SAPIENS: Protein language models for antibody humanization
- PyMOL: Visualization and binding interface mapping
- AMBER: Molecular Dynamics Simulations (200–300 ns)
- CPPTRAJ: Post-MD analysis (RMSD, RMSF, hydrogen bonds)

## 📊 Key Analyses
- DOPE score and Ramachandran plot validation
- MM/GBSA and MM/PBSA free energy calculations
- Binding energy mapping per residue

## 💡 Outcome
The humanized OKT3 showed reduced binding energy (-51 kcal/mol) compared to murine OKT3 (-66 kcal/mol), while retaining potential efficacy for therapeutic applications.

📁 `Final Thesis Presentation MSc Viro 2024.pdf` — Complete slide deck  
📂 `images/` — Include plots like RMSD, binding site diagrams, etc.
# Humanization of OKT3 Monoclonal Antibody

This repository documents the computational humanization of OKT3, a murine monoclonal antibody that binds CD3 on T-cells. The project involves sequence retrieval, structural modeling, and humanness scoring.

## 🧬 Tools & Techniques
- **BIOPHI** – Humanness score prediction
- **AlphaFold2** – Structure prediction
- **PyMOL** – Structural visualization
- **CDR and Framework Identification** – Based on sequence alignment and structural positioning

## 📂 Repository Contents
- `OKT3_sequence.fasta` – Original antibody sequence
- `BIOPHI_results.txt` – Humanness score output
- `OKT3_humanized_model.pdb` – Structure of the humanized antibody
- `Notes.md` – Observations, decision points, and challenges

## 🔍 Next Steps
- Affinity maturation using Rosetta or EVmutation
- Molecular Dynamics (MD) simulations using GROMACS or AMBER
- Experimental validation through lab-based assays

## ✍️ Author
**Juveria Rehman**  
M.Sc. in Virology | Computational Structural Biology | Antibody Engineering
