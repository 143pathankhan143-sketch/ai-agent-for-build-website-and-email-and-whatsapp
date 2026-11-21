# Step 01 — अपने computer की जानकारी और Python check

इस step में कुछ खरीदना नहीं और किसी account को connect नहीं करना। अभी project blueprint बना है; app का server अगली implementation step में बनाएँगे।

## 1. तुम कौन-सा desktop/laptop इस्तेमाल करोगे?

यह format भरकर chat में भेजो:

```text
OS: Windows 10/11 / macOS / Linux
RAM: 4 / 8 / 16 GB / पता नहीं
Free storage: लगभग ___ GB / पता नहीं
Coding experience: बिल्कुल नया / थोड़ा
Python version result: ___
```

RAM/storage पता नहीं तो कोई बात नहीं। शुरुआत templates से होगी; local AI model अभी install नहीं करेंगे। अगर तुम्हारे पास अभी केवल mobile है तो बताओ—desktop setup की जगह अलग development route plan करेंगे।

## 2. Python पहले से है या नहीं जाँचो

### Windows

Start menu में **PowerShell** खोलो। एक-एक करके चलाओ:

```powershell
py --version
python --version
```

इनमें से एक में `Python 3.11` या उससे नया दिखे तो ठीक है। अगर command not found आए या Microsoft Store खुले तो उसका message बताओ; अगली step में सही installation कराएँगे। दोनों commands का सफल होना जरूरी नहीं।

### macOS / Linux

Terminal खोलकर चलाओ:

```bash
python3 --version
```

हमें Python 3.11 या नया चाहिए। System Python को uninstall/replace मत करना। पुराना version हो तो output भेजो; OS के हिसाब से safe installation बताएँगे।

## 3. अभी क्या install नहीं करना है

- Node.js: React export phase आने तक जरूरी नहीं।
- Ollama / बड़े AI models: hardware देखने के बाद optional.
- Google Maps API, WhatsApp API या paid hosting: पहले local workflow बनाएँगे।
- कोई browser extension जो WhatsApp scrape/auto-send या Google Maps bulk extract करने को कहे: इस project का हिस्सा नहीं।

## 4. इस step की completion

तुम अपना OS, जितनी hardware information पता है और Python command का result भेज दो। **Passwords, API keys, OTP, private phone number या घर का exact address मत भेजना।**

इसके बाद Step 02 में local dashboard शुरू करेंगे: Hindi/English interface, local database और एक sample business save करने की सुविधा। पहले version में कोई real email/WhatsApp message नहीं जाएगा।
