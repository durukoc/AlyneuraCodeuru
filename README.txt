# AlyneuraCodeuru — statik site
Bu klasör, ücretsiz barındırma (GitHub Pages / Netlify / Vercel / Cloudflare Pages) için hazır tek sayfalık bir site içerir.

## Hızlı kurulum — GitHub Pages (ücretsiz)
1. GitHub'da yeni bir repo oluştur: `alyneuracodeuru-site`
2. Bu klasörün içindekileri reponun köküne yükle (`index.html`, `favicon.svg`).
3. Repo ayarları > *Pages* > *Source*: `Deploy from a branch` ve branch `main` seç.
4. 1-2 dakika içinde şu adreste yayında olur: `https://kullaniciadiniz.github.io/alyneuracodeuru-site/`

> Önemli: Ücretsiz olduğundan URL'de `.com` görünmez. `.com` görünmesi için bir domain satın alıp DNS yönlendirmesi gerekir.

## Netlify (ücretsiz)
- netlify.app'a giriş yap, "Add new site" > "Deploy manually", bu klasörü sürükle-bırak.
- URL `https://rastgele-ad.netlify.app` gibi olur. Dilersen *Site settings* > *Domain management* ile özel alt alan adı ayarlayabilirsin.

## Vercel (ücretsiz)
- vercel.com'a giriş yap, "Add New..." > "Project", bu repo veya klasörü bağla, auto deploy.

## Cloudflare Pages (ücretsiz)
- dash.cloudflare.com > Pages > Create a project > Direct upload > bu klasörü yükle.
