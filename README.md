# 🧠 مترجم فوري باستخدام Hugging Face وGradio

## 🧩 وصف المشروع
تطبيق ويب بسيط يتيح للمستخدمين ترجمة النصوص بين اللغتين **العربية** و**الإنجليزية** باستخدام نماذج مدربة مسبقًا من منصة Hugging Face. يعتمد على واجهة تفاعلية مبنية بـ Gradio.

---

## 🧠 النموذج المستخدم
تم استخدام نموذجين من مكتبة 🤗 Transformers:

- من الإنجليزية إلى العربية: [`Helsinki-NLP/opus-mt-en-ar`](https://huggingface.co/Helsinki-NLP/opus-mt-en-ar)
- من العربية إلى الإنجليزية: [`Helsinki-NLP/opus-mt-ar-en`](https://huggingface.co/Helsinki-NLP/opus-mt-ar-en)

---

## 🖼️ لقطة شاشة للواجهة

![واجهة التطبيق](Screenshot%202025-05-07%20071037.png)


---

## ⚙️ طريقة التشغيل
1. تأكد من تثبيت المكتبات التالية:
   ```bash
   pip install transformers gradio
## ✅ رابط Google Colab جاهز 
[🌐 رابط إلى الكود](https://colab.research.google.com/drive/111Mb5g6V8hA-8bkXK4-Pj2TRHo6kpTPU#scrollTo=RuTEGPAe5G_h)
