# Contributing to METU IEEE Education Materials

First of all, I genuinely, wholeheartedly congragulate you that you opened this file and really tried to improve something or create a new education. I don't know which year are you from, but I can feel the same passion I had. It's a cause worth fighting for. Your contribution and volunteering won't ever be forgotten, even if you, yourself forgot. Every contribution, even fixing a single typo matters. We always value it here. You are helping new students to learn faster and better. That's something more important than the other METU IEEE jobs in my honest opinion. May your path be prosper and your term would be even greater than mine.

## Who is this for?

Well, to whom wants to read here actually. But if you want me to go specific, this is generally for the main instructor of the whatever course it is and the contributors, or maybe some legacy enjoyers, I don't know. It depends on who you are and who you want to be. Who do you want to become in the future? A professor, a corporate slave, an unpaid open-source developer? Well I am a mixture of these three, but what matters is you actually. Not me, I will leave the club when the time comes and you will sit into the place once I sat, that's how it goes.

---

## 🛠️ How to Update the Curriculum

Well, this part is crucial, since you are updating a curriculum (or inventing your's) you got to be careful about it all the times. The success of the education program heavily relies on this. Bear that in your mind.

### 1. Updating Lectures
* All lecture materials must go into the `/lectures` directory, organized by week (e.g., `/lectures/week-01`).
* Prefer **Markdown (`.md`)** files or **Jupyter Notebooks (`.ipynb`)** over heavy PDFs so they render natively in the browser and on GitHub.

### 2. Updating Assignments
Well, this part is a little bit shaky for a while, since disappointingly GitHub Classroom is retired this August. I am trying to find a proper solution. If you are reading this line, that means that I haven't found it yet. I am sorry.

* All homework goes into the `/assignments` directory.
* **Do not push solution files** directly into the student-facing folders. Keep solutions in a separate private repository or an instructor-only branch.

### 3. Modifying the Cloud Environment (Codespaces)
Additionally, this part will be improved. If you are reading this file that early, (that would be a genuine surprise to me) I am still figuring out some enhancements that I keep the details to me.

* If the course requires a new VS Code extension or a new software package, do **not** ask students to install it manually. 
* Add it to the `.devcontainer/devcontainer.json` file. Test the container locally before merging to ensure it doesn't break the boot time for students.

---

## 🔄 The Pull Request Workflow
Even as instructors, we do not push directly to `main` (To be fair I did, but it was the first year, and I was doing it from bare metal, so I had to be fast with it. That's why. Don't do what I did.) We treat our educational materials with the same discipline as our software.

1. **Branch Out:** Create a branch for your update (e.g., `docs/update-week-3-slides`).
2. **Commit:** Use Conventional Commits (e.g., `docs: add week 3 pointers tutorial`).
3. **Review:** Open a Pull Request and have the lead instructor or Education Coordinator approve it before merging.
