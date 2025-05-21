# LEARNING GIT

## Commads
Commands I used to do this task:
```bash
1. ls
2. mkdir learninggit
3. ls
4. cd learninggit/
5. git status
6. git branch
7. git config --help
8. git config --list
9. git config user.name "Mirzomumin"
10. git config user.email "mirzomumin@list.ru"
11. git config --list --show-origin
12. ls 
13. cd learninggit/
14. ls
15. ls -a
16. mkdir docs folder ignored_folder
17. ls
18. cd learninggit/
19. ls
20. tocuh docs/file_1.txt docs/file_2.txt docs/file_3.txt
21. touch docs/file_1.txt docs/file_2.txt docs/file_3.txt
22. cp docs/* folder/
23. ls folder/
24. cp docs/* ignored_folder/
25. ls
26. ls docs
27. ls folder/
28. ls ignored_folder/
29. git status
30. touch .gitignore
31. echo "ignored_folder" > .gitignore 
32. cat .gitignore 
33. git status
34. git add .
35. git commit -m "feat(project structure): define initial project"
36. git status
37. git branch
38. git branch -m main
39. git branch
40. git checkout -b feature/ui main
41. git checkout main 
42. git branch feature/api
43. ls
44. cd learninggit/
45. ls
46. ls
47. cd learninggit/
48. ls
49. git log
50. git branch
51. ls
52. git branch
53. git checkout feature/api 
54. ls
55. ls docs/
56. vim docs/file_1.txt
57. cd learninggit/
58. git branch
59. ls
60. vim docs/file_1.txt 
61. git branch
62. git status
63. git add .
64. git log
65. git commit -m "feat(first text): add the first text in file"
66. git branch
67. ls
68. vim docs/file_1.txt 
69. git status
70. git add .
71. git commit -m "feat(second text) add the second text in file"
72. git branch
73. git checkout main 
74. git branch
75. git merge --no-ff feature/api -m "Merge branch 'feature/api' into main"
76. git branch
77. git remote add origin git@github.com:mirzomumin/learninggit.git
78. git push -u origin main
79. git remote --help
80. git remote remove origin 
81. git remote --help
82. git remote -v
83. git remote add origin https://github.com/mirzomumin/learninggit.git
84. git push -u origin main
85. ls
86. git branch
87. cd learninggit/
88. ls
89. git branch
90. git log 
91. git branch
92. git checkout feature/ui 
93. git branch
94. ls
95. vim docs/file_2.txt 
96. git status
97. git add docs/file_2.txt 
98. git commit -m "feat(second file): add a text in the send file of docs folder"
99. ls
100. rm folder/file_1.txt 
101. git branch
102. git status
103. git add folder/
104. git commit -m "fix(folder file): remove the first file of the folder directory"
105. git branch
106. git checkout man
107. git checkout main 
108. git rebase feature/ui 
109. git checkout feature/ui 
110. ls
111. vim docs/file_1.txt 
112. git branch
113. git status
114. git commit -m "feat(docs file): add a text into docs file"
115. git add .
116. git commit -m "feat(docs file): add a text into docs file"
117. git branch
118. git checkout main 
119. git rebase feature/ui 
120. git status
121. vim docs/file_1.txt 
122. git add .
123. git rebase --continue 
124. vim docs/file_1.txt
125. git add .
126. git rebase --continue
127. git branch
128. git tag -a v1.0.0 -m "add v1.0.0"
129. git log
130. git tag -l
131. git log --pretty=online
132. git log --pretty=oneline
133. git branch
134. git status
135. ls
136. ls folder/
137. vim folder/file_3.txt 
138. git status
139. git add .
140. git commit -m "feat(bug): add bug text into file of folder directory"
141. git revert HEAD
142. git status
143. vim folder/file_2.txt 
144. git add .
145. git commit -m "feat(bug): add second bug text into file"
146. git reset --help
147. git reset --hard HEAD~
148. git log
149. git branch
150. ls
151. vim docs/file_3.txt 
152. git status
153. git stash
154. git status
155. git stash pop
156. git add .
157. git commit -m "feat(stash text): add stash text into file"
158. git status
159. git remote add origin https://github.com/mirzomumin/learninggit.git
160. git push -u origin main
161. git checkout feature/ui 
162. git push origin feature/ui 
163. git push origin feature/api 
```
