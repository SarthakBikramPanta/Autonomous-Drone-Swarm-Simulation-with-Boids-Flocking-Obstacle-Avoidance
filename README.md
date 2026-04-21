# Autonomous-Drone-Swarm-Simulation-with-Boids-Flocking-Obstacle-Avoidance
Implemented a multi-agent autonomous swarm simulation in Python using Boids flocking algorithms and artificial potential fields for obstacle avoidance, modeling emergent collective behavior in unmanned aerial systems

Multi-agent swarm simulation with real-time interactive controls.
Implements Boids flocking algorithms and artificial potential field obstacle avoidance.

## Try it

Open in Colab: https://colab.research.google.com/drive/1j3P_U33xEI426h7yKkNHLfO5o9xCg_cg?usp=sharing
Or download `python file` and open it 

## What it does

- **Boids flocking** — each drone applies alignment, cohesion, and separation rules
- **Obstacle avoidance** — artificial potential fields push drones away from obstacles
- **Click to move target** — click anywhere on the canvas to redirect the swarm
- **Live sliders** — tune flocking parameters in real time without restarting
- **Add/remove obstacles** — dynamically change the environment

## Parameters you can control

| Slider | Effect |
|--------|--------|
| Drones (N) | Number of agents in the swarm |
| Max speed | How fast drones can travel |
| View range | How far each drone can sense neighbours |
| Separation range | Minimum personal space before repulsion |
| Cohesion | How strongly drones cluster together |
| Alignment | How strongly drones match neighbour heading |
| Target pull | How aggressively the swarm chases the target |
| Obstacle push | Strength of obstacle avoidance force |

## Tech stack

Python · JavaScript · HTML5 Canvas · Google Colab

## Files

| File | Description |
|------|-------------|
| `drone_swarm_sim.py` | Colab notebook — run to launch simulation |
| `drone_swarm_sim.html` | Standalone file — open in any browser |
| `interactive.gif` | Standalone file — open in any browser |
| `MIT License` | License |

