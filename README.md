Contains all assignments and other important material for Applied Machine Learning

How to Contribute to the Jupyter Notebook

We welcome collaborators who want to contribute improvements, analyses, or code updates to the Jupyter notebook in this repository. Please follow the steps below to propose edits safely.

🔹 1. Fork the Repository

Click Fork (top right of this repo) to create your own copy under your GitHub account.

Then, clone your fork to your local machine:

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

🔹 2. Create a New Branch

Before making changes, create a new branch to keep your updates separate:

git checkout -b notebook-updates

🔹 3. Open and Edit the Notebook

Launch Jupyter Notebook or JupyterLab:

jupyter notebook


or

jupyter lab


Navigate to the .ipynb file (for example, analysis/statistics.ipynb) and open it.
Make your edits — code updates, new visualizations, documentation, etc.

💡 Tip: Before saving, select Kernel → Restart & Run All to ensure all cells run cleanly and outputs are consistent.

🔹 4. Commit and Push Changes

Once your edits are complete:

git add analysis/statistics.ipynb
git commit -m "Updated handwashing duration analysis"
git push origin notebook-updates

🔹 5. Submit a Pull Request (PR)

On GitHub, go to your fork and click Compare & pull request.
Ensure the base repository is this project and the compare branch is your updated branch.

Please include:

A short summary of what you changed

Any new dependencies or requirements

Notes for reviewers, if applicable

🔹 6. Review and Merge

After review, your contribution will be merged into the main branch.
We appreciate clear, reproducible edits that enhance the project!
