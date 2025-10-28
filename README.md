# 🧠✨ GNN: Where the Graph Meets the Neural! 🚀

> A lightweight, **organized learning lab** for my Graph Neural Networks (GNN) journey.  
> Minimal top-level clutter — everything is neatly tucked under `Phases/` and `workspace/`.  
> ⚠️ **No videos or heavy files** are stored here — only references, notes, and my experiments!  

---

## 🎯 **Purpose**
To create a single home for my GNN learning — structured like a course & lab notebook, so that **future me** can easily revisit, reproduce, and reflect.  

---

## 🗂️ **Top-Level Layout**
📁 **Phases/** — ordered learning path (01 → 10). Each phase is modular and progressive.  
📁 **workspace/** — my creative playground:
- 🧾 `notebooks/` → Jupyter or Colab experiments  
- 🧠 `models/` → trained model checkpoints  
- 📊 `outputs/` → metrics, plots, logs  
- 🧮 `scripts/` → runnable `.py` scripts  
- 📚 `docs/` → detailed notes, derivations  
- 📦 `data/` → preprocessed datasets  

> 💡 Only *leaf folders* (no subfolders inside) have a `README.md` describing that topic.

---

## 🎥 **Referencing Courses (No Video Uploads)**
Each leaf `README.md` should include a **reference line** like this:
```
Reference: LinkedIn — Advanced Graph Neural Networks 2024 — C:\Users\Kessler\Downloads\LinkedIn\02 - Message Passing\01 - Message Passing.mp4
```
This lets me track my learning without storing the actual video.

---

## 📘 **Leaf README Template**
```
# 📁 <Folder Name>

**Purpose:** Briefly describe what this folder is about.

**Reference:** Course name and local video path  
Example: LinkedIn — Intro to GNNs — C:\Users\Kessler\Downloads\IntroGNN\lesson1.mp4

**Notes / TODOs:**
- Key idea: Message passing = Aggregate ➡️ Transform ➡️ Update
- TODO: Implement simple GCN layer under workspace/scripts/gcn_layer.py
```

---

## 🧾 **Naming Conventions**
- 🧪 Notebooks → `phase02_message_passing.ipynb`  
- 🧱 Scripts → `phase03_gcn_train.py`  
- 📈 Outputs → `exp01_cora_loss.png`  
- 🧠 Models → `exp01_cora_gcn.pt`  
- 🗓️ Use lowercase_with_underscores and prefix filenames with phase or experiment ID.  

---

## ⚙️ **Experiment Folder Example**
```
workspace/outputs/exp01_cora_gcn/
  ├── config.yml
  ├── metrics.csv
  ├── loss_curve.png
  └── notes.md
```

**Example `config.yml`:**
```yaml
name: exp01_cora_gcn
model: GCN
dataset: Cora
epochs: 200
lr: 0.01
notes: baseline GCN test run
```

---

## 🧹 **.gitignore Suggestions**
```
workspace/models/*
workspace/outputs/*
workspace/data/raw/*
__pycache__/
*.pyc
.ipynb_checkpoints/
```
> ✅ Keep the repo light and reproducible!

---

## 💻 **Quick Start (Windows PowerShell)**
```powershell
cd "GNN-Where-the-Graph-Meets-the-Neural"
git init
git add .
git commit -m "Initial learning structure ready 🚀"
```

---

## 🧭 **Workflow**
1. Pick a phase in `Phases/`
2. Add your local course/video reference in its leaf README  
3. Write notes → Implement ideas in notebooks or scripts  
4. Run experiments → Log config + results in `workspace/outputs/`  
5. Commit & push changes frequently!

---

## 🔍 **Tips**
- Search inside all leaf READMEs to find references quickly.  
- Keep experiment configs (`config.yml`) small but detailed.  
- Add a comment header for any borrowed code snippet:
  ```python
  # Source: LinkedIn - Advanced GNNs (2024) — adapted by Kessler
  ```

---

## 🧑‍🔬 **TODO Checklist**
- [ ] Create environment file: `workspace/docs/env.yml`
- [ ] Add first phase reference notes  
- [ ] Implement first GCN layer under `workspace/scripts/`  
- [ ] Train baseline GCN on Cora and save results  

---

## 💡 **Motto**
> “Graphs connect everything — now it’s my turn to connect the dots.” 🕸️

---

🎉 *Stay curious. Stay consistent. Stay neural.*  
— *Kessler*
