🚀 ZabHub Pro
Professional GitHub Code Pusher & Repository Manager

📝 عن البرنامج (About)
ZabHub هو أداة سطح مكتب متطورة مبنية بإطار عمل Electron، مصممة خصيصاً للمبرمجين الذين يرغبون في رفع وتحديث ملفاتهم البرمجية على مستودعات GitHub بسرعة واحترافية دون الحاجة لاستخدام أوامر Git المعقدة في كل مرة. يتميز البرنامج بواجهة مستخدم "Neon" عصرية توفر تجربة مريحة وعملية.

✨ المميزات (Features)
OAuth Integration: تسجيل دخول آمن ومباشر عبر حسابك في GitHub.

Repo Auto-Fetch: جلب قائمة مستودعاتك تلقائياً بمجرد الدخول.

Smart Path Handling: معالجة ذكية للمسارات لمنع أخطاء الـ Slashes.

Update Mode: إمكانية تحديث ملف موجود بالفعل عبر جلب الـ SHA تلقائياً.

Modern UI: واجهة زجاجية (Glassmorphism) مع تأثيرات النيون.

🛠️ طريقة الاستخدام (How to Use)
تسجيل الدخول (Login):

عند فتح البرنامج، اضغط على زر LOGIN WITH GITHUB.

سيفتح المتصفح ليطلب منك الصلاحيات، وافق عليها ثم عد للبرنامج.

إعداد الرفع (Setup):

اختر المستودع (Repository) المطلوب من القائمة المنسدلة.

اكتب مسار المجلد (Folder Path). ملاحظة: لا تبدأ المسار بـ / (مثال: اكتب src/js وليس /src/js/).

اكتب اسم الملف (Filename) مع الامتداد (مثال: index.js).

الرفع والتحديث (Push):

قم بلصق الكود الخاص بك في المحرر.

إذا كان الملف موجوداً مسبقاً وتريد تعديله، تأكد من تفعيل خيار "تحديث ملف موجود".

اضغط على SEND TO REPOSITORY وانتظر رسالة النجاح ✅.

📦 المتطلبات التقنية (Tech Stack)
Framework: Electron.js.

Styling: Tailwind CSS.

Backend: Node.js & Express (for OAuth callback).

API: GitHub REST API.

⚠️ ملاحظة أمنية (Security Note)
هذا التطبيق يستخدم OAuth2 للوصول إلى مستودعاتك بشكل آمن. لا يتم تخزين كلمات مرورك، والتوكن (Token) يستخدم فقط لجلسة العمل الحالية.

Developed with 💜 by Zakaria Barkawi (HZ Digital)
“Building the future of web tools, one line of code at a time.”s
