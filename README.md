# DOM-based-Content-Extraction-MM

**"Link တွေထုတ်ယူပြီး ၎င်း Link တွေထဲက ကြော်ငြာ၊ ကွန်မန့်စတဲ့ မလိုအပ်တာတွေကို ဖယ်ရှားကာ အဓိက စာသားနဲ့ ပုံတွေကို Markdown (.md) ဖိုင် ဒါမှမဟုတ် .asc, .rst ဖိုင်တွေ ပြန်ထုတ်ပေးတဲ့ လုပ်ငန်းစဉ်" ကို နည်းပညာဘာသာရပ်အရ အောက်ပါအတိုင်း ခေါ်ဆိုပါတယ်။

---

## 🔍 အဓိက အခေါ်အဝေါ်များ

| အခေါ်အဝေါ် (မြန်မာ/အင်္ဂလိပ်) | ရှင်းလင်းချက် |
| :--- | :--- |
| **Content Extraction** (ကန်တင့် အိတ်စထရက်ရှင်) | Website တစ်ခုရဲ့ HTML ထဲက မလိုအပ်တဲ့ အပိုင်းတွေ (navigation, sidebar, ကြော်ငြာ, comment) ကို ဖယ်ရှားပြီး **အဓိက ဆောင်းပါး/စာသား** ကိုသာ ထုတ်ယူတဲ့ လုပ်ငန်းစဉ်။ |
| **Article Extraction** (အာတီကယ် အိတ်စထရက်ရှင်) | Content Extraction အမျိုးအစားတစ်ခုဖြစ်ပြီး **သတင်း၊ ဘလော့ဂ်၊ ဆောင်းပါး** စတဲ့ စာမျက်နှာတွေကနေ အဓိက စာသားနဲ့ ရုပ်ပုံကို ထုတ်ယူတာကို အထူးရည်ညွှန်းပါတယ်။ |
| **Main Content Extraction (MCE)** | စာမျက်နှာရဲ့ "အဓိက အကြောင်းအရာ" ကို ခွဲခြားသတ်မှတ်တဲ့ နည်းပညာဆိုင်ရာ အသုံးအနှုန်း။ |
| **Web Scraping + Cleaning** | Web Scraping (ဒေတာခြစ်ယူခြင်း) လုပ်ပြီးနောက် ရလာတဲ့ ဒေတာကို **သန့်ရှင်းရေး (Data Cleaning/Sanitization)** လုပ်တဲ့ အဆင့်ပါဝင်တယ်ဆိုတာ ဖော်ပြချက်။ |
| **HTML to Markdown Conversion** | သန့်ရှင်းပြီးသား HTML ကို Markdown (.md), reStructuredText (.rst), သို့မဟုတ် AsciiDoc (.asc) ဖိုင်အဖြစ် ပြောင်းလဲတဲ့ နောက်ဆုံးအဆင့်။ |

---

## 🧠 ပိုမိုတိကျသော အသုံးအနှုန်းများ (Academic/Industrial)

- **DOM-based Content Extraction:** HTML ၏ DOM Tree ကိုခွဲခြမ်းစိတ်ဖြာပြီး အဓိက content ကို ရှာဖွေခြင်း (ဥပမာ - Readability, Boilerpipe စသည့် algorithms)။
- **Machine Learning-based Content Extraction:** မော်ဒယ်ကို သင်ကြားပေးပြီး အဓိက content ကို ခွဲခြားသတ်မှတ်ခြင်း (ဥပမာ - Dragnet, Newspaper3k)။
- **Web Archiving to Markdown:** Website တစ်ခုလုံးကို သိမ်းဆည်းခြင်း (Archiving) လုပ်ငန်း၏ တစ်စိတ်တစ်ပိုင်းအနေနဲ့ Markdown ဖိုင်များ ပြုလုပ်ခြင်း။

---

## 🏁 နိဂုံးချုပ်

**အတိုချုံးဆုံး အဖြေ:**  
ဒီလုပ်ငန်းစဉ်ကို **"Content Extraction"** (သို့) **"Article Extraction"** လို့ ခေါ်ပါတယ်။

**အသေးစိတ်ဖော်ပြချင်ရင်:**  
> *"Web Scraping ဖြင့် Link များထုတ်ယူခြင်း၊ ထို့နောက် Main Content Extraction လုပ်ခြင်းနှင့် HTML to Markdown Conversion ပြုလုပ်ခြင်း"*

**မြန်မာလို ရှင်းလိုက်ရင်လည်း:**  
> *"ဝဘ်စာမျက်နှာတစ်ခုရဲ့ အဓိက အကြောင်းအရာ (ဆောင်းပါး၊ စာသား၊ ပုံ) ကို ဆွဲထုတ်သန့်စင်ပြီး Markdown ဖိုင် ပြောင်းတဲ့ လုပ်ငန်းစဉ်"*

အဲဒီထဲမှာ **Web2MD** နဲ့ **webpull** က ဒီအလုပ်အတွက် အကောင်းဆုံးဖြစ်ပါတယ်။

---

ခင်ဗျားမေးထားတဲ့ လုပ်ဆောင်ချက်အဆင့်ဆင့်ကို ဖြေရှင်းပေးနိုင်တဲ့ GitHub Repository အမျိုးမျိုးရှိပါတယ်။ အဲဒါတွေကို အောက်ပါအတိုင်း အဓိက အုပ်စု (၃) ခုခွဲပြီး စာရင်းပြုစုပေးလိုက်ပါတယ်။

---

### 📦 အပိုင်း (၁) - Link Extraction အပါအဝင်၊ Website တစ်ခုလုံးကို Markdown အဖြစ် ပြောင်းလဲပေးနိုင်သော "အစုံအလင်" Tools များ

ဒီ Tools တွေက ခင်ဗျားစဉ်းစားထားတဲ့ "Link Extraction -> Content Cleaning -> Markdown Output" ဆိုတဲ့ workflow တစ်ခုလုံးကို လုပ်ဆောင်ပေးနိုင်ပါတယ်။

#### 1. **Web2MD** (`floatinghotpot/web2md`)
*   **အလုပ်လုပ်ပုံ:** Website တစ်ခုလုံး (Dynamic နဲ့ Static) ကို ရှာဖွေပြီး (Crawl) သန့်ရှင်းတဲ့ Markdown ဖိုင်တွေအဖြစ် ပြောင်းလဲပေးပါတယ်။ ဆိုလိုတာက Link တွေကို အလိုအလျောက် ရှာဖွေပြီး ၎င်း Link တွေထဲက အဓိက စာသားနဲ့ ပုံတွေကို ထုတ်ယူကာ `.md` ဖိုင်အဖြစ် သိမ်းဆည်းပေးမှာဖြစ်ပါတယ်။
*   **Output Format:** Markdown (.md)

#### 2. **webpull** (`Dhravya/webpull`)
*   **အလုပ်လုပ်ပုံ:** Sitemap သို့မဟုတ် Link တွေကနေ စာမျက်နှာတွေကို ရှာဖွေပြီး (Discover)၊ parallel စနစ်ဖြင့် ယူဆောင်ကာ (Fetch)၊ Intelligent Content Extraction လုပ်ပြီး Markdown အဖြစ် ပြောင်းလဲပေးပါတယ်။ ဖိုင်တွေကို URL လမ်းကြောင်းအတိုင်း သိမ်းဆည်းပေးပြီး YAML Frontmatter လည်း ထည့်ပေးပါတယ်။
*   **Output Format:** Markdown (.md) with YAML frontmatter

#### 3. **Firecrawl** (`Klomgor/firecrawl`)
*   **အလုပ်လုပ်ပုံ:** API တစ်ခုအနေနဲ့ ဆောင်ရွက်ပြီး၊ Website တစ်ခုလုံးကိာ Markdown အဖြစ်ပြောင်းပေးပါတယ်။ Link တွေကိုလိုက်ပြီး Crawl လုပ်ခြင်း၊ Sitemap ကိုသုံးခြင်းတို့ကို လုပ်ဆောင်နိုင်ပြီး Output ကို Markdown, HTML, Screenshot, JSON စသဖြင့် ရယူနိုင်ပါတယ်။
*   **Output Format:** Markdown (.md), HTML, Screenshot, JSON

#### 4. **DocDown** (`alxpez/docdown`)
*   **အလုပ်လုပ်ပုံ:** Customizable Web Scraper တစ်ခုဖြစ်ပြီး Documentation တွေအတွက် အထူးသင့်တော်ပါတယ်။ HTML Content ကို ခြစ်ယူခြင်း (Scrape)၊ ဆက်စပ် Link တွေကို လုပ်ဆောင်ခြင်း (Process) နဲ့ Clean Markdown Output ကို ထုတ်ပေးပါတယ်။
*   **Output Format:** Markdown (.md)

---

### 🧹 အပိုင်း (၂) - HTML/Web Content ကို သန့်ရှင်းပြီး Markdown အဖြစ်သို့ ပြောင်းလဲပေးသော Core Libraries များ

ဒီ Tools တွေက Link Extraction လုပ်ငန်းကို မပါဝင်ဘဲ၊ ခင်ဗျား Link တွေကို ထုတ်ယူပြီးသား HTML Content (သို့) တိုက်ရိုက် Web Page ကို သန့်ရှင်းတဲ့ Markdown အဖြစ် ပြောင်းလဲပေးပါတယ်။

#### 1. **Article Extractor** (`pankaj28843/article-extractor`)
*   **အလုပ်လုပ်ပုံ:** Web Page ရဲ့ HTML ကို Readability-style Scoring နဲ့ ခွဲခြမ်းစိပ်ဖြာပြီး အဓိက Article Content ကိုသာ ထုတ်ယူကာ Markdown အဖြစ် ပြောင်းလဲပေးပါတယ်။ CLI, API နဲ့ Python Library အနေနဲ့ သုံးနိုင်ပါတယ်။
*   **Output Format:** Markdown (.md), Sanitized HTML

#### 2. **pyreadability** (`randerzander/pyreadability`)
*   **အလုပ်လုပ်ပုံ:** Mozilla ရဲ့ Readability.js ကို Pure Python နဲ့ ပြန်လည်အကောင်အထည်ဖော်ထားတာပါ။ Web Page တစ်ခုရဲ့ အဓိက ဖတ်ရှုနိုင်တဲ့ content ကို ထုတ်ယူပြီး Clean HTML (သို့) Markdown အဖြစ် ပြန်ပေးပါတယ်။
*   **Output Format:** Markdown (.md), Clean HTML

#### 3. **rs-trafilatura** (`Murrough-Foley/rs-trafilatura-python`)
*   **အလုပ်လုပ်ပုံ:** Rust နဲ့ရေးထားတဲ့ မြန်ဆန် (high-performance) Python Library တစ်ခုပါ။ Web Page တစ်ခုရဲ့ အဓိက Content ကို ထုတ်ယူခြင်း၊ HTML သန့်ရှင်းရေးလုပ်ခြင်းနဲ့ Markdown ပြောင်းလဲခြင်းတို့ကို လုပ်ဆောင်ပါတယ်။
*   **Output Format:** Markdown (.md) - GitHub Flavored Markdown

#### 4. **html2cleantext** (`html2cleantext`)
*   **အလုပ်လုပ်ပုံ:** Python Package ဖြစ်ပြီး HTML ကို Clean, Structured Markdown (သို့) Plain Text အဖြစ် ပြောင်းလဲပေးပါတယ်။ မလိုအပ်တဲ့ အစိတ်အပိုင်းတွေကို ဖယ်ရှားပေးပြီး Language-Specific Text Cleanup လည်း လုပ်ဆောင်နိုင်ပါတယ်။
*   **Output Format:** Markdown (.md), Plain Text

#### 5. **trafilatura** (`trafilatura`)
*   **အလုပ်လုပ်ပုံ:** Python package နှင့် CLI tool တစ်ခုဖြစ်ပြီး Web Crawling, Downloading, Scraping နှင့် Main Text, Metadata, Comments များကို ထုတ်ယူခြင်းအတွက် အဓိက အသုံးပြုပါတယ်။
*   **Output Format:** CSV, JSON, XML, TXT (Markdown အထွက်အတွက်မူ သီးသန့် converter လိုအပ်နိုင်ပါသည်)

---

### 🚀 အပိုင်း (၃) - Command Line Interface (CLI) အသုံးပြုရန် လွယ်ကူသော Tools များ

ကုဒ်ရေးစရာမလိုဘဲ command line ပေါ်တွင် အသုံးပြုနိုင်ရန် ရည်ရွယ်ထားသော tools များဖြစ်သည်။

#### 1. **url-to-markdown-cli-tool** (`mmdclx/url-to-markdown-cli-tool`)
*   **အလုပ်လုပ်ပုံ:** Node.js CLI tool ဖြစ်ပြီး Puppeteer ကိုသုံးကာ web page တစ်ခုကို fetch လုပ်ကာ ads, navigation စတဲ့ noise တွေကို ဖယ်ရှားပြီး LLM-friendly markdown အဖြစ် ပြောင်းလဲပေးပါတယ်။
*   **Output Format:** Markdown (.md)

#### 2. **md-fetch** (`nathabonfim59/md-fetch`)
*   **အလုပ်လုပ်ပုံ:** Powerful CLI tool တစ်ခုဖြစ်ပြီး headless browser ကိုသုံးကာ web content ကို fetch လုပ်ကာ Clean, Readable Markdown အဖြစ် ပြောင်းလဲပေးပါတယ်။ Anti-scraping measures တွေကိုလည်း bypass လုပ်နိုင်စွမ်းရှိပါတယ်။
*   **Output Format:** Markdown (.md)

---

### 🧠 အခြားထူးခြားသော Tools များ

*   **decruft** (`jamtur01/decruft`): Clean, readable content ကို extract လုပ်ပြီး Metadata (title, author, date) များကိုပါ ထုတ်ယူပေးပါတယ်။ Site-specific extractors (GitHub, Reddit, etc.) တွေပါဝင်ပြီး Markdown output ကို တိုက်ရိုက်မထုတ်ပေးနိုင်ပေမယ့် အခြား library များနဲ့တွဲဖက်သုံးရန် အထောက်အကူပြုပါတယ်။

---

### 💎 အကျဉ်းချုပ်

*   **"Link တွေပါ လိုက်ပြီး အလုပ်လုပ်ချင်ရင်":** **Web2MD**, **webpull**, **Firecrawl** (သို့) **DocDown** ကို စဉ်းစားပါ။
*   **"ကျွန်တော့်မှာ Link တွေရှိပြီးသား၊ သန့်ရှင်းရေးပဲလုပ်ချင်ရင်":** **Article Extractor**, **pyreadability**, (သို့) **rs-trafilatura** ကို သုံးနိုင်ပါတယ်။
*   **"အမြန်ဆုံး၊ ရိုးရှင်းတဲ့ CLI tool တစ်ခုလိုချင်ရင်":** **url-to-markdown-cli-tool** (သို့) **md-fetch** က အကောင်းဆုံးဖြစ်ပါတယ်။

ဒီ Tools တွေကို အသုံးပြုခြင်းအားဖြင့် ခင်ဗျားရဲ့ Colab script ကို ပိုမိုအဆင့်မြင့်ပြီး အလိုအလျောက်လုပ်ဆောင်နိုင်တဲ့ system တစ်ခုအဖြစ် ပြောင်းလဲနိုင်ပါလိမ့်မယ်။

ခင်ဗျားစဉ်းစားထားတဲ့ Workflow အတွက် ဒီ Tools တွေက လုံလောက်တဲ့ အကူအညီ ဖြစ်မယ်လို့ မျှော်လင့်ပါတယ်။ တစ်ခုခု ထပ်ပြီးအကူအညီလိုရင် ပြောပါ။
