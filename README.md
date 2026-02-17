# GPU Selection Dashboard
Developed an interactive Tableau dashboard to evaluate and recommend an optimal cloud GPU configuration for a startup ML training workflow.

### Problem
The team needed to select a RunPod GPU for model training under budget and VRAM constraints.
The decision required balancing:
- Hourly cost ($/hr)
- VRAM capacity (GB)
- Relative training speed
- Performance-per-dollar tradeoffs

I built a structured evaluation framework to quantify tradeoffs and justify a recommendation.

### Solution
I designed an interactive dashboard that:
- Filters GPUs by minimum required VRAM (global constraint)
- Dynamically ranks GPUs by cost, speed, or memory
- Visualizes the cost vs. relative training speed tradeoff
- Highlights Pareto-efficient options under different constraints

The analysis compares 18 RunPod GPU configurations and allows stakeholders to adjust constraints in real time.

### Outcome

Using this framework, I recommended RTX 4090 as the optimal balance of:
- Sufficient VRAM for model size
- Strong relative training performance among lower-cost GPUs

The dashboard provided transparent justification for the final infrastructure decision.

### Dashboard Preview
<img width="1470" height="921" alt="Screenshot 2026-02-17 at 2 05 36 PM" src="https://github.com/user-attachments/assets/c7092c72-e5f7-4745-a0ca-8cd1d92bb92c" />

### Live Dashboard

View the interactive dashboard here: https://public.tableau.com/app/profile/georgia.thomas2122/viz/GPUSelectionDashboard/Dashboard1
