# git_homework_4
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- check_lists
- Bag Reports
- SQL
- Charles
- Mobile testing

        $ git branch Jmeter; git branch сheck_Lists; git branch Bag_Reports; git branch SQL; git branch Charles; git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий

        $ git push -u -all

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

        $ git checkout Bag_Reports
        $ touch bug_report_structure.txt
        $ vim bug_report_structure.txt

4. Запушить структуру багрепорта на внешний репозиторий

        $ git add bug_report_structure.txt
        $ git commit bug_report_structure.txt -m "new_file"
        $ git push

5. Вмержить ветку Bag Reports в Main

        $ git checkout main
        $ git merge Bag_Reports -m "merge"

6. Запушить main на внешний репозиторий

        $ git push

7. В ветке CheckLists набросать структуру чек листа

        $ git checkout check_lists
        $ touch check_list.txt
        $ vim check_list.txt

8. Запушить структуру на внешний репозиторий

        $ git add check_list.txt
        $ git commit check_list.txt -m "new"
        $ git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main

        $ git pull



