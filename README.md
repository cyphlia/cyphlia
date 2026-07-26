<div align="center">

# Hi, I'm Kartik Amit Desai 👋

**CS Undergrad @ IIIT Raichur · Physics-Informed ML · Hamiltonian Optimization · AutoML**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/kad11)
[![Email](https://img.shields.io/badge/Email-kadat1164%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:kadat1164@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white)](https://github.com/cyphlia)

</div>

---

### What I'm working on

I build systems at the intersection of **physics and machine learning** — specifically,
what happens when you stop treating a neural network's hyperparameters as knobs
you set from outside training, and start treating them as physical objects that
**evolve alongside the weights**, governed by the same energy-conserving mathematics
that describes a pendulum or an orbiting planet.

I care as much about **proving when and why something works** — with proper
statistical testing, honest negative results, and real-world validation — as I do
about building it in the first place.

---

### 🔭 Featured Project: Hamiltonian Hyperparameter Dynamics (HHD)

**A self-tuning neural network optimizer that co-evolves weights and hyperparameters
via symplectic (Hamiltonian Monte Carlo) integration — eliminating the expensive
outer retraining loop that every standard HPO method relies on.**

```
Weights and hyperparameters, jointly, in one augmented phase space,
integrated by a leapfrog scheme, corrected by Metropolis-Hastings.
```

**The three-phase curriculum (Method C):**
`Adam Warmup` → `HMC Co-evolution` → `L-BFGS Curvature Polish`, all inside a
single training run — no throwing away 20 models to find good hyperparameters.

**Validated, not just claimed:**

| What I did | Result |
|---|---|
| Controlled physics benchmark (harmonic oscillator, 5 seeds) | **74× lower MSE** than pure Hamiltonian co-evolution alone |
| 11 standardized HPO benchmarks (HPOBench, HPOLib, NAS-Bench-201) | Friedman test *p* = 7.9×10⁻⁴; statistically tied with Optuna TPE (Nemenyi CD) |
| Real clinical data (Wisconsin Breast Cancer, Pima Diabetes) | Matched 20-trial search quality at **13–19× lower compute cost** |
| Found an untuned baseline beating tuned search on one dataset | Traced it to validation-set overfitting ("the optimizer's curse") — quantified per method, not hand-waved |
| Built NUTS (No-U-Turn Sampler) from scratch as an alternative integrator | Reported honestly when it *lost* to fixed-step leapfrog, with a concrete explanation (unadapted mass matrix) |
| Ablation study on every component | Found L-BFGS is irreplaceable (36× worse without it) — and that *more components isn't automatically better* |

I'd rather publish a method that's honestly competitive with the state of the art
than one that's dishonestly "the best" — every claim above is backed by a
significance test, not an average.

**[→ Full repo](https://github.com/cyphlia/HPO-HMC)**

---

### 🛠️ Other Projects

**Athena — Desktop Assistant**
Voice-activated agentic AI assistant for notes, tasks, app launching, email, and
calendar sync, with a PyQt interface.

**Comparative Study on the Binary Knapsack Problem**
Implemented and benchmarked 3 classical, 3 metaheuristic, and 2 quantum
algorithms for NP-hard optimization, analyzing efficiency and scalability.

**DesaiArts**
Full-stack e-commerce storefront (Next.js + Tailwind) with product listing,
filtering, and a lightweight admin/data layer, deployed on Vercel.

---

### 🧰 Tech Stack

**Languages:** ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/-C%2FC%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**ML / Scientific Computing:** ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white) scikit-learn · Optuna

**Other:** Django · Git · LaTeX · Next.js · Tailwind CSS

**Areas of interest:** Physics-informed ML · Geometric/Structure-Preserving Deep
Learning · Automated Hyperparameter Optimization (AutoML) · Bayesian Methods ·
Graph Neural Networks

---

### 🎓 Currently

- B.Tech in Computer Science & Engineering, IIIT Raichur (2023–27)
- Teaching Assistant, Data Structures & Applications, IIIT Raichur
- Founder & Coordinator, NOTES Music Club, IIIT Raichur
- Coordinator, Game-Excellence Club, IIIT Raichur

---

<div align="center">
<i>Always happy to talk physics-informed ML, AutoML, or Geometric Deep learning — feel free to reach out.</i>
</div>
