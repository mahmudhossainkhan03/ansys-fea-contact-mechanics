# Finite Element Analysis (FEA) & Contact Mechanics

Structural stress evaluation, mesh convergence studies, and non-linear frictional contact simulations executed across **ANSYS Mechanical**, **Abaqus CAE**, and **PrePoMax / CalculiX**.

---

## ⚡ Key Projects Included

### 1. Sliding Block Frictional Contact & Mesh Convergence Study
* **Simulation Scope:** Non-linear contact interaction modeling and boundary constraint evaluation for contacting sliding interfaces.
* **Analysis & Verification:**
  * Configured contact formulations (Augmented Lagrange / Pure Penalty) and normal stiffness scaling.
  * Performed mesh refinement and convergence verification against hand-calculated analytical stress solutions.
  * Compiled findings into a structured LaTeX laboratory report detailing equivalent von Mises stress ($\sigma_{vm}$) distribution and contact pressure contours.

### 2. Stepped Aircraft Elevator Torque Tube Optimization
* **Simulation Scope:** Structural sizing, torsional stress analysis, and factor-of-safety (FOS) evaluation for an aircraft elevator torque tube under static loads.
* **Design Stack:** 3D CAD modeling in SolidWorks coupled with ANSYS Mechanical static structural solver.

---

## 📁 Repository Structure

```text
├── Sliding-Block-Contact-Analysis/
│   ├── Sliding_Block_Contact.wbpj   # ANSYS Workbench project file
│   ├── Mesh_Convergence_Data.xlsx   # Mesh refinement & error analysis
│   └── FEA_Lab_Report.pdf           # Complete LaTeX laboratory report
├── Aircraft-Elevator-Torque-Tube/
│   ├── Torque_Tube_Geometry.step    # SolidWorks STEP file
│   └── Static_Structural_FEA.wbpj   # ANSYS Static Structural setup
└── README.md                        # Project documentation
