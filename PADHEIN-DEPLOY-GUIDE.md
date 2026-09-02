# Website Live Karne Ka Guide (Free)

## Files ismein hain
- `index.html` — poora website (ek hi file mein HTML+CSS+JS), naam **"दिशा गार्डनिंग / Disha Gardening"**
- `robots.txt` + `sitemap.xml` — Google ko site samajhne ke liye
- Contact details already daali hui hain: phone/WhatsApp `8053549942`, address `13-17, Sector, HUDA`, email `sainiabhishek9994@gmail.com`, timing "हमेशा खुला — 24x7"
- Saari plants/pots photos free-license (Unsplash) se seedhi internet se load hoti hain — koi photo upload karne ki zarurat nahi. Bas site ko internet chalu hote hue hi dekhna, tabhi photos dikhengi.

## Step 1 — Free Hosting (GitHub Pages)
1. github.com par free account bana lo (agar nahi hai).
2. Ek naya repository banao, naam: `disha-gardening` (ya jo bhi naam pasand ho).
3. `index.html`, `robots.txt`, `sitemap.xml` — teeno files us repo mein upload kar do (GitHub website par "Add file → Upload files" se seedha ho jayega, terminal ki zarurat nahi). Purani file already repo mein hai to upload karte waqt "replace existing file" wala option chunna.
4. Repo ke Settings → Pages mein jao → Branch select karo `main` → Save.
5. 1-2 minute mein site live ho jayegi is link par:
   `https://<your-github-username>.github.io/<repo-name>/`

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

## Photos ke baare mein
Filhaal saari photos free-license Unsplash se hain (indoor plants, outdoor plants, phool, fal, succulents, herbal plants, aur sabhi tarah ke pots) — koi copyright issue nahi, professional dikhti hain. Jab bhi aap apni nursery ki asli photos khींचना chaho:

1. Phone se achhi roshni mein clear photo lo (har category ke liye ek photo — indoor plants, outdoor plants, pots types waghera)
2. `index.html` file mein Ctrl+F se `images.unsplash.com` search karo — jitni bhi jagah milegi wahan `src="..."` ke andar wala link apni photo ke link/file se replace kar dena
3. Agar photo apne computer se lagani hai (URL nahi), to photo ko `images` naam ke folder mein daal ke GitHub par upload karo, aur code mein `src="images/photo-naam.jpg"` likh dena

Photo size 200-500 KB rakhna best hai (compressor.io se free mein chhota kar sakte ho), warna site slow ho sakti hai.

## Website mein kya-kya add ho chuka hai
- Naam: दिशा गार्डनिंग (Disha Gardening)
- Har plant/pot category ki real photo
- Scroll karte waqt smooth fade-in animation
- Cards par hover karne se lift/zoom effect
- Hero section mein background photo + animated entrance
- Contact section mein aapka phone, address, email, WhatsApp button (24x7 khula dikhaya gaya hai)

## Aage kya add kar sakte ho (optional)
- Google Maps embed (address ke saath map dikhana)
- Har plant/pot ke saath price
- WhatsApp Business catalog link

Koi bhi step mein atko to bata dena, main aage help kar dunga.
