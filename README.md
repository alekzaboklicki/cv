# CV / strona wizytówka — Aleksander Żaboklicki

Statyczna, dwujęzyczna (PL/EN) strona-wizytówka wdrażana na Vercelu.

| Plik | Do czego służy |
|---|---|
| `index.html` | cała strona; jedyne zewnętrzne zależności to kroje Oswald i Inter z Google Fonts (styl „Studio”: grafit + bursztyn, wspólny z CV z `tools/cvgen.py`). `?lang=en` otwiera wersję angielską, `?rola=pm\|po\|proc\|ai\|trainer` od razu pokazuje odpowiedź pod daną rolę. Hero ma osadzony film z animowanymi grafikami SVG (5 scen + klatka końcowa) o tym, jak łączę role: sprzedaż B2B → Product Owner → PM → aplikacje i AI → wszystkie role naraz; rusza, gdy jest widoczny |
| `photo.webp` | zdjęcie profilowe |
| `og-image.jpg` | obrazek podglądu linku (1200×630); adres strony: https://cv-ruby-delta.vercel.app/ |
| `CV-Aleksander-Zaboklicki.pdf` | plik pobierany przyciskiem „CV w PDF" |
| `robots.txt` | blokada indeksowania |
| `vercel.json` | nagłówek `X-Robots-Tag: noindex` |

Strona jest celowo wyłączona z wyszukiwarek.
