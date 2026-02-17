# gpu-selection-dashboard
Developed an interactive decision-support dashboard to evaluate and recommend a cloud GPU configuration for a startup ML workflow.

The tool compares 18 RunPod GPU options across:

Hourly cost

VRAM capacity

Rank-based relative training performance

Performance-per-dollar tradeoffs

Key functionality includes:

Global VRAM eligibility filtering to enforce model memory constraints

Parameter-driven dynamic ranking by cost, speed, or memory

Cost vs performance visualization to identify Pareto-efficient options

This analysis directly supported a final GPU recommendation by quantifying tradeoffs between budget constraints and performance tier.

Live dashboard: (https://public.tableau.com/app/profile/georgia.thomas2122/viz/GPUSelectionDashboard/Dashboard1?publish=yes&showOnboarding=true)
