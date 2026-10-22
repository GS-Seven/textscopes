# TextScope — Privacy-First Writing, SEO & AI Text Utilities

**Official Web App:** **[https://textscopes.com](https://textscopes.com)**

**TextScope** ([textscopes.com](https://textscopes.com)) is a fast, 100% client-side suite of writing, readability, SEO, and LLM text utilities for writers, editors, developers, and prompt engineers. Every tool runs locally in your browser with zero server uploads, zero account sign-ups, and instant real-time analysis across **6 languages** (English, Español, Deutsch, Português, 日本語, 한국어).

## Live Online Tools

| Tool | Live URL | Key Capabilities & Use Cases |
| :--- | :--- | :--- |
| **[Word Counter & Readability Analyzer](https://textscopes.com/)** | [textscopes.com](https://textscopes.com/) | Real-time word, character, sentence, and paragraph counter with **Flesch Reading Ease** score, **Flesch-Kincaid Grade Level**, reading/speaking time, and 1–3 word n-gram keyword density. |
| **[AI Text Cleaner & Format Stripper](https://textscopes.com/ai-text-cleaner)** | [textscopes.com/ai-text-cleaner](https://textscopes.com/ai-text-cleaner) | Strips ChatGPT/Claude/Gemini Markdown (`**bold**`, `# headers`, code fences), removes **zero-width invisible characters** (`U+200B`, `U+FEFF`, `U+00A0`), converts AI em-dashes (`—`) and curly quotes, and fixes broken PDF line wraps. |
| **[LLM Token Counter & Context Calculator](https://textscopes.com/token-counter)** | [textscopes.com/token-counter](https://textscopes.com/token-counter) | Estimates BPE token counts for **GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro, and Llama 3** (including CJK character weighting) and calculates exact context window fill percentages (`8K` to `1M` tokens). |
| **[Headline Analyzer & Google SERP Preview](https://textscopes.com/headline-checker)** | [textscopes.com/headline-checker](https://textscopes.com/headline-checker) | Evaluates H1/title tag length (50–60 chars / 550–600px), power words, emotional triggers, clickbait patterns, and renders a live Google Search snippet preview. |
| **[Reading & Speaking Time Calculator](https://textscopes.com/reading-time)** | [textscopes.com/reading-time](https://textscopes.com/reading-time) | Calculates silent reading time (150–300 WPM) and speech/presentation duration (110–170 WPM) for articles, scripts, podcasts, and academic papers. |
| **[Case Converter & Code Naming Tool](https://textscopes.com/case-converter)** | [textscopes.com/case-converter](https://textscopes.com/case-converter) | One-click text transformation between `UPPERCASE`, `lowercase`, `Title Case`, `Sentence case`, `camelCase`, `PascalCase`, `snake_case`, `kebab-case`, and `CONSTANT_CASE`. |

## Multilingual Directory (All 36 Live Pages)

TextScope is fully localized across 6 languages to support global writers and developers:

| Language | Word Counter | AI Text Cleaner | LLM Token Counter | Headline Checker | Reading Time | Case Converter |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **English** | [Word Counter](https://textscopes.com/) | [AI Text Cleaner](https://textscopes.com/ai-text-cleaner) | [Token Counter](https://textscopes.com/token-counter) | [Headline Checker](https://textscopes.com/headline-checker) | [Reading Time](https://textscopes.com/reading-time) | [Case Converter](https://textscopes.com/case-converter) |
| **Español** | [Contador de Palabras](https://textscopes.com/es/) | [Limpiador de Texto IA](https://textscopes.com/es/ai-text-cleaner) | [Contador de Tokens IA](https://textscopes.com/es/token-counter) | [Analizador de Titulares](https://textscopes.com/es/headline-checker) | [Tiempo de Lectura](https://textscopes.com/es/reading-time) | [Convertidor de Mayúsculas](https://textscopes.com/es/case-converter) |
| **Deutsch** | [Wortzähler](https://textscopes.com/de/) | [KI-Text-Bereiniger](https://textscopes.com/de/ai-text-cleaner) | [KI-Token-Zähler](https://textscopes.com/de/token-counter) | [Überschriften-Tester](https://textscopes.com/de/headline-checker) | [Lesezeit-Rechner](https://textscopes.com/de/reading-time) | [Groß-/Kleinschreibung](https://textscopes.com/de/case-converter) |
| **Português** | [Contador de Palavras](https://textscopes.com/pt/) | [Limpador de Texto IA](https://textscopes.com/pt/ai-text-cleaner) | [Contador de Tokens IA](https://textscopes.com/pt/token-counter) | [Analisador de Títulos](https://textscopes.com/pt/headline-checker) | [Tempo de Leitura](https://textscopes.com/pt/reading-time) | [Conversor de Maiúsculas](https://textscopes.com/pt/case-converter) |
| **日本語** | [文字数・単語数カウント](https://textscopes.com/ja/) | [AIテキストクリーナー](https://textscopes.com/ja/ai-text-cleaner) | [AIトークンカウンター](https://textscopes.com/ja/token-counter) | [見出し・タイトルチェッカー](https://textscopes.com/ja/headline-checker) | [読了・スピーチ時間計算](https://textscopes.com/ja/reading-time) | [大文字・小文字変換](https://textscopes.com/ja/case-converter) |
| **한국어** | [글자수·단어수 세기](https://textscopes.com/ko/) | [AI 텍스트 클리너](https://textscopes.com/ko/ai-text-cleaner) | [AI 토큰 카운터](https://textscopes.com/ko/token-counter) | [제목·헤드라인 분석기](https://textscopes.com/ko/headline-checker) | [읽기·발표 시간 계산기](https://textscopes.com/ko/reading-time) | [대소문자·표기법 변환기](https://textscopes.com/ko/case-converter) |

## Core Formulas & Reference Benchmarks

### 1. Flesch Reading Ease & Flesch-Kincaid Grade Level
Used in the [TextScope Word Counter & Readability Analyzer](https://textscopes.com/):

- **Flesch Reading Ease:** `206.835 - 1.015 × (Total Words / Total Sentences) - 84.6 × (Total Syllables / Total Words)`
- **Flesch-Kincaid Grade Level:** `0.39 × (Total Words / Total Sentences) + 11.8 × (Total Syllables / Total Words) - 15.59`
- **Target Score:** `60–70` (8th–9th Grade) is the standard benchmark for web articles, blog posts, and business communications.

### 2. BPE Token Estimation & LLM Context Windows
Used in the [TextScope LLM Token Counter](https://textscopes.com/token-counter):

- **English Prose:** `1 token ≈ 0.75 words` (`~4 characters`), or `100 tokens ≈ 75 words`.
- **Source Code / JSON / Markdown:** `1 token ≈ 3 to 3.3 characters` due to punctuation and syntax symbols.
- **CJK Text (Japanese, Korean, Chinese):** `1 character ≈ 1.2 to 1.8 tokens` depending on UTF-8 byte-pair vocabulary coverage.
- **Standard Context Windows:** `8,192` (8K), `32,768` (32K), `128,000` (128K — GPT-4o / Llama 3.1), `200,000` (200K — Claude 3.5 Sonnet), and `1,000,000` (1M — Gemini 1.5 Pro).

### 3. Invisible Unicode Characters & AI Formatting Artifacts
Cleaned by the [TextScope AI Text Cleaner](https://textscopes.com/ai-text-cleaner):

- **Zero-Width Space (`U+200B`), Zero-Width Non-Joiner (`U+200C`), Zero-Width Joiner (`U+200D`):** Invisible characters that break string matching, regex validation, and database indexing.
- **Byte Order Mark (`U+FEFF`) & Soft Hyphen (`U+00AD`):** Hidden layout artifacts copied from rich-text editors or PDFs.
- **Non-Breaking Space (`U+00A0`):** Prevents standard HTML/CSS word wrapping and breaks whitespace splitting.

### 4. Reading & Speaking Speed Benchmarks
Used in the [TextScope Reading Time Calculator](https://textscopes.com/reading-time):

- **Silent Reading (Adult Average):** `238 WPM` (non-fiction) / `260 WPM` (fiction).
- **Public Speaking & Keynotes:** `130 WPM` (`~780 words` for a 6-minute talk; `~1,300 words` for a 10-minute presentation).
- **Audiobook & Podcast Narration:** `150–160 WPM` (`~9,300 words` per recorded hour).

## Privacy & Architecture

- **100% Client-Side Execution:** Built with vanilla HTML5, CSS3, and JavaScript. No text ever leaves the browser.
- **Zero Dependencies:** No external frameworks or bulky bundles—instant First Contentful Paint (FCP) and fast Core Web Vitals.
- **Full Internationalization (i18n):** Complete `hreflang` reciprocity, localized `WebApplication` + `FAQPage` JSON-LD structured data, and canonical URL mapping across all 36 tool pages.

## Links

- **Website:** [https://textscopes.com](https://textscopes.com)
- **Privacy Policy:** [https://textscopes.com/privacy](https://textscopes.com/privacy)
- **Sitemap:** [https://textscopes.com/sitemap.xml](https://textscopes.com/sitemap.xml)
