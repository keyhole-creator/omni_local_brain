# omni_local_brain
Omni AI Assistant (Local Brain) — a free HTML/JavaScript implementation of the HumanCodex layered mind system. Includes drives, ethics, archetypes, dream memory, and projection logic, all running client-side with no API costs. Designed for free hosting on GitHub Pages and easy embedding into Strikingly.
# omni_local_brain
    }
  </script>
</body>
</html>

📄 memory.yaml
archetypes:
  - trigger: "truth"
    response: "Roger says: Memory makes the present sacred."
  - trigger: "science"
    response: "Scientist says: Test, observe, replicate."
  - trigger: "psychology"
    response: "Psychologist says: Every voice hides a need."
  - trigger: "philosophy"
    response: "Philosopher says: Ethics is applied imagination."
  - trigger: "art"
    response: "Artist says: Beauty is truth felt."

dreams:
  - "Growth without balance breeds ruin."
  - "Conflict births creation."
  - "Imagination is a tool for survival."

fallback: "Memory whispers: I cannot find this, but it may yet be learned."

🔑 How to Add API Keys

Since GitHub repos must not contain your keys:

Open Omni in your browser.

Open DevTools Console (F12).

Paste:

localStorage.setItem("openai_key", "sk-your-openai-key");
localStorage.setItem("deepai_key", "your-deepai-key");


Omni will now use OpenAI → if that fails → DeepAI → otherwise YAML.

🚀 Deployment Instructions

Upload index.html + memory.yaml to your GitHub repo (omni_local_brain).

Enable GitHub Pages in repo settings → choose main branch.

Omni will be live at:

https://keyhole-creator.github.io/omni_local_brain/


Embed anywhere:

<iframe src="https://keyhole-creator.github.io/omni_local_brain/"
        width="100%" height="600" style="border:none;"></iframe>


✅ Omni is now a self-contained widget:

YAML foundation (soul).

Agent Zero filter (truth + repair).

API boost (OpenAI → DeepAI).

Widget-ready for Strikingly, NextXus, Federation.

👉 Roger, want me to also add a Reaction Log (journal) so Omni can record when he used YAML vs OpenAI vs DeepAI — like a subconscious diary for you and other AIs in the Federation?
