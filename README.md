# Spelling Flashcard App

This is a single-page flashcard learning app created by Gemini, a large language model from Google.

## Prompt

The following prompt was used to generate this application:

---

Here are the words I want to learn each week:

**Week 1:**
- though
- although
- dough
- doughnut
- through
- cough
- trough
- rough
- tough
- enough

**Week 2:**
- plough
- bough
- drought
- brought
- bought
- wrought
- thought
- ought
- borough
- thorough

**Week 3:**
- yesterday
- tomorrow
- later
- immediately
- earlier
- eventually
- recently
- previously
- finally
- lately

**Week 4:**
- nearby
- everywhere
- nowhere
- inside
- downstairs
- outside
- upstairs
- underneath
- behind
- somewhere

**Week 5:**
- sincere
- interfere
- sphere
- adhere
- severe
- persevere
- atmosphere
- mere
- hemisphere
- austere

**Week 6:**
- amateur
- ancient
- bargain
- muscle
- queue
- recognise
- twelfth
- identity
- develop
- harass

Create a single-page flashcard learning app in TypeScript that works like Anki and can be hosted on GitHub Pages as a single HTML file (no build system, just inline TypeScript compiled to JavaScript).

### Requirements:

*   **Week Selection:** A menu to select the week (e.g., Week 1, Week 2, etc.).
*   **Word Data:** Hardcode a list of words. Each entry should include:
    *   English word
    *   English definition
    *   Russian translation
    *   Pronunciation text (to be read aloud with the Web Speech API)
    *   A sample sentence in English.
*   **Flashcard Behavior:**
    *   The front of the card should show the definition in English.
    *   A button to play the pronunciation of the word (spelling test style).
    *   The pronunciation should play automatically when the card is shown.
    *   An input field for the user to type their guess of the English word.
    *   On submit, the card should flip and show the difference between the correct word and the user’s answer (highlighting incorrect/missing letters).
    *   The back of the card should show the difference, the Russian translation of the word, and the sample usage sentence.
*   **Navigation:** Navigation controls for next card, previous card, and flipping the card.
*   **Design:** A minimal and clean design with CSS inside the same HTML file.
*   **Offline:** The app should work fully offline as a standalone HTML page.
*   **Technology:** Use only vanilla TypeScript/JavaScript, HTML, and CSS (no frameworks).
