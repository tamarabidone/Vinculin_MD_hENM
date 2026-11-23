Structural and Coordinate Files (.pdb)
protein.pdb / average.pdb: Representative coordinate files or time-averaged structures extracted from the simulation trajectory.
Trajectories and Logs
*.trr: Trajectory files containing coordinates, velocities, and/or forces (e.g., eigenvectors from covariance analysis).
covar.log: Log file generated during covariance matrix / Principal Component Analysis (PCA).
3. Quantitative Analysis Outputs (.xvg)
All .xvg files are plain-text tabular files generated via GROMACS analysis tools, which can be plotted using Grace, Python (Matplotlib), or NumPy:
ca_rmsd.xvg / protein_rmsd.xvg / rmsd.xvg: Root Mean Square Deviation (RMSD) calculated for Alpha-carbons or the whole protein over time, tracking structural stability.
ca_rmsf.xvg: Root Mean Square Fluctuation (RMSF) per residue, showing local flexibility and dynamic regions.
ca_gyrate.xvg: Radius of gyration, measuring the compactness and overall folding/unfolding behavior of the protein structure over time.
sasa.xvg / res_sasa.xvg: Solvent Accessible Surface Area (SASA) calculated globally or residue-by-residue.
eigenvalues.xvg: Eigenvalues corresponding to eigenvectors from Essential Dynamics / PCA analysis.
mindist.xvg: Minimum distance between specified groups (useful for tracking interactions or unbinding events).
num_contacts.xvg: Number of atomic or residue-residue contacts formed over the course of the simulation.
