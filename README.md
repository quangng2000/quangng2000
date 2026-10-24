# Quang Nguyen

**ML research** · [Website](https://quangng2000.github.io/)

I focus on machine learning research. My projects explore program compilation into transformer components, speech restoration with pretrained audio representations, language-model steering with learned twisting functions and sequential Monte Carlo, and formal proofs of the mathematical foundations of learning.

I'm also a **contributor and maintainer of [LemmaScript](https://github.com/midspiral/LemmaScript)**, a verification toolchain for TypeScript.

## Research interests

- Program compilation and neuro-symbolic learning in transformers
- Speech restoration, audio representations, and mean-flow generative models
- Probabilistic inference and language-model steering with twisted SMC
- Probabilistic modeling and formal verification of machine learning foundations

## Selected work

<table>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/reuse-apple/">
        <img src="assets/research/reuse-apple.svg" width="260" alt="RE-USE Apple: offline speech enhancement with a shared Swift, MLX, and Metal inference engine.">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/quangng2000/reuse-apple">RE-USE Apple</a></h3>
      <p>An independent Swift / MLX / Metal port of NVIDIA NemotronLabs RE-USE for offline speech enhancement, using NVIDIA's pretrained 9.61M model through a Mac CLI and an iPhone/iPad app target.</p>
      <p>M4 Pro GPU inference verified. The iPhone/iPad build passes; physical-device validation is pending.</p>
      <p><a href="https://github.com/quangng2000/reuse-apple">Code</a> · <a href="https://quangng2000.github.io/projects/reuse-apple/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/h-wavjepa/">
        <img src="assets/research/h-wavjepa-three-latent-spaces.png" width="260" alt="Proposed H-WavJEPA architecture with fine, intermediate, and coarse latent spaces, separate predictors, EMA targets, and per-level losses.">
      </a>
      <br><sub>Proposed forecasting design; illustrative horizons.</sub>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/quangng2000/h-wavjepa">H-WavJEPA</a></h3>
      <p>Hierarchical audio representation research with three learned latent spaces, EMA targets, and a PyTorch Lightning + Hydra training workflow.</p>
      <p><a href="https://github.com/quangng2000/h-wavjepa">Code</a> · <a href="https://quangng2000.github.io/projects/h-wavjepa/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/riftco-transformer/">
        <img src="assets/research/cajal-pipeline.svg" width="260" alt="Cajal-lite program compiled through linear type checking and a multilinear map into programmed linear attention.">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/quangng2000/riftco-transformer">Cajal Compiler to Transformer Heads</a></h3>
      <p>Compiling typed Cajal-lite programs into programmed transformer components, including linear-attention heads, and combining them with learned components.</p>
      <p><a href="https://github.com/quangng2000/riftco-transformer">Code</a> · <a href="https://quangng2000.github.io/projects/riftco-transformer/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/temf-wavjepa-film/">
        <img src="assets/research/temf-wavjepa-film.gif" width="260" alt="Animated toy illustration of FiLM conditioning and TEMF mean-flow generation.">
      </a>
      <br><sub>Toy method illustration; not trained speech output.</sub>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/quangng2000/temf-wavjepa-film">TEMF + WavJEPA-Nat (FiLM)</a></h3>
      <p>A speech-restoration research prototype combining frozen WavJEPA-Nat features, FiLM conditioning, and TEMF mean-flow generation.</p>
      <p><a href="https://github.com/quangng2000/temf-wavjepa-film">Code</a> · <a href="https://quangng2000.github.io/projects/temf-wavjepa-film/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/smc-steering/">
        <img src="assets/research/smc-steering.svg" width="260" alt="A learned twisting function guides sequence proposals, followed by importance weighting and adaptive resampling.">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://quangng2000.github.io/projects/smc-steering/">SMC Steering with Learned Twisting Functions</a></h3>
      <p>Inference-time language-model steering with contrastive twist learning, importance weighting, and adaptive SMC resampling.</p>
      <p><a href="https://quangng2000.github.io/projects/smc-steering/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <sub>Input</sub><br>
      <a href="https://quangng2000.github.io/projects/rmfsr/">
        <img src="assets/research/rmfsr-input.png" width="260" alt="Input speech spectrogram from the RMFSR repository demonstration.">
      </a>
      <br><sub>20 inference steps</sub><br>
      <a href="https://quangng2000.github.io/projects/rmfsr/">
        <img src="assets/research/rmfsr-nfe20.png" width="260" alt="Output speech spectrogram from the same RMFSR demonstration after 20 inference steps.">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/quangng2000/rmfsr">RMFSR</a></h3>
      <p>An independent experimental implementation of MeanFlow speech restoration, with PyTorch models and training and evaluation tools.</p>
      <p><a href="https://github.com/quangng2000/rmfsr">Code</a> · <a href="https://quangng2000.github.io/projects/rmfsr/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/lean-elbo/">
        <img src="assets/research/lean-elbo.svg" width="260" alt="ELBO decomposition and lower bound for finite, strictly positive probability distributions.">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/quangng2000/lean-elbo">ELBO in Lean 4</a></h3>
      <p>A Lean 4 formalization of the evidence lower bound for finite, strictly positive probability distributions.</p>
      <p><a href="https://github.com/quangng2000/lean-elbo">Code</a> · <a href="https://quangng2000.github.io/projects/lean-elbo/">Project details</a></p>
    </td>
  </tr>
  <tr>
    <td width="32%" valign="top">
      <a href="https://quangng2000.github.io/projects/lemmascript/">
        <img src="assets/research/lemmascript.svg" width="260" alt="Annotated TypeScript passes through LemmaScript to Dafny or Lean 4 for formal verification.">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/midspiral/LemmaScript">LemmaScript</a></h3>
      <p><strong>Contributor and maintainer.</strong> A verification toolchain for TypeScript, with Dafny and Lean 4 backends.</p>
      <p><a href="https://github.com/midspiral/LemmaScript">Code</a> · <a href="https://github.com/midspiral/LemmaScript/blob/main/GETTING_STARTED.md">Documentation</a> · <a href="https://quangng2000.github.io/projects/lemmascript/">Project details</a></p>
    </td>
  </tr>
</table>

More project notes and demonstrations are on my [website](https://quangng2000.github.io/).
