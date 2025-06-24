git config --global user.name "NamaGitHubKamu"
git config --global user.email "EmailGitHubKamu"

git clone https://github.com/NamaGitHubKamu/AgusXSS-107X.git
cd AgusXSS-107X

mv ../agusxss.py .

echo "# AgusXSS 107X
XSS Scanner otomatis by Agus 107X dari PasuruanSecTeam.

## 📌 Fitur:
- Scan XSS Reflected/Stored
- Payload auto inject
- Filter bypass
- Full branding hacker

## 🔥 Cara Pakai
\`\`\`
$ pkg install python git
$ git clone https://github.com/NamaGitHubKamu/AgusXSS-107X
$ cd AgusXSS-107X
$ python agusxss.py
\`\`\`

" > README.md

git add .
git commit -m "🔥 rilis AgusXSS 107X by PasuruanSecTeam"
git push
