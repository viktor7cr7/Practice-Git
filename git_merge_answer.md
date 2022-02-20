1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- BagReports
- SQL
- Charles
- Mobile testing

***
``` git checkout -b Postman  ```
    
```    git checkout -b Jmeter ```

```      git checkout -b CheckLists ```

``` git checkout -b BagReports ```

```git checkout -b SQL ```

``` git checkout -b Charles ```

``` git checkout -b Mobile Testing ```

***

2. Запушить все ветки на внешний репозиторий

 ``` git push origin --all ```
***

3. В ветке BagReports сделать текстовый документ со структурой баг репорта

``` git checkout Bag Reports ```

``` nano bagStructure.txt ```

***

4.  Запушить структуру багрепорта на внешний репозиторий

``` git add . ```

``` git commit -am "bagReportStructure" ```

``` git push ```

***

5. Вмержить ветку Bag Reports в Main

 ``` git checkout main ```

 ``` git merge BagReports ```

 ***

 6. Запушить main на внешний репозиторий

 ``` git add . ```

 ``` git commit - am "bagReportStructure" ```

 ``` git push ```
 ** *

 7. В ветке CheckLists набросать структуру чек листа

 ``` git checkout CheckLists ```

 ``` nano ChecklistStructure.txt ```

***
8. Запушить структуру на внешний репозиторий

``` git add . ```

``` git commit -am "CheckListStructure" ```

``` git push ``` 
***

9.  На внешнем репозитории сделать Pull Request ветки CheckLists в main

``` "Pull requests - "New pull request" - "base:main <- compare:CheckLists" - "Create pull request" ```
***
10. Синхронизировать Внешнюю и Локальную ветки Main

``` git checkout main ```

``` git pull ```
****