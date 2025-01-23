Rozdział 03, lekcja 02 — Interakcja z dużym modelem językowym

Zdolność dużych modeli językowych do generowania ustrukturyzowanych treści umożliwia ich integrację z logiką aplikacji, co pozwala programistycznie sterować ich zachowaniem. Na obecnym etapie rozwoju pełnią one rolę narzędzia, które umożliwia przetwarzanie i generowanie danych w sposób dotąd niemożliwy do osiągnięcia programistycznie, na przykład z pomocą wyrażeń regularnych.

W kursie AI_devs 3 skupimy się na programistycznej interakcji z dużymi modelami językowymi poprzez API, budując częściowo-autonomiczne narzędzia zwane Agentami AI lub Systemami Agencyjnymi. Są to złożone rozwiązania wymagające praktycznego doświadczenia w programowaniu i dobrego zrozumienia natury dużych modeli językowych.

Narzędzia te mogą realizować najróżniejsze zadania i procesy, ale nie są uniwersalne. Dlatego skupimy się na tworzeniu ich indywidualnych komponentów oraz modułów. W ten sposób możliwe będzie ich połączenie w różnych konfiguracjach i dopasowanie do naszych potrzeb.

Jeszcze kilka miesięcy temu wybór modelu ogólnego zastosowania zaczynał się i kończył na OpenAI. Natomiast dziś pod uwagę możemy brać:

- OpenAI: Modele z rodziny o1, GPT, w tym także TTS, Whisper i Embedding
- Anthropic: Modele z rodziny Claude, tylko tekst + obraz
- Vertex AI (Google): Modele Gemini oraz wybranych dostawców, takich jak Anthropic, i inne
- xAI: Modele Grok, które dość szybko przebiły się na szczyty rankingów, top 10
- Amazon Bedrock (Amazon): Modele Anthropic, Mistral, Meta i inne
- Azure (Microsoft): Modele OpenAI, Meta i inne
- Groq: Modele Open Source, na przykład Llama
- a także kilka innych, takich jak OpenRouter, Perplexity, Cerebras, Databricks, Mistral AI czy Together AI.

Możemy zatem wybierać między różnymi ofertami cenowymi, limitami dostępu do API, polityką prywatności i przetwarzania danych, a także samymi modelami. Jest to istotne, ponieważ agenci AI będą autonomicznie korzystać z naszych baz wiedzy lub uzyskają dostęp do narzędzi. Przełoży się to na działanie na dość dużej skali, uwzględniającej przetwarzanie nawet dziesiątek milionów tokenów, co generuje zauważalne koszty. Obrazuje to poniższy przykład zapytania z prośbą do Agenta AI o zapisanie zadań w Linear, co przełożyło się na 17 tysięcy 400 tokenów zapytania, czyli input, i 461 tokenów odpowiedzi, czyli output. Warto też zwrócić uwagę na czas wykonania zapytania, czyli aż 24 sekundy.