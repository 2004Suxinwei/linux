cd "C:\Users\su xin wei\Downloads\Git-2.45.2-64-bit.exe"
echo "# linux" >> README.md
git init
git add README.md
git add main.py
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/2004Suxinwei/linux.git
git push -u origin main
