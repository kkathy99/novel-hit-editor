[novel-hit-editor](https://github.com/YOUR_GITHUB_USERNAME/novel-hit-editor)
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo YOUR_GITHUB_USERNAME/novel-hit-editor \
  --path . \
  --name novel-hit-editor
cd /Users/kk/.codex/skills/novel-hit-editor

git init
git add .
git commit -m "Initial novel hit editor skill"

git branch -M main
git remote add origin https://github.com/你的用户名/novel-hit-editor.git
git push -u origin main
