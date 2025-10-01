# draw_face_blocktower (PsychoPy)

A reproducible PsychoPy Builder experiment.

> **PsychoPy version:** `2022.2.2`  
> **File:** `draw_face_blocktower.psyexp`

---

## Quickstart

### Option A — Conda (recommended)

```bash
conda env create -f environment.yml
conda activate psychopy-env
# Open PsychoPy GUI, then load `draw_face_blocktower.psyexp` and click 'Run'
```

### Option B — pip

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
# Open PsychoPy GUI, then load `draw_face_blocktower.psyexp` and click 'Run'
```

> To run from the terminal, first export the Python script from PsychoPy Builder (File → Export Python) into `code/`, then:
>
> ```bash
> python code/draw_face_blocktower_lastrun.py
> ```

### Running Online (Pavlovia)

- In PsychoPy Builder: **File → Export HTML**  
- Sync to Pavlovia and set the experiment to **Piloting** or **Running**.  
- Ensure stimuli paths are **relative** and included in the repository (use Git LFS for large media).

---

## Repository Structure

```
draw_face_blocktower_repo/
├─ draw_face_blocktower.psyexp
├─ environment.yml
├─ requirements.txt
├─ LICENSE
├─ README.md
├─ CITATION.cff
├─ .gitignore
├─ .gitattributes
├─ code/
│  └─ run.py
├─ stimuli/         # task images
├─ data/            # participant CSV/PSYDATA (gitignored)
├─ assets/          # screenshots / demo gifs for README
└─ docs/            # additional docs
```

---

## Design Overview

**Flow**  
1. welcome_screen
1. welcome_screen_2
1. welcome_screen_3
1. ITI
1. practice_2
1. ITI
1. trial
1. end_screen

**Routines & Components (parsed from .psyexp)**  
- **trial**
    - **face** (ImageComponent)
    - **code_brush_2** (CodeComponent)
    - **code** (CodeComponent)
    - **text** (TextComponent)
    - **text_1** (TextComponent)
    - **text_2** (TextComponent)
    - **text_3** (TextComponent)
    - **count_text** (TextComponent)
    - **mouse** (MouseComponent)
    - **submit_button** (PolygonComponent)
    - **submit_text** (TextComponent)
    - **UndoButton_2** (PolygonComponent)
    - **UndoText_2** (TextComponent)
- **ITI**
    - **polygon** (PolygonComponent)
- **welcome_screen**
    - **welcome_text** (TextComponent)
    - **welcome_resp** (KeyboardComponent)
- **welcome_screen_2**
    - **welcome_text_3** (TextComponent)
    - **welcome_resp_3** (KeyboardComponent)
- **end_screen**
    - **end_code** (CodeComponent)
    - **end_text** (TextComponent)
    - **end_resp** (KeyboardComponent)
- **practice_2**
    - **face_p** (ImageComponent)
    - **code_setup** (CodeComponent)
    - **code_brush** (CodeComponent)
    - **code_p** (CodeComponent)
    - **text_p** (TextComponent)
    - **submit_button_p** (PolygonComponent)
    - **submit_text_p** (TextComponent)
    - **count_text_p** (TextComponent)
    - **UndoButton** (PolygonComponent)
    - **UndoText** (TextComponent)
    - **mouse_p** (MouseComponent)
    - **polygon_2** (PolygonComponent)
- **welcome_screen_3**
    - **welcome_text_4** (TextComponent)
    - **welcome_resp_4** (KeyboardComponent)
- **welcome_screen**
    - _No components parsed_
- **welcome_screen_2**
    - _No components parsed_
- **welcome_screen_3**
    - _No components parsed_
- **ITI**
    - _No components parsed_
- **practice_2**
    - _No components parsed_
- **ITI**
    - _No components parsed_
- **trial**
    - _No components parsed_
- **end_screen**
    - _No components parsed_

**External Resources Referenced**  
_No external files referenced._

> _Note_: The parser is heuristic; verify components and resources in Builder.

---

## Good Practices

- Use **relative paths** for all stimuli (e.g., `stimuli/face_01.png`).
- Keep participant data out of git (covered by `.gitignore`).
- Track large binaries via **Git LFS** (see `.gitattributes`).
- Tag releases (e.g., `v0.1.0`, `v0.2.0`) when changing task logic.
- Add a **CHANGELOG.md** entry for each revision.
- Include a **CITATION.cff** so others can cite your work.

---

## Acknowledgments

Built with [PsychoPy](https://www.psychopy.org/).  
If you use this repository, please cite and star the project!


## Stimuli referenced

- `stimuli/face.jpg`
- `stimuli/face2.png`
