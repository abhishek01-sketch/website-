# Website Live Karne Ka Guide (Free)

## Files ismein hain
- `index.html` — poora website (ek hi file mein HTML+CSS+JS)
- `robots.txt` + `sitemap.xml` — Google ko site samajhne ke liye
- Contact info abhi placeholder hai (`+91 XXXXX XXXXX`, address, email) — jab bhi ready ho, `index.html` mein Ctrl+F se dhoondh ke apni details daal dena. 4 jagah change karni hai: phone/WhatsApp number (2 jagah), address, email (2 jagah).

## Step 1 — Free Hosting (GitHub Pages)
1. github.com par free account bana lo (agar nahi hai).
2. Ek naya repository banao, naam: `hariyali-nursery` (ya jo bhi naam pasand ho).
3. `index.html`, `robots.txt`, `sitemap.xml` — teeno files us repo mein upload kar do (GitHub website par "Add file → Upload files" se seedha ho jayega, terminal ki zarurat nahi).
4. Repo ke Settings → Pages mein jao → Branch select karo `main` → Save.
5. 1-2 minute mein site live ho jayegi is link par:
   `https://<your-github-username>.github.io/hariyali-nursery/`

Ye link bilkul free hai, koi cost nahi. Isse phone, laptop, tablet — har jagah khulegi (responsive design already built-in hai).

## Step 2 — Apna Free Domain (Optional but recommended)
`.github.io` wala link thoda lamba lagta hai. Agar chhota, memorable naam chahiye:
- **Freenom / InfinityFree jaisi free .tk/.ml domains** — abhi kaafi unreliable ho gayi hain (Google unhe kam trust karta hai), isliye recommend nahi karunga.
- Better option: **Namecheap ya GoDaddy se ek .com/.in domain** kharido — inki cost bahut kam hoti hai (₹100-800/year range mein, especially first year offers). Ye ek baar ka chhota investment hai jo site ko bahut professional banata hai aur Google mein bhi behtar rank karta hai.
- Domain lene ke baad, GitHub Pages ke "Custom domain" setting mein daal do — GitHub free mein connect kar dega.

Agar bilkul free hi chahiye, `github.io` wala link filhaal use kar sakte ho — kaam bilkul sahi karega.

## Step 3 — Google Par Launch Karna (Search Console)
1. `https://search.google.com/search-console` par jao, apne Google account se login karo.
2. "Add Property" → apni site ka URL daalo.
3. Ownership verify karega (GitHub Pages ke liye HTML file method ya DNS method use karo — Search Console khud step-by-step batayega).
4. Verify hone ke baad, left menu mein "Sitemaps" par jao aur ye URL submit karo:
   `sitemap.xml`
5. Google ab site ko crawl karke Google Search mein dikhana shuru kar dega. Isme kabhi-kabhi kuch din se 2 hafte tak lag sakte hain.

## Step 4 — Contact Info Add Karna
Jab details ready ho, `index.html` file mein ye jagah update karna:
- WhatsApp number: `https://wa.me/91XXXXXXXXXX` (XXXXXXXXXX ki jagah 10-digit number)
- Phone display text: `+91 XXXXX XXXXX`
- Address: contact section mein "यहाँ नर्सरी का पूरा पता डालें"
- Email: 2 jagah `yourmail@example.com` ko replace karna

## Aage kya add kar sakte ho (optional)
- Asli nursery/plants ki photos (abhi illustrations hain)
- Google Maps embed (address ke saath map dikhana)
- Har plant/pot ke saath price
- WhatsApp Business catalog link

Koi bhi step mein atko to bata dena, main aage help kar dunga.
