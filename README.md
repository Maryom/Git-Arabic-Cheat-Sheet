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


__:txt in settings folder مثال على ذلك يوضح كيفية حذف جميع ملفات__
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

## : لنقل الملف من جلد إلى مجلد

```
git mv <source> <destination>
```

__:مثال على توضح نقل base.rb ➡️ lib folder__
```
git mv base.rb lib/base.rb
```

## : ويمكنك إستخدام الأمر لإعادة تسميه ملف

```
git mv <old_file_name> <new_file_name>
```

__:مثال على ذلك__
```
git mv core.java base.java
```

## : لرؤية التفاصيل السابقة للمستودع الذي تعمل عليه

```
git log
```

## :commits لرؤية التفاصيل السابقة للمستودع الذي تعمل عليه ولتحديد عدد 

```
git log -n    # n للتوضيح💡 مجرد عدد
```

__:مثال على ذلك__
```
git log -2
```

## :commits لمعرفة تفاصيل أكثر عن 

```
git log -p
```

## : لرؤية عدد من الإحصائيات بشكل مختصر 

```
git log -stat
```
