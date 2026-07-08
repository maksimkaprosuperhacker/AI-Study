# AI Study

A mobile app that turns any uploaded course material into a test, a summary, or a glossary of key terms — generated on the fly by GPT. Backend: [Srver_Ai_Study](https://github.com/maksimkaprosuperhacker/Srver_Ai_Study).

**1st place, City Project Competition — 250,000 ₸.** One of my earliest projects.

## Features

- **Test**: generates a quiz from uploaded material, with a configurable question count.
- **Summarize**: condenses material into a summary.
- **Terms**: extracts and defines key terms.
- **Courses**: organizes materials into courses you can revisit.

## Tech Stack

- **React Native + Expo Router**
- **JavaScript**

## Run locally

```bash
git clone https://github.com/maksimkaprosuperhacker/AI-Study.git
cd AI-Study
npm install
npx expo start
```

Requires [Srver_Ai_Study](https://github.com/maksimkaprosuperhacker/Srver_Ai_Study) running for the AI backend.

## Key Files

- `app/course_tabs/test.jsx` — quiz generation flow.
- `app/course_tabs/summarize.jsx` — summary generation.
- `app/course_tabs/terms.jsx` — key-terms extraction.
- `app/courses/[course].jsx` — course view.

## Author

- [@maksimkaprosuperhacker](https://github.com/maksimkaprosuperhacker)
