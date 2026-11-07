# தமிழ்நாடு அரசுப் பாடநூல்கள் — 2-ஆம் வகுப்பு டிஜிட்டல் களஞ்சியம் (TNSCERT Class 2)

[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-Live-F38020?style=flat&logo=cloudflare)](https://tn-class-02.pages.dev/)
[![Curriculum](https://img.shields.io/badge/Curriculum-SCERT_2026--27_First_Edition-blue)](#)
[![Verified Pages](https://img.shields.io/badge/Pages-824_Verified_Pages-success)](#)
[![Zero Data Loss](https://img.shields.io/badge/SHA_Match-100%25_Verified-brightgreen)](#)

தமிழ்நாடு மாநிலக் கல்வியியல் ஆராய்ச்சி மற்றும் பயிற்சி நிறுவனம் (TNSCERT / SCERT) வெளியிட்டுள்ள **2026-2027 புதிய பாடத்திட்ட 2-ஆம் வகுப்புப் பாடநூல்களின்** அதிகாரப்பூர்வ முதற்பதிப்பு (First Edition 2026) டிஜிட்டல் வெக்டார் போர்ட்டல்.

🌐 **நேரலைத் தளம் (Live Portal):** [https://tn-class-02.pages.dev/](https://tn-class-02.pages.dev/)  
📁 **பழைய பாடநூல்கள் களஞ்சியம் (2018–2022 Archive):** [Eaglesiva/tn-class-02-archive](https://github.com/Eaglesiva/tn-class-02-archive)

---

## 📊 2026 அதிகாரப்பூர்வ முதற்பதிப்பு பாடநூல்கள் விவரம் (2026 First Edition Inventory)

தமிழ்நாடு அரசு 2026-27 கல்வியாண்டில் 2-ஆம் வகுப்பிற்கு **இணைந்த தொகுதிகளாக (Combined Volumes)** பாடநூல்களை வெளியிட்டுள்ளது:

| பருவம் (Term) | தொகுதி விவரம் (Volume / Subject) | பயிற்றுமொழி (Medium) | அச்சுப் பக்கங்கள் | கோப்பகப் பாதை (Directory Path) | நிலை (Status) |
| :--- | :--- | :---: | :---: | :--- | :---: |
| **பருவம் 1 (Term 1)** | தொகுதி 1: தமிழ் & ஆங்கிலம் (VOL-I TAMIL & ENGLISH) | தமிழ் / ஆங்கிலம் | **160** | `books/2026-27/term1/vol1_tamil_english/` | ✅ 100% SHA Verified |
| **பருவம் 1 (Term 1)** | தொகுதி 2: கணிதம் & சூழ்நிலையியல் (VOL-II MATHS & EVS) | தமிழ் வழி (TM) | **144** | `books/2026-27/term1/vol2_maths_evs_tm/` | ✅ 100% SHA Verified |
| **பருவம் 1 (Term 1)** | Volume 2: Mathematics & Environmental Studies | ஆங்கில வழி (EM) | **144** | `books/2026-27/term1/vol2_maths_evs_em/` | ✅ 100% SHA Verified |
| **பருவம் 2 (Term 2)** | தொகுதி 1: தமிழ் & ஆங்கிலம் (VOL-I TAMIL & ENGLISH) | தமிழ் / ஆங்கிலம் | **136** | `books/2026-27/term2/vol1_tamil_english/` | ✅ 100% SHA Verified |
| **பருவம் 2 (Term 2)** | தொகுதி 2: கணிதம் & சூழ்நிலையியல் (VOL-II MATHS & EVS) | தமிழ் வழி (TM) | **120** | `books/2026-27/term2/vol2_maths_evs_tm/` | ✅ 100% SHA Verified |
| **பருவம் 2 (Term 2)** | Volume 2: Mathematics & Environmental Studies | ஆங்கில வழி (EM) | **120** | `books/2026-27/term2/vol2_maths_evs_em/` | ✅ 100% SHA Verified |
| **பருவம் 3 (Term 3)** | தொகுதி 1 & 2 (3 பாடநூல்கள்) | TM / EM | — | `books/2026-27/term3/` | ⏳ SCERT வெளியீடு நிலுவை (Pending) |
| **மொத்தம் (Class 2)** | **6 அதிகாரப்பூர்வ புதிய பாடநூல்கள்** | **அனைத்தும்** | **824 பக்கங்கள்** | **30 JSON மேனிஃபெஸ்ட்டுகள்** | **100% PASS** |

---

## 🏗️ கோப்பமைப்பு கட்டமைப்பு (Repository Structure)

```text
Eaglesiva/tn-class-02/
├── index.html                               # 2026 பாடநூல்களுக்கான நவீன முதன்மை போர்ட்டல்
├── viewer.html                              # அசல் அச்சுப் பக்கங்களுக்கான அதிவேக PDF Reader
├── vendor/pdfjs/                            # Offline PDF.js என்ஜின்
└── books/
    └── 2026-27/
        ├── term1/
        │   ├── vol1_tamil_english/          # 160 பக்கங்கள் (page-001.pdf முதல் page-160.pdf வரை)
        │   │   ├── edition.json             # SCERT பதிப்புத் தகவல் & சான்று
        │   │   ├── pages.json               # பக்கங்களின் வரிசைப் பட்டியல்
        │   │   ├── source_record.json       # SCERT மூலத் தகவல்
        │   │   ├── split_validation.json    # SHA256 & பைட்டுகள் சரிபார்ப்பு
        │   │   └── pages/                   # அசல் வெக்டார் பக்கங்கள்
        │   ├── vol2_maths_evs_tm/           # 144 பக்கங்கள்
        │   └── vol2_maths_evs_em/           # 144 பக்கங்கள்
        └── term2/
            ├── vol1_tamil_english/          # 136 பக்கங்கள்
            ├── vol2_maths_evs_tm/           # 120 பக்கங்கள்
            └── vol2_maths_evs_em/           # 120 பக்கங்கள்
```

---

## 🏛️ பழைய பாடநூல்கள் பாதுகாப்பு (Legacy Archive Reference)

முந்தைய 2018–2022 பாடத்திட்டத்தின் 1,044 பக்கங்கள், 114 வினா-விடை ஆவணங்கள் மற்றும் 18 மேனிஃபெஸ்ட்டுகள் (மொத்தம் **1,176 கோப்புகள்**) அனைத்தும் முழுமையான தரவுப் பாதுகாப்புடன் தனியாக **[Eaglesiva/tn-class-02-archive](https://github.com/Eaglesiva/tn-class-02-archive)** களஞ்சியத்தின் `main` கிளையில் பாதுகாக்கப்பட்டுள்ளன.

---

## 📜 பதிப்புரிமை & தரவு ஆதாரம் (Copyright & Attribution)

பாடநூல்களின் பதிப்புரிமை **தமிழ்நாடு மாநிலக் கல்வியியல் ஆராய்ச்சி மற்றும் பயிற்சி நிறுவனம் (TNSCERT)** மற்றும் **தமிழ்நாடு பாடநூல் மற்றும் கல்வியியல் பணிகள் கழகத்திற்கு** உரியது.
