
Comandos utilizados: 

1. $ git clone https://github.com/jtorova5/devjumpers.git
2. $ cd devjumpers
3. $ touch README.md
4. $ git status
5. $ git add .
6. $ git commit -m "commit inicial"
7. $ git push
8. $ touch privado.txt
9. $ mkdir privada
10. $ touch .gitignore
11. $ git status
12. $ git add .
13. $ git commit -m "Ignorar archivos"
14. $ touch 1.txt
15. $ git branch v0.2
16. $ git checkout v0.2
17. $ touch 1.txt
18. $ touch 2.txt
19. $ git status
20. $ git add .
21. $ git commit -m "Agregando 1.txt en main y 2.txt en v0.2"
22. $ git push --set-upstream origin v0.2
23. $ git checkout v0.2
24. $ git status
25. $ git add .
26. $ git commit -m "Actualizando 1.txt en v0.2"
27. $ git checkout main
28. $ git merge v0.2

Ramas con merge: main  (git branch --merged)
Ramas sin merge: v0.2  (git branch --no-merged)

29. git add .
30. git commit -m "conflictos resueltos"
31. $ git merge v0.2
32. $ git branch -D v0.2
33. $ git log --oneline --decorate --all --graph

image.png

34. $ git list



