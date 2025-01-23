# AI_devs 3, Lekcja 1, Moduł 1 — Interakcja z dużym modelem językowym

![Cover](https://cloud.overment.com/S02E03-1731372201.png)

W niniejszym artykule przedstawimy możliwości generatywnego AI w zakresie manipulacji i generowania nowych grafik oraz zdjęć. Porównamy różne narzędzia oraz podejdziemy do tematu z perspektywy programistycznej i projektowej. 

## 1. Wprowadzenie do tematu

Kreacja graficzna i praca ze zdjęciami dotychczas nie były bezpośrednio związane z programowaniem. Owszem, programowanie znalazło zastosowanie w tworzeniu narzędzi, ale rzadko w samym procesie projektowania. Takie narzędzia jak [Midjourney](tools/Midjourney.md) czy [Stable Diffusion](glossary/Stable%20Diffusion.md) przyciągają uwagę nie tylko projektantów, ale i deweloperów. Istnieją jednak także narzędzia, które wykorzystywane są w sposób bardziej funkcjonalny, co pokazuje przykład [picthing](https://pic.ping.gg/), platformy do skutecznego usuwania tła, stworzona przez twórcę `Theo z t3.gg`. 

### 1.1 Picthing

Narzędzie picthing znacząco poprawia jakość usuwania tła, co ilustruje jak generatywne AI może być wykorzystane do tworzenia użytecznych produktów.

![Picthing](https://cloud.overment.com/2024-09-26/aidevs3_picthing-a5ce0e6a-b.png)

### 1.2 Projekty Pieter Levels

Innym interesującym przykładem są projekty [Pieter Levels](https://x.com/levelsio), takie jak [PhotoAI](https://photoai.com/) i [InteriorAI](https://interiorai.com). Zajmują się one specyficznymi problemami i są skuteczne, co potwierdzają statystyki przedstawiane przez Pietera.

![Pieter Levels](https://cloud.overment.com/2024-09-26/aidevs3_levelsio-55df5a6e-5.png)

## 2. Obecne możliwości generowania obrazu

Rozwój generatywnej grafiki w ostatnich latach jest imponujący. Porównując dane z 2022 i 2024 roku, zauważalne są znaczne postępy w jakości generowanych obrazów, m.in. w artykule [Comparing AI-generated images two years apart — 2022 vs. 2024](https://medium.com/@junehao/comparing-ai-generated-images-two-years-apart-2022-vs-2024-6c3c4670b905).

![Porównanie](https://cloud.overment.com/2024-09-26/aidevs3_midjourney-79dd9b18-9.png)

### 2.1 Ograniczenia

Mimo że jakość generowanych obrazów się poprawiła, nadal istnieją ograniczenia w modelach, w tym trudności z generowaniem szczegółowych elementów jak tekst, dłonie czy lustrzane odbicia. Nasze oczekiwania wobec generowanych treści powinny być dostosowane do obecnych możliwości technologii.

![Ograniczenia](https://cloud.overment.com/2024-09-26/aidevs3_peace-955577e3-1.png)

### 2.2 Przykład zamiany twarzy

Możemy jednak efektywnie wykorzystać AI do prostych zadań, takich jak zamiana twarzy na już istniejących zdjęciach. Poniżej prezentujemy użycie narzędzia [ComfyUI](ComfyUI), które potrafi zastąpić twarze na generowanych obrazach.

![Zamiana twarzy](https://cloud.overment.com/2024-09-26/aidevs3_swap-92e327ca-8.png)

### 2.3 Narzędzia API i hosting

Z programistycznego punktu widzenia interesują nas dostępne modele poprzez API. Dobrym przykładem są platformy takie jak [Replicate](tools/Replicate.md) i [Leonardo.ai](https://leonardo.ai/). Możemy także samodzielnie hostować modele, korzystając z platform takich jak [RunPod](https://blog.runpod.io/how-to-get-stable-diffusion-set-up-with-comfyui-on-runpod/).

## 3. Generowanie grafik w oparciu o szablony

Tworzenie grafik może być uproszczone dzięki szablonom, szczególnie w obszarze marketingu. Na przykład, w eduweb.pl wykorzystano szablony okładek wydarzeń, które pozwalały na łatwą i szybką produkcję wizualizacji, wystarczyło tylko zmienić zdjęcie i tekst.

![Szablony](https://cloud.overment.com/2024-09-26/aidevs3_eduweb-b678b9a8-5.png)

## 4. Techniki projektowania promptów dla modeli

Podobnie jak z wprowadzeniem w LLM, generowanie grafik wymaga napisania skutecznego promptu. W tym kontekście, lepiej skupić się na używaniu prostych słów kluczowych niż na rozbudowanych opisach.

![Prompt example](https://cloud.overment.com/2024-09-26/aidevs3_mj-852d34e2-4.png)

Eksperymentowanie z różnymi podejściami do promptów, na przykład skupiając się na słowach kluczowych, może przynieść lepsze rezultaty. Logika korzystania z meta promptów, które różnią się w zależności od oczekiwań, może również zwiększyć efektywność generowania grafik.

![Meta prompt](https://cloud.overment.com/2024-09-27/aidevs3_metaprompt-472bcf88-b.png)

## 5. Generowanie grafik za pomocą HTML i CSS

Narzędzie [htmlcsstoimage](https://htmlcsstoimage.com) pozwala na generowanie obrazów w oparciu o HTML oraz CSS, co umożliwia dynamiczną edycję tekstów oraz stylów. Te rozwiązania łączą generatywną grafikę z technologiami webowymi.

![htmlcsstoimage](https://cloud.overment.com/2024-09-27/aidevs3_htmlcsstoimage-c6f590af-a.png)

## 6. Podsumowanie narzędzi

Narzędzia generatywnej grafiki, takie jak [ComfyUI](ComfyUI) oraz [HTMLCSStoImage](https://htmlcsstoimage.com), mogą być wykorzystane do tworzenia automatycznych rozwiązań i nowoczesnych modeli graficznych. Te innowacje mogą pomóc w procesach marketingowych oraz rozwoju produktów. 

**WAŻNE:** Jeśli nie posiadasz komputera, który pozwoli na swobodną pracę z ComfyUI, warto rozważyć alternatywne narzędzia.

Pomocny może być film prezentujący Dobre praktyki pracy z ComfyUI:
<div style="padding:75% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1029104946?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="02_03_comfy"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Mam nadzieję, że ten artykuł pomoże Ci w zrozumieniu i pełnym wykorzystaniu możliwości narzędzi generatywnej grafiki!