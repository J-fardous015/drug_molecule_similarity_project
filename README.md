#Drug Molecule Similarity Project

This is a small project in which I compared the chemical structures of a few common drugs to determine how similar they are.
I used Python and RDKit to convert SMILES into molecules, create fingerprints, calculate Tanimoto similarity, and visualize the results. And I did it as a friendly cheminformatics project.

I used Colab for this mini project.

🔹 Molecules I chose:

Aspirin

Paracetamol

Ibuprofen

Caffeine

Metformin

These were chosen just for practice.

🔹 What the Project Does

Reads molecule names and SMILES

Converts each SMILES into an RDKit Mol object

Generates Morgan fingerprints

Calculates similarity between every pair of molecules

Creates a similarity matrix

Shows all molecules in a grid

Draws a heatmap of similarity values

Saves the results in a CSV file

Shows the top most similar molecule pairs

🔹 Output Files

After running the notebook, you’ll get:

molecule_grid.svg — pictures of all molecules

heatmap.png — similarity heatmap

drug_similarity.csv — similarity values in table form

🔹 How to Run

Just open and run the Jupyter/Colab notebook:

drug_similarity.ipynb


Everything will run step-by-step.

✨ Why I Built This

I’m exploring AI and cheminformatics, and I wanted to start with something simple:
Compare drug structures and visualize their similarity.

👤 Author

Jannatul Fardous
Learning cheminformatics and AI for drug discovery.
