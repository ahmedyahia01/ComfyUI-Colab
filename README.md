[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ahmedyahia01/ComfyUI-Colab/blob/main/ComfyUI_Installer.ipynb)

# 📚 ComfyUI: دليل الإعداد الشامل للكورس

مرحباً بك في **دليل الإعداد الشامل لـ ComfyUI** 🎨  
سيقوم **دفتر العمل (Notebook)** في هذا المشروع بتجهيز بيئة عمل كاملة وقوية على **Google Colab**، مع تحميل أحدث النماذج وحل جميع المشاكل الشائعة تلقائيًا.

---

## ✨ مميزات الإعداد

هذا المشروع ليس مجرد تثبيت عادي، بل هو **بيئة عمل متكاملة** تم تصميمها بعناية لتكون:

- 📦 **متكاملة**: تحميل أحدث نموذج **Stable Diffusion 3** مع أهم الإضافات *(Custom Nodes)* مثل **ComfyUI-Manager** و **Impact-Pack** تلقائيًا.  
- 💾 **دائمة**: حفظ كل الملفات (**ComfyUI، النماذج، المخرجات**) مباشرة على **Google Drive** الخاص بك.  
- 💪 **قوية**: معالجة المشاكل الشائعة (مثل انقطاع التحميل) بطريقة ذكية ومستقرة.  
- 🖱️ **بنقرة واحدة**: بعد الإعداد الأولي، يمكنك تشغيل كل شيء عبر خلية واحدة فقط.

---

## ⚠️ متطلبات مسبقة (مرة واحدة فقط)

> يجب تنفيذ هذه الخطوات **قبل** تشغيل الكود لأول مرة.

### 1️⃣ إنشاء حساب Hugging Face  
- [إنشاء حساب جديد](https://huggingface.co) (مجانًا وسريع)

### 2️⃣ الموافقة على شروط نموذج Stable Diffusion 3  
- سجل دخولك، ثم اذهب إلى:  
  [stabilityai/stable-diffusion-3-medium](https://huggingface.co/stabilityai/stable-diffusion-3-medium)  
- وافق على الترخيص بالضغط على **Agree and access repository**.

### 3️⃣ إنشاء مفتاح وصول Hugging Face  
- من إعدادات حسابك: [صفحة المفاتيح](https://huggingface.co/settings/tokens)  
- اضغط **New token** → اختر الصلاحية **read** → **Generate a token**  
- انسخ المفتاح (يبدأ بـ `hf_...`).

### 4️⃣ إنشاء حساب ومفتاح ngrok  
- [التسجيل](https://dashboard.ngrok.com/signup) (يمكنك استخدام حساب Google)  
- بعد تسجيل الدخول، انسخ الـ **Authtoken** من:  
  [صفحة المصادقة](https://dashboard.ngrok.com/get-started/your-authtoken)  

---

## ⚙️ كيفية الاستخدام

1. **فتح الكود في Colab**  
   - اضغط زر **Open in Colab** في أعلى الصفحة.

2. **حفظ المفاتيح السرية في Colab**  
   - من القائمة اليسرى اضغط أيقونة **🔑 Secrets**  
   - أضف مفتاح Hugging Face:  
     - **Name:** `HF_TOKEN`  
     - **Value:** الصق المفتاح الخاص بك  
   - أضف مفتاح ngrok:  
     - **Name:** `NGROK_AUTH_TOKEN`  
     - **Value:** الصق مفتاح ngrok الخاص بك  

3. **تشغيل الخلايا بالترتيب**  
   - **الخلية 1:** ربط Google Drive والتحقق من المفاتيح  
   - **الخلية 2:** تثبيت ComfyUI والنماذج (قد تستغرق حتى ساعة أول مرة)  
   - **الخلية 3:** تشغيل الخادم وإنشاء رابط عام

---

## 🚑 حل المشاكل الشائعة

- **`Cannot connect to GPU backend`**  
  حصتك المجانية في Colab انتهت مؤقتًا → انتظر 12-24 ساعة أو اشترك في **Colab Pro**.

- **`address already in use` عند الخلية 3**  
  يوجد عملية قديمة → أعد تشغيل الخلية 3.

- **أخطاء ngrok أو المصادقة**  
  تأكد من كتابة اسم المتغير `NGROK_AUTH_TOKEN` بشكل صحيح.

- **Missing Models**  
  الإعداد يثبت النماذج الأساسية فقط. للحصول على نماذج إضافية استخدم **ComfyUI-Manager** من داخل الواجهة.

---

## 🎯 الهدف

هذا المشروع يهدف إلى توفير **تجربة سلسة وبلا تعقيد**.  
استمتع بالكورس ✨

---
