⚙️ Project Setup

Before starting, create and activate a virtual environment:
```
python -m venv venvSofia
# Activate it
venvSofia\Scripts\activate   # on Windows
# OR
source venvSofia/bin/activate  # on macOS / Linux
```

Then install all required dependencies:

```
pip install -r requirements.txt
```

📁 Requirements File

All necessary packages (like `numpy` and `pandas`) are listed in `requirements.txt`.
Always install them before running the notebook or any Python files.

🔄 Git Workflow

We follow a simple Developer / Gatekeeper workflow.

Developer
Create or update code locally.
Commit your changes:
```
git add .
git commit -m "Describe your changes"
```

Push to a new branch:
```
git push -u origin your-branch-name
```

Create a Pull Request (PR) on GitHub.

Gatekeeper

1. Review the PR carefully.

2. Approve and merge the branch into main.

3. Pull the latest changes locally and test that everything works.