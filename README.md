# HALFpipe Task-Based fMRI Analysis Manual

*Image-Based Meta-Analysis of Parenting Constructs and Emotion-Processing Brain Activity*

Written by Junxuan Zhao. Adapted for the Parenting IBMA project from the ENIGMA Task-Based fMRI Imaging Manual (Waller, Erk, Walter & Veer, based on the ENIGMA resting-state fMRI manual by Pozzi, Toenders, Veer, Waller, Haswell, Morey & Schmaal) and from the official HALFpipe documentation at fmri.science/halfpipe (About, Installation, and Manuals pages).

This manual assumes HALFpipe v1.3.2. Site-specific parenting-construct mappings, task contrasts, and analysis models referenced throughout are defined in your site's Site Confirmation Packet (Parenting Construct and fMRI Harmonization). Please have that document open alongside this manual.

Please address questions and comments to junxuan@student.unimelb.edu.au.

## Summary

This manual will take each of the contributing sites in the Parenting IBMA project through running HALFpipe on their local task-fMRI data, from data preparation through to the group-level summary statistics maps that will be pooled across sites for the image-based meta-analysis (IBMA).

No prior experience with HALFpipe is needed. This manual will cover everything you will need from data preparation through to the group-level summary statistics maps by following steps.

**Step 1: Prepare for data analysis**
Gather all data that you will need, including anatomical scans, functional scans, event files, parenting and demographic covariates.

**Step 2: Install a container platform**
You will need either Singularity/Apptainer or Docker to run HALFpipe.

**Step 3: Download HALFpipe & Set up Working directory**
The version 1.3.2 of HALFpipe should be downloaded, even if you have a previous version of HALFpipe.

**Step 4: Run preprocessing and Feature Extraction**
You will perform pre-processing according to pre-specified parameters and will extract first-level contrasts for each subject based on the Site Confirmation Packet that was shared with you alongside this manual.

**Step 5: Quality Assessment**
You will inspect output of HALFpipe and complete quality assessment in an interactive graphical interface following guidelines provided.

**Step 6: Group-level Analysis**
You will conduct group-level analysis for the harmonized parenting constructs based on the Site Confirmation Packet that was shared with you alongside this manual.

**Step 7: Upload Results for the IBMA — Deadline 31st December 2026**
