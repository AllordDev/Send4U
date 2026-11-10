# سياسة الخصوصية | Privacy Policy — Send4U

**تاريخ السريان / Effective Date:** 2025  
**اسم التطبيق / Application Name:** Send4U  
**المعرف البرمجي / Package ID:** `com.github.allorddev.send4u`  
**المطور والمالك الحصري / Developer & Owner:** Allord  

---

## أولاً: باللغة العربية

### 1. نظرة عامة والتزام الخصوصية
يحترم تطبيق **Send4U** خصوصية المستخدمين بشكل كامل. صُمم التطبيق ليعمل كأداة نقل ملفات وتطبيقات ومحادثة محلية ومعالجة مستندات (PDF / Word / سبورة تفاعلية) مباشرة من جهاز إلى جهاز (**Peer-to-Peer / Local Wi-Fi & Hotspot**) دون الحاجة إلى خوادم وسيطة أو رفع أي ملفات إلى الإنترنت.

### 2. عدم جمع البيانات الشخصية (Zero Data Collection)
- **لا يقوم التطبيق بجمع أو تخزين أو مشاركة أو بيع** أي بيانات شخصية أو تعريفية عن المستخدم.
- **لا توجد خوادم سحابية وسيطة:** جميع عمليات نقل الملفات، الصور، الفيديوهات، التطبيقات (المثبتة وغير المثبتة)، الرسائل النصية والصوتية، السبورة التفاعلية، وتحويلات PDF/Word تتم حصرياً داخل نطاق الشبكة المحلية (LAN / Wi-Fi / Hotspot) بين الأجهزة التي يربطها المستخدم بنفسه، وتُحفظ مباشرة في مجلد **`/Send4U`** المستقل على جهازك.
- **لا توجد أدوات تتبع إعلانية:** التطبيق خالٍ تماماً من حزم التتبع الإعلاني أو التحليلات التجارية الخارجية.

### 3. أذونات النظام وطريقة استخدامها
يطلب التطبيق الأذونات التالية حصرياً لتشغيل الميزات التي يختارها المستخدم بنفسه:
1. **الكاميرا (`CAMERA`):** تُستخدم فقط لمسح رمز الاستجابة السريعة (QR Code) للربط الفوري بين الجهازين، ولا يتم التقاط أو حفظ أو إرسال أي صور منها.
2. **الشبكة والواي فاي والموقع التقريبي (`INTERNET`, `ACCESS_WIFI_STATE`, `NEARBY_WIFI_DEVICES`, `ACCESS_FINE_LOCATION`):** مطلوبة من نظام أندرويد لاكتشاف الأجهزة القريبة على نفس الشبكة المحلية، وفحص دعم تردد 5GHz، وتشغيل نقطة الاتصال المحلية (Local Hotspot / Web Portal).
3. **الميكروفون (`RECORD_AUDIO`):** يُستخدم حصرياً عندما يضغط المستخدم بنفسه على زر تسجيل رسالة صوتية داخل غرفة المحادثة المحلية.
4. **قراءة جهات الاتصال (`READ_CONTACTS`):** تُستخدم فقط عندما يختار المستخدم ميزة "نقل الأسماء" لتصدير جهات الاتصال التي يحددها بصيغة `VCF` إلى جهازه الآخر.
5. **إدارة الملفات وتثبيت الحزم (`MANAGE_EXTERNAL_STORAGE`, `REQUEST_INSTALL_PACKAGES`):** تُستخدم لحفظ الملفات المستلمة والمحولة مباشرة داخل مجلد **`/Send4U`** المستقل على الجهاز وتثبيت التطبيقات المستلمة بموافقة المستخدم المباشرة.

### 4. فحص التحديثات الرسمية والأمان
يتصل التطبيق برابط ملف الإصدار الرسمي (`version.json`) الخاص بالمطور على GitHub للتحقق من رقم الإصدار وصلاحية التوقيع الرقمي الرسمي للتطبيق فقط، دون إرسال أي بيانات خاصة بالمستخدم أو جهازه.

---

## Second: In English

### 1. Overview & Privacy Commitment
**Send4U** is built from the ground up with a strict **Offline-First, Zero-Tracking** architecture. All file transfers, APK sharing, voice/text chat messages, live whiteboard strokes, and PDF/Word conversions occur exclusively over your local Wi-Fi or Hotspot connection directly between your paired devices.

### 2. Zero Personal Data Collection
- **No Cloud Uploads:** Your files, photos, videos, apps, contacts, documents, and messages are never uploaded to any external server or cloud storage. Everything is saved directly into the standalone **`/Send4U`** folder on your device.
- **No Analytics or Ad Trackers:** Send4U contains zero third-party advertising SDKs, behavioral trackers, or telemetry loggers.

### 3. System Permissions Usage
All requested Android permissions are used strictly at runtime for user-initiated actions:
- **Camera:** Used exclusively for local QR code scanning to pair devices.
- **Wi-Fi / Nearby Devices / Location:** Required by Android OS APIs to discover peers on the local network, detect 5GHz band capability, and manage local Wi-Fi Hotspot connections.
- **Microphone:** Used only when actively recording a voice note in the local LAN chat room.
- **Contacts:** Used only when the user explicitly selects contacts to export/transfer as `.vcf` files.
- **Storage & Package Install:** Used to save incoming files and converted documents directly to the standalone `/Send4U` directory and install received APK bundles upon user confirmation.

### 4. Security & Official Update Verification
The application periodically performs a read-only check against the official `version.json` endpoint hosted on GitHub solely to verify the latest version number and ensure APK integrity. No user data is transmitted during this check.

---

**Copyright © 2025 Allord. All Rights Reserved.**
