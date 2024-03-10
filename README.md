# work_with_git

## 1-4 Создать локальный репозиторий в текущей папке

![image](https://github.com/feelingod/work_with_git/assets/128130924/60da5e1c-8d71-49f7-a6eb-29a2ceb6e7e7)

![image](https://github.com/feelingod/work_with_git/assets/128130924/b787312f-fb3b-410a-9bde-ef371ff3c762)

## 5 Добавьте туда пустой текстовый документ.

![image](https://github.com/feelingod/work_with_git/assets/128130924/515ba9d7-ebf9-41c3-a6f7-de7ba3bb06f9)

## 6. Сформируйте этот документ, создавая commit для каждого абзаца, не менее 5 абзацев. 

![image](https://github.com/feelingod/work_with_git/assets/128130924/042f5e15-8918-4738-b0ed-f432fb59ca6f)

![image](https://github.com/feelingod/work_with_git/assets/128130924/b3f232df-6d0e-4ed7-85c3-fcf96e706b89)

![image](https://github.com/feelingod/work_with_git/assets/128130924/78ca90be-b46e-4a92-aa94-672e2a516664)

![image](https://github.com/feelingod/work_with_git/assets/128130924/9eba873f-c99b-4ba6-89c3-99e50fc5c497)

![image](https://github.com/feelingod/work_with_git/assets/128130924/28f20445-0fe8-4358-b161-e331457aa75a)

![image](https://github.com/feelingod/work_with_git/assets/128130924/84efac56-2b21-4cd5-972a-38e99c69c4eb)

## 7. Посмотреть статус текущего репозитория.

![image](https://github.com/feelingod/work_with_git/assets/128130924/67bcc1b6-ed84-464c-8744-ce5a876d2a13)

## 8. Добавить файл.
![image](https://github.com/feelingod/work_with_git/assets/128130924/a19e9251-3c2b-4b28-85ea-d5b066254c90)

## 9. Создать коммит, указать для него комментарий.

![image](https://github.com/feelingod/work_with_git/assets/128130924/bd432922-fa6d-4b35-9421-829f665831e4)

## 10. Посмотреть протокол коммитов.
```
C:\Users\Антон\Desktop\work\work_with_git>git log

commit 891962f577641a253546708facb4a5252548b690 (HEAD -> main, origin/main, origin/HEAD)
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 21:05:01 2024 +0600

    text2 added commit

commit 6ce96ac359b47bf0e568c48d6134b1c64bd9a824
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:42:11 2024 +0600

    5 commit

commit 3f68a84fdd2cb4a0015b16931d769a39ff8622dd
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:41:24 2024 +0600

    4 commit

commit 05adefc508e8325f9bfeb7180e4f602f804f4a46
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:40:50 2024 +0600

    3 commit

commit 27d62fa725d900bd74e1aa200e5d49aec0830cc0
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:39:58 2024 +0600

    2 commit

commit 6298fb46af8046b2a28e11899c3c3ff3763c3e6e
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:37:17 2024 +0600

    first commit

commit 5786422606c914a1e1cdb4ba1c07405e51d5a9db
Author: kaneki_ken <128130924+feelingod@users.noreply.github.com>
Date:   Wed Mar 6 19:28:14 2024 +0500

    Initial commit

```

## 11. Посмотреть изменения в файле по сравнению с последним коммитом.

```

C:\Users\Антон\Desktop\work\work_with_git>git log -p
commit 891962f577641a253546708facb4a5252548b690 (HEAD -> main, origin/main, origin/HEAD)
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 21:05:01 2024 +0600

    text2 added commit

diff --git a/text2.txt b/text2.txt
new file mode 100644
index 0000000..e69de29

commit 6ce96ac359b47bf0e568c48d6134b1c64bd9a824
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:42:11 2024 +0600

    5 commit

diff --git a/text.txt b/text.txt
index 498aa48..00746cf 100644
--- a/text.txt
+++ b/text.txt
@@ -1,4 +1,5 @@
 1 str
 2 str
 3 str
-4 str
\ No newline at end of file
+4 str
+5 str
\ No newline at end of file
:

```

## 12. Убрать изменения относительно последнего коммита из файла

![image](https://github.com/feelingod/work_with_git/assets/128130924/4b99814a-08c9-45d8-82b4-8a931802d537)

Файл откатился (на момент коммита он был пустой)

![image](https://github.com/feelingod/work_with_git/assets/128130924/b26e700a-5210-4dd4-94dd-1d43c95f785c)


## 13. Просмотреть существующие ветки.

![image](https://github.com/feelingod/work_with_git/assets/128130924/0ce93721-f092-40ba-904f-f60824e390a8)

## 14.Создать новую ветку.

![image](https://github.com/feelingod/work_with_git/assets/128130924/d6b30f65-a908-4feb-b1c6-60af99d3a665)

## 15. Переключиться на другую ветку.

![image](https://github.com/feelingod/work_with_git/assets/128130924/da92af7b-6455-4447-bcfe-3105f327fcd6)

## 16. Создать новую ветку и сразу же переключиться на нее.

![image](https://github.com/feelingod/work_with_git/assets/128130924/a64e2b82-fbca-490b-8a29-fd2579457f9e)

## 17. Удалить ветку.

![image](https://github.com/feelingod/work_with_git/assets/128130924/b2c54d57-6804-4901-96b5-4120b8087df5)

## 18. Добавить (merge) изменения из указанной ветки в текущую.

![image](https://github.com/feelingod/work_with_git/assets/128130924/2a53107a-26c9-44ac-ae98-2228c0e89c1b)

## 19. Создать конфликт.

Текст файла text2.txt для коммита 1-branch:

![image](https://github.com/feelingod/work_with_git/assets/128130924/c9dcebe3-dbd8-43c2-92b5-3de9656ae93e)

Текст для коммита main ветки (написано что для 1-branch, но я случайно перепутал и не сделал checkout)

![image](https://github.com/feelingod/work_with_git/assets/128130924/90337987-5462-4444-a929-3258415ea51e)

```
C:\Users\Антон\Desktop\work\work_with_git>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\Антон\Desktop\work\work_with_git>git add .

C:\Users\Антон\Desktop\work\work_with_git>git commit -m "branch added"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\Антон\Desktop\work\work_with_git>git push origin 1-branch
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for '1-branch' on GitHub by visiting:
remote:      https://github.com/feelingod/work_with_git/pull/new/1-branch
remote:
To https://github.com/feelingod/work_with_git.git
 * [new branch]      1-branch -> 1-branch

C:\Users\Антон\Desktop\work\work_with_git>git add .

C:\Users\Антон\Desktop\work\work_with_git>git commit -m "коммит для 1-branch"
[main da9b830] коммит для 1-branch
 1 file changed, 1 insertion(+)

C:\Users\Антон\Desktop\work\work_with_git>git branch
  1-2-branch
  1-branch
* main

C:\Users\Антон\Desktop\work\work_with_git>git log
commit da9b830b93664f32ae2db3b78a8fc758fcf87e93 (HEAD -> main)
Author: ZXC_GHOUL_KANEKI_KEN_993 <anisimovanton225@gmail.com>
Date:   Sun Mar 10 13:34:53 2024 +0500

    коммит для 1-branch

commit e30d1a41b942f325033eefb12ed260d45b255714 (origin/main, origin/HEAD)
Author: ZXC_GHOUL_KANEKI_KEN_993 <anisimovanton225@gmail.com>
Date:   Sun Mar 10 01:25:10 2024 +0500

    test commit zxc.txt added

commit 891962f577641a253546708facb4a5252548b690 (origin/1-branch, 1-branch, 1-2-branch)
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 21:05:01 2024 +0600

    text2 added commit

commit 6ce96ac359b47bf0e568c48d6134b1c64bd9a824
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:42:11 2024 +0600

    5 commit

commit 3f68a84fdd2cb4a0015b16931d769a39ff8622dd
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 20:41:24 2024 +0600

    4 commit
	

C:\Users\Антон\Desktop\work\work_with_git>git add .

C:\Users\Антон\Desktop\work\work_with_git>git commit -m "коммит для 1-брэнч (теперь точно)"
On branch 1-branch
nothing to commit, working tree clean

C:\Users\Антон\Desktop\work\work_with_git>git push origin 1-branch
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 392 bytes | 130.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/feelingod/work_with_git.git
   891962f..82be874  1-branch -> 1-branch

C:\Users\Антон\Desktop\work\work_with_git>


```


## 20. Посмотреть в каких файлах есть конфликты.

```

C:\Users\Антон\Desktop\work\work_with_git>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\Антон\Desktop\work\work_with_git>git merge 1-branch
Auto-merging text2.txt
CONFLICT (content): Merge conflict in text2.txt
Automatic merge failed; fix conflicts and then commit the result.

C:\Users\Антон\Desktop\work\work_with_git>git push origin main
Everything up-to-date

C:\Users\Антон\Desktop\work\work_with_git>

```
![image](https://github.com/feelingod/work_with_git/assets/128130924/427779a8-2c2c-40ba-87e6-f437b2652429)


## 21. Устранить конфликты.

![image](https://github.com/feelingod/work_with_git/assets/128130924/54b45d05-fee9-45f9-9557-b5a3ce4fc90a)

## 22. Переключиться на указанный коммит.

```
C:\Users\Антон\Desktop\work\work_with_git>git log
commit d1c90c41a58c79761363b4ce5c3874dd92b787ec (HEAD -> main, origin/main, origin/HEAD)
Merge: da9b830 82be874
Author: ZXC_GHOUL_KANEKI_KEN_993 <anisimovanton225@gmail.com>
Date:   Sun Mar 10 13:50:26 2024 +0500

    исправлен конфликт при слиянии веток

commit 82be874d64aee89e756dba11bb83f8f03712e52d (origin/1-branch, 1-branch)
Author: ZXC_GHOUL_KANEKI_KEN_993 <anisimovanton225@gmail.com>
Date:   Sun Mar 10 13:38:28 2024 +0500

    теперь точно коммит для 1-branch

commit da9b830b93664f32ae2db3b78a8fc758fcf87e93
Author: ZXC_GHOUL_KANEKI_KEN_993 <anisimovanton225@gmail.com>
Date:   Sun Mar 10 13:34:53 2024 +0500

    коммит для 1-branch

commit e30d1a41b942f325033eefb12ed260d45b255714
Author: ZXC_GHOUL_KANEKI_KEN_993 <anisimovanton225@gmail.com>
Date:   Sun Mar 10 01:25:10 2024 +0500

    test commit zxc.txt added

commit 891962f577641a253546708facb4a5252548b690 (1-2-branch)
Author: unknown <superuser@it-112a-13.MEPHI3.LESNOY>
Date:   Wed Mar 6 21:05:01 2024 +0600


C:\Users\Антон\Desktop\work\work_with_git>git checkout  82be874
Note: switching to '82be874'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 82be874 теперь точно коммит для 1-branch

C:\Users\Антон\Desktop\work\work_with_git>


```

## 23. Сделать ребазирование (rebase) текущей ветки.

![image](https://github.com/feelingod/work_with_git/assets/128130924/9249df4a-88ee-403d-8aba-9c7cff75cbcd)

![image](https://github.com/feelingod/work_with_git/assets/128130924/e625c326-2cda-4a88-9a2e-eba36efba905)

![image](https://github.com/feelingod/work_with_git/assets/128130924/5ad9a218-07cb-4aa9-945d-2e00a9505f37)

```
C:\Users\Антон\Desktop\work\work_with_git>git branch
  1-2-branch
  1-branch
* main

C:\Users\Антон\Desktop\work\work_with_git>git rebase 1-branch
Auto-merging text2.txt
CONFLICT (content): Merge conflict in text2.txt
error: could not apply da9b830... коммит для 1-branch
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply da9b830... коммит для 1-branch

C:\Users\Антон\Desktop\work\work_with_git>

```

![image](https://github.com/feelingod/work_with_git/assets/128130924/8b72f73d-aadf-4ddb-89d6-468eab50126a)

![image](https://github.com/feelingod/work_with_git/assets/128130924/906ff49f-6113-470c-8a69-2df66eeb3af5)

```
C:\Users\Антон\Desktop\work\work_with_git>git status
interactive rebase in progress; onto 815953b
Last commands done (2 commands done):
   pick e30d1a4 test commit zxc.txt added
   pick da9b830 коммит для 1-branch
No commands remaining.
You are currently rebasing branch 'main' on '815953b'.
  (all conflicts fixed: run "git rebase --continue")

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   text2.txt


C:\Users\Антон\Desktop\work\work_with_git>

```

## 24. Удалить ветку.

```
C:\Users\Антон\Desktop\work\work_with_git>git branch -d 1-branch
Deleted branch 1-branch (was 815953b).

C:\Users\Антон\Desktop\work\work_with_git>git push --delete origin 1-branch
To https://github.com/feelingod/work_with_git.git
 - [deleted]         1-branch

C:\Users\Антон\Desktop\work\work_with_git>

```

## 25. Пропустить текущий конфликтный коммит и перейти к следующему.

```
C:\Users\Антон\Desktop\work\work_with_git>git add .

C:\Users\Антон\Desktop\work\work_with_git>git commit -m "next commit"
On branch main
Your branch is up to date with 'origin/main'.

Last commands done (2 commands done):
   pick e30d1a4 test commit zxc.txt added
   pick da9b830 коммит для 1-branch
No commands remaining.
You are currently editing a commit while rebasing branch 'main' on '815953b'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

nothing to commit, working tree clean

C:\Users\Антон\Desktop\work\work_with_git>git push
Everything up-to-date

C:\Users\Антон\Desktop\work\work_with_git>

```

![image](https://github.com/feelingod/work_with_git/assets/128130924/b91e8bb7-e645-4ac7-9355-bf1f11e356a8)

## 26. Отправить изменения из локального репозитория для указанной ветки в удаленный (дистанционный).

```
C:\Users\Антон\Desktop\work\work_with_git>git add .

C:\Users\Антон\Desktop\work\work_with_git>git commit -m "26 branch change added"
[main 0a4d71c] 26 branch change added
 1 file changed, 1 insertion(+)
 create mode 160000 work_with_git

C:\Users\Антон\Desktop\work\work_with_git>git push origin 1-2-branch
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for '1-2-branch' on GitHub by visiting:
remote:      https://github.com/feelingod/work_with_git/pull/new/1-2-branch
remote:
To https://github.com/feelingod/work_with_git.git
 * [new branch]      1-2-branch -> 1-2-branch

C:\Users\Антон\Desktop\work\work_with_git>
```


## 27. Забрать изменения из репозитория, для которого были созданы удаленные ветки по умолчанию.
```
C:\Users\Антон\Desktop\work\work_with_git>git branch
  1-2-branch
* main

C:\Users\Антон\Desktop\work\work_with_git>git fetch

C:\Users\Антон\Desktop\work\work_with_git>git branch
  1-2-branch
* main

C:\Users\Антон\Desktop\work\work_with_git>git branch -a
  1-2-branch
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/create-branch
  remotes/origin/main

C:\Users\Антон\Desktop\work\work_with_git>git checkout create-branch
Switched to a new branch 'create-branch'
branch 'create-branch' set up to track 'origin/create-branch'.

C:\Users\Антон\Desktop\work\work_with_git>git merge main
Already up to date.

```

## 28.Забрать изменения удаленной ветки из репозитория основной ветки по умолчанию.

![image](https://github.com/feelingod/work_with_git/assets/128130924/4f31223d-fceb-4600-a2c6-322cdbd7b4d3)

```
C:\Users\Антон\Desktop\work\work_with_git>git fetch

C:\Users\Антон\Desktop\work\work_with_git>git branch
  1-2-branch
* main

C:\Users\Антон\Desktop\work\work_with_git>git branch -a
  1-2-branch
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/create-branch
  remotes/origin/main

C:\Users\Антон\Desktop\work\work_with_git>git checkout create-branch
Switched to a new branch 'create-branch'
branch 'create-branch' set up to track 'origin/create-branch'.

C:\Users\Антон\Desktop\work\work_with_git>git merge main
Already up to date.

C:\Users\Антон\Desktop\work\work_with_git>git fetch
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 944 bytes | 49.00 KiB/s, done.
From https://github.com/feelingod/work_with_git
   d1c90c4..967789c  main       -> origin/main

C:\Users\Антон\Desktop\work\work_with_git>git branch -a
  1-2-branch
* create-branch
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/create-branch
  remotes/origin/main

C:\Users\Антон\Desktop\work\work_with_git>git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 1 commit, and can be fast-forwarded.
  (use "git pull" to update your local branch)

C:\Users\Антон\Desktop\work\work_with_git>git merge origin/create-branch
Updating d1c90c4..3205e01
Fast-forward
 new_file | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 new_file

C:\Users\Антон\Desktop\work\work_with_git>git commit -m"28_punkt"
On branch main
Your branch and 'origin/main' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

Last commands done (2 commands done):
   pick e30d1a4 test commit zxc.txt added
   pick da9b830 коммит для 1-branch
No commands remaining.
You are currently editing a commit while rebasing branch 'main' on '815953b'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

nothing to commit, working tree clean

C:\Users\Антон\Desktop\work\work_with_git>

```

## 29.Создать копию репозитория.

```

C:\Users\Антон\Desktop\work\work_with_git>git clone https://github.com/feelingod/work_with_git.git

```










