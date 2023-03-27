**GIT. HOMEWORK_2**
1. На локальном репозитории сделать ветки для:
```
mkdir HW_2
cd HW_2
git init
echo “kek_cheburek” > start.txt
git add .
git commit -m “added start.txt”
```
1.1	- Postman
```
git branch Postman
```
1.2	- Jmeter
```
git branch Jmeter
```
1.3	- CheckLists
```
git branch CheckLists
```
1.4	- Bag Reports
```
git branch Bag_Reports
```
1.5	- SQL
```
git branch SQL
```
1.6	- Charles
```
git branch Charles
```
1.7	- Mobile testing
```
git branch Mobile_testing
```
2. Запушить все ветки на внешний репозиторий
```
git remote add origin git@github.com:raskote/HW_2.git
git branch -M main
git push origin --all
```
3. В ветке Bag_Reports сделать текстовый документ со структурой баг репорта
```
git checkout Bag_Reports
touch structurebr.txt
nano structurebr.txt
- Title: Example
- Description: Example
- Preposition: Example
- Steps to reproduce: Example
- Expected result: Example
- Actual result: Example
- Attachments: Example
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add .
git commit -m “added structurebr.txt”
git push
```
5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge Bag_Reports
```
6. Запушить main на внешний репозиторий.
```
git push
```
7. В ветке CheckLists набросать структуру чек листа.
```
git checkout CheckLists
touch structurecl.txt
nano structurecd.txt
- ID: Example
- Title: Example
- Steps: Example
- Expected Result: Example
- Actual Result: Example
```
8. Запушить структуру на внешний репозиторий
```
git add .
git commit -m “added structurecl.txt”
git push
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
compare & pull request
merge
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull
```
