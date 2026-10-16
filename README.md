# Ian Campbell

Math & CS at Georgia Tech (B.S. expected May 2028, minors in Robotics and Spanish). I build software that has to work outside the demo: production web apps, and learning-based control for robots and drones.

🌐 **[iancampbell.dev](https://iancampbell.dev)**, my personal site · [LinkedIn](https://linkedin.com/in/ian-campbell-)

## Featured project

### [RushHQ](https://github.com/icampbell47/rushhq): recruitment platform in production use
Next.js 14 · TypeScript · Supabase Postgres

A 99-member Georgia Tech fraternity used it during rush in place of legacy recruitment software, for check-in, brother ratings and bid decisions. Highlights:
- Duplicate-proof check-in from many devices at once: a Postgres function with an advisory lock, tested by firing 25 parallel requests.
- Signed, expiring sessions in place of a forgeable cookie, plus locked-down function grants and row-level security, with pgTAP tests.
- CI runs lint, typecheck, unit tests, the build and the database tests against a seeded local Supabase.

## What I'm working on

- **Undergraduate researcher, Autonomous Systems & RL (Georgia Tech):** a recurrent PPO drone-navigation policy (PyTorch, CNN+GRU) for partially observable wildfire environments, plus a thermal-aware hybrid A* planner with a reproducible benchmarking harness.
- **Software engineering consultant, Poetic:** an LLM scoring pipeline, and turning multiple prototype notebooks into a tested Python package with CI.

## Previously

- **NASA Goddard (SWE intern):** RL navigation for planetary rovers, with zero-shot sim-to-real transfer on a mobile robot.
- **HackGT 12 winner, Ming Management Training:** a React/Next.js platform with a multi-agent Gemini evaluation pipeline.

## Toolbox

**Languages:** Python, C/C++, TypeScript/JavaScript, SQL, Java, Julia, MATLAB
**Web:** React, Next.js, Node.js, Supabase/Postgres
**ML & robotics:** PyTorch, TensorFlow, scikit-learn, OpenCV, ROS 2, Gymnasium/MuJoCo
**Infra:** Docker, Linux, Git, GitHub Actions
