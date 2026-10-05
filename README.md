# 🗺️ <team-name> Roadmaps

A community-driven collection of learning roadmaps. Browse paths for your field, or share your own so others can learn from your journey.

> **Everyone is welcome** — beginners and experienced folks alike. If you followed a path that worked for you, write it down. Someone else needs it.

---

## 📚 Tracks

| Track | Folder | Description |
|-------|--------|-------------|
| ☁️ Cloud & DevOps | [`roadmaps/cloud-devops`](./roadmaps/cloud-devops) | Linux, containers, CI/CD, IaC, cloud platforms |
| 🛠️ Data Engineering | [`roadmaps/data-engineering`](./roadmaps/data-engineering) | Pipelines, warehousing, streaming, orchestration |
| 📊 Data Science | [`roadmaps/data-science`](./roadmaps/data-science) | Statistics, ML, analysis, visualization |
| 🎨 Frontend | [`roadmaps/frontend`](./roadmaps/frontend) | HTML/CSS/JS, frameworks, performance |
| ⚙️ Backend | [`roadmaps/backend`](./roadmaps/backend) | APIs, databases, architecture, security |
| ✏️ UI/UX | [`roadmaps/ui-ux`](./roadmaps/ui-ux) | Research, design systems, prototyping |

---

## 🔍 How to Use This Repo

1. Pick your track from the table above.
2. Open the track folder and check its `README.md` for the list of available roadmaps.
3. Open any roadmap folder and follow it at your own pace.

Every roadmap lives in its own folder, with the author's name in the folder name.

---

## 🤝 How to Contribute

You do **not** need to be a Git expert. Follow these steps:

### 1. Fork the repository
Click the **Fork** button at the top right of this page.

### 2. Clone your fork
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 3. Create a branch
```bash
git checkout -b add-<topic>-roadmap
```
Example: `git checkout -b add-kubernetes-roadmap`

### 4. Add your roadmap
Create a new folder inside the right track:

```
roadmaps/<track>/<topic>-<your-name>/
├── README.md        ← your roadmap (required)
└── roadmap.png      ← image or PDF (optional)
```

Example: `roadmaps/cloud-devops/kubernetes-path-ahmed/README.md`

Start from the template: [`templates/ROADMAP_TEMPLATE.md`](./templates/ROADMAP_TEMPLATE.md)

### 5. Add it to the track index
Open `roadmaps/<track>/README.md` and add one row to the table:

```markdown
| Kubernetes Path | [@ahmed](https://github.com/ahmed) | Beginner → Intermediate | [Open](./kubernetes-path-ahmed) |
```

### 6. Commit and push
```bash
git add .
git commit -m "Add Kubernetes roadmap (cloud-devops)"
git push origin add-kubernetes-roadmap
```

### 7. Open a Pull Request
Go to your fork on GitHub and click **Compare & pull request**. Fill in the PR template. A maintainer will review it and merge it.

---

## 📏 Contribution Rules

- **Naming:** folders use `lowercase-with-dashes`, no spaces, no special characters.
- **One roadmap per folder**, with a `README.md` inside.
- **Use the template** so all roadmaps look consistent.
- **Link to free resources** whenever possible, and mention if a resource is paid.
- **Give credit:** if your roadmap is based on someone else's work, link to the source.
- **Keep it respectful and original.** Do not copy content you don't have the right to share.
- **Images:** keep them under 5 MB, and use `.png`, `.jpg`, or `.pdf`.

---

## 🧩 Roadmap Template

Copy this into your roadmap's `README.md`:

````markdown
# <Roadmap Title>

**Author:** [@your-github-username](https://github.com/your-github-username)
**Track:** Cloud & DevOps | Data Engineering | Data Science | Frontend | Backend | UI/UX
**Level:** Beginner | Intermediate | Advanced
**Estimated time:** e.g. 3 months

## 🎯 Goal
What will someone be able to do after finishing this roadmap?

## ✅ Prerequisites
- ...

## 🛤️ The Path

### Phase 1 — <Name> (Weeks 1–4)
- [ ] Topic one — [resource](https://example.com)
- [ ] Topic two — [resource](https://example.com)
**Mini project:** ...

### Phase 2 — <Name> (Weeks 5–8)
- [ ] ...

## 🧪 Projects to Build
1. ...

## 📖 Extra Resources
- Books, courses, channels, communities

## 💡 Tips & Mistakes to Avoid
- ...
````

---

## 🗂️ Repository Structure

```
.
├── README.md
├── CONTRIBUTING.md
├── templates/
│   └── ROADMAP_TEMPLATE.md
├── .github/
│   └── PULL_REQUEST_TEMPLATE.md
└── roadmaps/
    ├── cloud-devops/
    ├── data-engineering/
    ├── data-science/
    ├── frontend/
    ├── backend/
    └── ui-ux/
```

---

## 🙋 Need Help?

- Stuck with Git? Open an **Issue** and tag it `help wanted`.
- Want a track that doesn't exist yet? Open an **Issue** and suggest it.
- Found a broken link or a mistake? Send a small PR, every fix counts.

---

## 👥 Maintainers

Maintained by the **<team-name>** team. See the [Contributors](../../graphs/contributors) page for everyone who helped.

---

⭐ If this repo helped you, give it a star and share it with a friend.
