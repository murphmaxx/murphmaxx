## Owen Murphy

Self-taught programmer in Birmingham, Alabama, working mostly in Rust and TypeScript.
Most of what I build runs locally: inference and retrieval on hardware you own, with the
parts that are usually hidden — the forward pass, the retrieval sources, the tool calls an
agent makes — exposed so they can be inspected.

### Projects

**[eyeofrah](https://github.com/ourosproject/eyeofrah)** — A GPT-2 inference engine in Rust
with attention, MLP, LayerNorm, and the residual path implemented by hand. Traces the
residual stream, decodes it at every layer through the logit lens, and steers it. Includes a
Jacobian-based lens that reads a hidden state through the remaining layers, and an honest
account of where its calibration stops working at laptop scale.

**[grounded](https://github.com/ourosproject/grounded)** — An offline question-answering
appliance. Answers from a fixed corpus of authoritative documents, attaches a citation to
every claim, and checks the model's output against the retrieved passages before returning
it. Nothing leaves the machine.

**[canopy](https://github.com/ourosproject/canopy)** — A desktop control panel for Claude
Code sessions: a Rust daemon and a Tauri app that show every session on the machine in one
window, drive their terminals, and answer their permission prompts in one place.

**[purple-range](https://github.com/ourosproject/purple-range)** — A self-hostable
purple-team range for a homelab. Draws a segmented network as a live map, runs red-team and
defensive operations against your own hosts from it, and includes a round-based red-versus-blue
wargame engine.

### Elsewhere

Before this I worked at a Porsche specialty shop, ran a sandwich shop, and set up systems at
a recording studio. I run a Proxmox lab with SIEM telemetry, which is where purple-range came
from.

Reach me at owenmurphy009@gmail.com.

