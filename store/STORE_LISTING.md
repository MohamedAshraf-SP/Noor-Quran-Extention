# Chrome Web Store listing — نور / Noor (v1.3.0)

Copy each block into the matching field of the Developer Dashboard.

---

## 1. Package
Upload: `store/nour-1.3.0.zip`

The store name and short description come from `_locales/` automatically (Arabic default + English, Urdu, Indonesian, Malay, Turkish, French).

## 2. Store listing tab

**Category:** Lifestyle
**Language:** Arabic (add English as a second listing language)

### Detailed description — Arabic

```
نور — رفيقك اليومي مع القرآن الكريم والأذكار والصلاة، في متصفحك.

📖 المصحف الشريف
• ١١٤ سورة بالرسم العثماني مع التفسير الميسر
• الاستماع آية بآية مع تظليل الآية المتلوّة (١٢ قارئاً)
• البحث في الآيات، العلامات، ومتابعة القراءة من حيث توقفت

🎧 أكثر من ٢٤٠ قارئاً
• جميع قراء mp3quran بكل الروايات: حفص، ورش، قالون وغيرها
• تشغيل متتابع، تكرار، تحميل MP3، وقائمة مفضلة
• يستمر الصوت بعد إغلاق نافذة الإضافة

📻 إذاعات وقنوات القرآن مباشرة
• إذاعة القرآن الكريم من القاهرة، إذاعة الشارقة للقرآن، السعودية، مكة المكرمة، الكويت، الأردن، عُمان، البحرين، الجزائر، تونس وأكثر من ١٨٠ إذاعة
• بث مباشر لقناة القرآن الكريم من المسجد الحرام وقناة السنة النبوية من المسجد النبوي

🕌 مواقيت الصلاة والأذان
• حساب دقيق يعمل بدون إنترنت، ٩ طرق حساب، المذهب الحنفي والجمهور
• تنبيه عند دخول الوقت مع صوت الأذان (٣١ صوتاً) وتنبيه قبل الأذان
• اتجاه القبلة والمسافة إلى الكعبة

🤍 الأذكار والتذكير
• أذكار الصباح والمساء وبعد الصلاة والنوم والاستيقاظ، وأدعية من القرآن، وأسماء الله الحسنى
• تذكير كل ساعة (أو كما تختار) بآية وتفسيرها أو ذكر أو حديث، مع أوقات هدوء
• سبحة إلكترونية بأهداف وإحصائيات

📗 الختمة
• اختر مدة الختمة (من ٣ إلى ٩٠ يوماً) واقرأ وردك صفحة بصفحة
• متابعة التقدّم والأيام المتتالية، وتذكير مسائي إن لم يكتمل الورد

📜 الحديث الشريف
• صحيح البخاري ومسلم والسنن الأربعة والموطأ والأربعون النووية والأحاديث القدسية

🕋 يوم الجمعة
• تذكير بسورة الكهف، وعدّاد للصلاة على النبي ﷺ، وتذكير بساعة الاستجابة

🔒 الخصوصية
لا إعلانات، لا تتبّع، لا جمع لأي بيانات. كل إعداداتك محفوظة في متصفحك فقط.

«خيركم من تعلّم القرآن وعلّمه» — شارك الإضافة، والدالّ على الخير كفاعله.
```

### Detailed description — English

```
Noor — your daily companion for the Holy Quran, azkar and prayer, right in your browser.

📖 THE HOLY QURAN
• All 114 surahs in Uthmani script with Tafsir al-Muyassar
• Verse-by-verse audio with the current ayah highlighted (12 reciters)
• Search the Quran, bookmarks, and continue where you left off

🎧 240+ RECITERS
• Every reciter on mp3quran in every riwayah (Hafs, Warsh, Qalun…)
• Continuous playback, repeat, MP3 download, favorites
• Audio keeps playing after you close the popup

📻 LIVE QURAN RADIO & TV
• Cairo Quran Radio, Sharjah Quran Radio, Saudi, Makkah, Kuwait, Jordan, Oman, Bahrain, Algeria, Tunisia and 180+ stations
• Live Quran channel from Masjid al-Haram and Sunnah channel from Masjid an-Nabawi

🕌 PRAYER TIMES & ADHAN
• Accurate offline calculation, 9 methods, Hanafi/standard Asr
• Adhan alert at prayer time (31 adhan voices) plus a heads-up before it
• Qibla direction and distance to the Kaaba

🤍 AZKAR & REMINDERS
• Morning, evening, after-prayer, sleep and waking azkar, Quranic duas, 99 Names of Allah
• Hourly (or custom) reminder with an ayah + tafsir, a dhikr or a hadith — with quiet hours
• Digital tasbeeh with targets and stats

📗 KHATMA PLANNER
• Pick a 3–90 day plan and read your daily portion page by page
• Progress, streaks and an evening reminder if today's portion isn't done

📜 HADITH
• Sahih al-Bukhari, Sahih Muslim, the four Sunan, Muwatta, Nawawi's 40, Hadith Qudsi

🕋 FRIDAY
• Surat al-Kahf reminder, salawat counter, and a reminder for the hour of response

🔒 PRIVACY
No ads, no tracking, no data collection. Your settings stay in your browser.
```

### Graphics
| Field | File |
|---|---|
| Store icon (128×128) | `icons/icon128.png` |
| Screenshots (1280×800) | `store/images/1-quran.png` … `5-reminder.png` |
| Small promo tile (440×280) | `store/images/promo-small-440x280.png` |
| Marquee promo tile (1400×560) | `store/images/promo-marquee-1400x560.png` |

## 3. Privacy practices tab

**Single purpose:**
```
An Islamic daily companion: read and listen to the Holy Quran and keep up with prayer times, adhan alerts and daily azkar reminders.
```

**Permission justifications:**

| Permission | Justification |
|---|---|
| storage | Saves the user's settings, reading position, bookmarks, khatma progress and counters locally. |
| unlimitedStorage | Caches Quran pages, surah texts and reciter lists so they load instantly and work with a weak connection. |
| alarms | Schedules prayer-time adhan alerts, the user's chosen dhikr/ayah reminders, and the daily khatma and Friday reminders. |
| notifications | Shows prayer-time and reminder notifications when the user picks "system notification" style. |
| offscreen | Plays Quran recitations, radio and the adhan in the background so audio continues after the popup closes. |
| geolocation | Optional "My location" button: coordinates are used locally to calculate prayer times and Qibla. Never transmitted. |
| idle | Skips dhikr reminders while the screen is locked. |
| Host permissions | Fetches public content only: Quran text/tafsir (alquran.cloud), recitations/radio/TV lists (mp3quran.net), audio (islamic.network, qurango.net), hadith (cdn.jsdelivr.net), adhan audio (aladhan.com, islamcan.com), and live radio/TV streams (holol.com, ercdn.net, mgmlcdn.com, streamlock.net). |

**Remote code:** No, I am not using remote code. (All JavaScript, including hls.js, is bundled in the package.)

**Data usage:** tick **none** of the data types. Then tick all three certifications:
- I do not sell or transfer user data to third parties…
- I do not use or transfer user data for purposes unrelated to my item's single purpose
- I do not use or transfer user data to determine creditworthiness or for lending purposes

> Location: coordinates never leave the device, so per the policy definitions this is not "collected". If a reviewer asks, point to the privacy policy section on location.

**Privacy policy URL:** the public URL where you host `store/privacy-policy.html` (see README step 3).

## 4. Distribution tab
- Visibility: **Public**
- Regions: **All regions**
