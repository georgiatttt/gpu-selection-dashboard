# gpu-selection-dashboard
Developed an interactive dashboard to evaluate and recommend a cloud GPU configuration for a startup ML workflow.

The tool compares 18 RunPod GPU options across:
- Hourly cost
- VRAM capacity
- Rank-based relative training performance
- Performance per dollar tradeoffs 

Key functionality includes:
- Global VRAM eligibility filtering to enforce model memory constraints
- Dynamic ranking by cost, speed, or memory
- Cost vs performance visualization to identify Pareto-efficient options

This analysis directly supported a final GPU recommendation by quantifying tradeoffs between budget constraints and performance tier.

<img width="1470" height="921" alt="Screenshot 2026-02-17 at 2 05 36 PM" src="https://github.com/user-attachments/assets/c7092c72-e5f7-4745-a0ca-8cd1d92bb92c" />

### Live dashboard: 
https://public.tableau.com/app/profile/georgia.thomas2122/viz/GPUSelectionDashboard/Dashboard1?publish=yes&showOnboarding=true
