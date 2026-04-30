# Superhero Database System Documentation  

## Overview  
A version-controlled, Windows Forms-based Superhero Database System designed to support One Kick Heroes Academy HQ in managing trainee hero records, exam scores, and ranks with GitHub integration.  

## Features  
- **Add New Superhero:** Input hero details (ID, Name, Age, Superpower, Exam Score) and auto-calculate rank and threat level.  
- **View All Superheroes:** Display records in a DataGridView with calculated ranks and threat levels.  
- **Update Superhero Information:** Search by Hero ID, edit details, recalculate rank/threat level, and save updates.  
- **Delete Superhero:** Remove selected records directly from the database file.  
- **Generate Summary Report:** Calculate totals, averages, and rank distribution, saving results to `summary.txt`.  
- **Version Control with Git:** Stage, commit, and push changes to GitHub after each major modification.  

## Technical Stack  
- **C# Windows Forms:** User-friendly interface with input fields, buttons, and DataGridView controls.  
- **Text File Storage:** Records stored in `superheroes.txt` with summary reports in `summary.txt`.  
- **Git & GitHub:** Integrated version control for commits, repository management, and collaboration.  

## End-to-End Workflow (Verified)  
- **Create:** Add new superheroes with exam scores and auto-calculated ranks.  
- **Assign:** Threat levels automatically linked to ranks (Pop Quiz → Finals Week).  
- **View:** DataGridView provides full visibility of hero records.  
- **Edit:** Update hero details and recalculate rank/threat level.  
- **Delete:** Remove heroes from the system seamlessly.  
- **Report:** Generate and save summary statistics for academy oversight.  

## Compliance & Quality Assurance  
### Required Data Fields  
- **People:** Hero ID, Name, Age, Superpower, Exam Score, Rank, Threat Level.  
- **Reports:** Summary statistics including totals, averages, and rank distribution.  

### Ranking System  
- **S-Rank (81–100):** Finals Week threat.  
- **A-Rank (61–80):** Midterm Madness threat.  
- **B-Rank (41–60):** Group Project Gone Wrong threat.  
- **C-Rank (0–40):** Pop Quiz threat.  

### Test Data (Evidence)  
The application is pre-populated with sample heroes to demonstrate:  
- **Score Variation:** Heroes across all rank categories.  
- **Threat Distribution:** Proper mapping of ranks to threat levels.  
- **Summary Reports:** Accurate calculations of averages and totals.  
