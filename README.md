# محتوى الملف 

- الـGit Remote.
- الـGit vs Github.
- إنشاء مستودع جديد على Github.
- الـGit Remote لربط Git بـ Github.
- رفع التحديثات على Github باستخدام Git (git push).
- تحميل التحديثات من Github باستخدام Git (git pull).


####  الـGit Remote.

الـGit Remote هو أمر يتيح لك إدارة الاتصالات بين مستودع Git الخاص بك ومستودعات Git أخرى (مثل GitHub و GitLab و Bitbucket) والتفاعل معها.

عند استخدام Git Remote ، يمكنك تعيين مستودعات بعيدة كمخزن بعيد لمشروعك المحلي ، ومن ثم استخدام Git لنسخ تعديلاتك إلى مخزن البعيد وجلب تحديثات من مخزن البعيد إلى المشروع المحلي. يمكنك أيضًا استخدام Git Remote لإنشاء نسخ احتياطية من مشروعك المحلي ومشاركتها مع آخرين عبر الإنترنت.

لإضافة remote جديد ، يمكنك استخدام الأمر git remote add مع اسم مختصر للمستودع البعيد ورابط المستودع البعيد. على سبيل المثال:

      git remote add origin https://github.com/username/repository.git
