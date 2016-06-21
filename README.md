# Git-algorithmersBook-SheetCheat
This is a sheet cheat of Git book written by @algorithmers

## :لإنشـاء مسـتودع فـارغ

```
git init 
```

## :لإضافة ملف

```
git add <file_name>
```
__:مثال على ذلك__
```
git add home.php
git add contact.php
git add admin.php
```
## :لإضافة العديد من الملفات

```
git add .
```

## :للتخزيـن الفعـلي للتعديـلات و حفظها

```
git commit -m 'reason here..'
```

## :Tags لعرض قائمة

```
git tag
```

## :Tags للبحث عن 

```
git tag -l <صيغة معينة>
```

__:مثال على ذلك__
```
git tag -l "v1.7*"
```
## :Annotated Tag لإنشاء

```
git tag -a v1.8.0 -m 'version 1.8'  # للتوضيح💡 Tag name is: v1.8.0, After -m you just write a message that will be saved with the tag.
```

## :Lightweight Tag لإنشاء

```
git tag v1.8.0 
```

## :Tag لرؤية تفاصيل أكثر عن 

```
git show v1.8.0 
```

## :Unstage للتراجع ولجعل الملف بحالة

```
git reset HEAD <file_name>
```
__:مثال على ذلك__
```
git reset HEAD myCode.c
```

## : إلغاء كل التعديلات والعودة للنسخة التي كنت عليها قبل البدء في التعديل

```
git checkout -- <file_name>
```

__:مثال على ذلك__
```
git checkout -- file.java
```

## : لعرض تفاصيل عن حالة الملفات 

```
git status
```

## : للحصول على تقرير مختصر عن حالة الملفات 

```
git status --short
```

## : للحصول على تقرير مختصر حول حالة المشروع والتعديلات الحالية

```
git status -s
```

## : لحذف ملف وإلغاء متابعته

```
git rm <file_name>
git commit -m 'reason here..'
```

__:مثال على ذلك__
```
git rm myFile.py
git commit -m 'Delete myFile.py 🐍'
```


__:مثال على ذلك يوضح كيفية حذف جميع الملفات .txt in settings folder__
```
git rm settings/\*.txt
git commit -m 'Delete all .txt files in settings folder'
```

## : لحذف المتابعة مع بقاء الملف نفسه

```
git rm --cached <file_name>
```

__:مثال على ذلك__
```
git rm --cached myFile.py
```



