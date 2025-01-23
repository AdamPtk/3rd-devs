# AI_devs 3, Lekcja 1, Moduł 1 — Interakcja z dużym modelem językowym

![Cover](https://cloud.overment.com/S02E03-1731372201.png)

W tym artykule przyjrzymy się, jak generatywne AI wpływa na manipulację i tworzenie nowych grafik oraz zdjęć, łącząc perspektywę programistyczną i projektową.

## 1. Wprowadzenie do tematu

Kreacja graficzna i praca ze zdjęciami tradycyjnie nie były ściśle powiązane z programowaniem, poza tworzeniem narzędzi czy zaawansowanych interakcji webowych. Jednak rozwój narzędzi takich jak [Midjourney](tools/Midjourney.md) czy [Stable Diffusion](glossary/Stable%20Diffusion.md) przyciąga uwagę nie tylko projektantów, ale także deweloperów, otwierając nowe możliwości w integracji AI z procesami twórczymi.

Przykładem praktycznego zastosowania generatywnego AI jest narzędzie [picthing](https://pic.ping.gg/), stworzone przez **Theo z t3.gg**, które znacząco poprawia jakość usuwania tła ze zdjęć, co ilustruje potencjał AI w tworzeniu użytecznych produktów.

![Picthing](https://cloud.overment.com/2024-09-26/aidevs3_picthing-a5ce0e6a-b.png)

Kolejnym interesującym przykładem są projekty [Pietera Levelsa](https://x.com/levelsio), takie jak [PhotoAI](https://photoai.com/) i [InteriorAI](https://interiorai.com), które skutecznie rozwiązują konkretne problemy, co potwierdzają przedstawiane przez niego statystyki.

![Pieter Levels](https://cloud.overment.com/2024-09-26/aidevs3_levelsio-55df5a6e-5.png)

## 2. Obecne możliwości generowania obrazu

Rozwój generatywnej grafiki w ostatnich latach jest imponujący. Porównując wyniki z 2022 i 2024 roku, zauważalny jest znaczny wzrost jakości generowanych obrazów. W artykule [Comparing AI-generated images two years apart — 2022 vs. 2024](https://medium.com/@junehao/comparing-ai-generated-images-two-years-apart-2022-vs-2024-6c3c4670b905) przedstawiono przykłady tego postępu.

![Porównanie](https://cloud.overment.com/2024-09-26/aidevs3_midjourney-79dd9b18-9.png)

### Ograniczenia

Mimo postępów, modele generatywne nadal mają trudności z precyzyjnym odtworzeniem pewnych elementów, takich jak tekst, dłonie, zęby czy lustrzane odbicia. Ważne jest, aby nasze oczekiwania były dostosowane do aktualnych możliwości technologii.

![Ograniczenia](https://cloud.overment.com/2024-09-26/aidevs3_peace-955577e3-1.png)

Jednak mimo tych ograniczeń, AI może być efektywnie wykorzystywane do zadań takich jak zamiana twarzy na istniejących zdjęciach. Przykładem jest użycie narzędzia [ComfyUI](ComfyUI), które pozwala na zastępowanie twarzy na generowanych obrazach.

![Zamiana twarzy](https://cloud.overment.com/2024-09-26/aidevs3_swap-92e327ca-8.png)

## 3. Programistyczne aspekty generatywnego AI

Z punktu widzenia programisty, istotne jest korzystanie z modeli dostępnych przez API. Platformy takie jak [Replicate](tools/Replicate.md) i [Leonardo.ai](https://leonardo.ai/) umożliwiają integrację modeli z aplikacjami, a samodzielny hosting modeli jest możliwy dzięki usługom takim jak [RunPod](https://blog.runpod.io/how-to-get-stable-diffusion-set-up-with-comfyui-on-runpod/).

Ponadto, stosowanie szablonów ułatwia generowanie grafik w celach marketingowych. Na przykład, w eduweb.pl wykorzystywano szablony okładek wydarzeń, co pozwalało na szybkie tworzenie spójnych wizualizacji poprzez zmianę zdjęcia i tekstu.

![Szablony](https://cloud.overment.com/2024-09-26/aidevs3_eduweb-b678b9a8-5.png)

## 4. Techniki projektowania promptów dla modeli

Podobnie jak w przypadku interakcji z dużymi modelami językowymi, efektywne generowanie grafik wymaga napisania skutecznego promptu. Często lepsze rezultaty przynoszą proste prompty z użyciem kluczowych słów, zamiast długich i szczegółowych opisów.

![Przykład promptu](https://cloud.overment.com/2024-09-26/aidevs3_mj-852d34e2-4.png)

Eksperymentowanie z różnymi podejściami do promptów, np. poprzez stosowanie meta promptów dostosowanych do konkretnych oczekiwań, może zwiększyć efektywność generowania grafik.

![Meta prompt](https://cloud.overment.com/2024-09-27/aidevs3_metaprompt-472bcf88-b.png)

## 5. Generowanie grafik za pomocą HTML i CSS

Narzędzia takie jak [htmlcsstoimage](https://htmlcsstoimage.com) umożliwiają generowanie obrazów na podstawie kodu HTML i CSS, co pozwala na dynamiczną edycję tekstów i stylów. Dzięki temu można łączyć generatywną grafikę z technologiami webowymi, tworząc elastyczne rozwiązania.

![htmlcsstoimage](https://cloud.overment.com/2024-09-27/aidevs3_htmlcsstoimage-c6f590af-a.png)

## 6. Podsumowanie narzędzi

Narzędzia z zakresu generatywnej grafiki, takie jak [ComfyUI](ComfyUI) i [htmlcsstoimage](https://htmlcsstoimage.com), oferują szerokie możliwości w automatyzacji procesów i tworzeniu nowatorskich rozwiązań graficznych. Ich zastosowanie może znacząco wspomóc działania marketingowe i rozwój produktów, łącząc kreatywność z programistycznymi umiejętnościami.

**WAŻNE:** Jeśli nie dysponujesz sprzętem pozwalającym na swobodną pracę z ComfyUI, warto rozważyć korzystanie z alternatywnych narzędzi dostępnych online.

Dla lepszego zrozumienia pracy z ComfyUI, pomocny może być poniższy film prezentujący dobre praktyki:

<div style="padding:75% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/1029104946?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="02_03_comfy"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## 7. Podsumowanie

Generatywne AI otwiera przed nami nowe możliwości w zakresie tworzenia i manipulacji grafiką, zarówno dla projektantów, jak i programistów. Wykorzystanie dostępnych narzędzi i modeli pozwala na automatyzację procesów, tworzenie spójnych materiałów marketingowych i rozwijanie innowacyjnych produktów. Ważne jest, aby poznać i zrozumieć te narzędzia, by w pełni wykorzystać ich potencjał w naszych projektach.