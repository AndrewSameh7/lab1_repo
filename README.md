https://andrewsameh7.github.io/lab1_repo/
ssh-keygen -t ed25519 -C "andrewsameh2003@gmail.com"
cat ~/.ssh/id_ed25519.pub
mkdir lab1_repo
cd lab1_repo
git init
touch name.txt
nano name.txt
Andrew Sameh
git add name.txt
git commit -m "add full name"
git remote add origin git@github.com:AndrewSameh7/lab1_repo.git
git push origin master
