# Project Plan: Asma'ul Husna Learning App for Grade 5 (Darjah 5)

## Project Overview
An interactive educational web application to help 10-year-old students learn and test their knowledge of Allah's 99 names (Asma'ul Husna). The app will match Arabic names with their Malay meanings in an engaging, child-friendly format.

## Target Audience
- Primary students (Grade 5 / Darjah 5)
- Age: 10 years old
- Language: Malay meanings for Arabic names

## Project Structure

```
asma-ul-husna-darjah-5/
├── index.html          # Main page with brief notes about Asma'ul Husna
├── quiz.html           # Interactive quiz page
├── assets/
│   ├── css/
│   │   └── style.css   # Main stylesheet
│   ├── js/
│   │   ├── main.js     # Main page functionality
│   │   └── quiz.js     # Quiz functionality
│   └── images/         # Images and graphics (if needed)
├── data/
│   └── names.json      # JSON file containing all 99 names with Arabic and Malay translations
├── plan.md             # This file
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## Features

### 1. Index Page (index.html)
- **Purpose**: Introduction and educational content
- **Content**:
  - Brief notes/explanation about Asma'ul Husna
  - Overview of the 99 names
  - Educational introduction suitable for 10-year-olds
- **Navigation**:
  - Button/link to navigate to quiz section
- **Design Considerations**:
  - Child-friendly interface
  - Large, readable fonts
  - Colorful and engaging design
  - Simple navigation

### 2. Quiz Page (quiz.html)
- **Purpose**: Interactive learning through matching game
- **Functionality**:
  - Display Arabic names of Allah
  - Display Malay meanings (scrambled or in a selection)
  - Match Arabic names to correct Malay meanings
  - Interactive feedback for correct/incorrect matches
  - Progress tracking
- **User Experience**:
  - Simple drag-and-drop or click-to-select interface
  - Visual feedback (colors, animations)
  - Encouraging messages for children
  - Score display (optional)
- **Design Considerations**:
  - Large buttons for easy clicking
  - Clear visual distinction between Arabic and Malay text
  - Fun, engaging animations
  - Accessible for young users

## Data Structure

### names.json
JSON file containing all 99 names with:
- Arabic name (in Arabic script)
- Transliteration (Romanized Arabic)
- Malay translation/meaning
- Brief description (optional)

Example structure:
```json
{
  "names": [
    {
      "id": 1,
      "arabic": "الرحمن",
      "transliteration": "Ar-Rahman",
      "malay": "Yang Maha Pemurah",
      "description": "..."
    },
    ...
  ]
}
```

## Technical Implementation Plan

### Phase 1: Framework Setup ✅
- [x] Create folder structure
- [x] Create project plan
- [x] Set up basic files

### Phase 2: Data Preparation
- [ ] Research and compile all 99 names
- [ ] Create names.json with Arabic, transliteration, and Malay meanings
- [ ] Verify accuracy of translations

### Phase 3: Index Page Development
- [ ] Design layout for index page
- [ ] Write content about Asma'ul Husna suitable for children
- [ ] Create navigation button to quiz
- [ ] Apply styling for child-friendly interface

### Phase 4: Quiz Page Development
- [ ] Design quiz interface layout
- [ ] Implement matching mechanism (drag-drop or click-select)
- [ ] Add feedback system (correct/incorrect indicators)
- [ ] Implement progress tracking
- [ ] Add score system (optional)

### Phase 5: Styling & Polish
- [ ] Apply consistent styling across pages
- [ ] Add animations and transitions
- [ ] Ensure responsive design
- [ ] Test on different devices

### Phase 6: Testing & Deployment
- [ ] Test with target age group
- [ ] Fix bugs and usability issues
- [ ] Deploy to GitHub Pages
- [ ] Final review

## Design Guidelines

### Colors
- Use bright, friendly colors
- Ensure good contrast for readability
- Consider color-blind accessibility

### Typography
- Large, readable fonts (minimum 16px)
- Clear distinction between Arabic and Malay text
- Child-friendly font choices

### Interactions
- Large clickable areas
- Clear visual feedback
- Simple, intuitive controls
- No complex gestures required

### Content
- Age-appropriate language
- Encouraging and positive messages
- Educational and respectful tone

## GitHub Pages Configuration

- Repository name: `asma-ul-husna-darjah-5`
- GitHub Pages will serve from root directory
- Main entry point: `index.html`
- Ensure all assets use relative paths

## Future Enhancements (Optional)
- Audio pronunciation of Arabic names
- Progress saving (localStorage)
- Different quiz modes (multiple choice, fill-in-the-blank)
- Leaderboard or achievement system
- Print-friendly versions
- Dark mode toggle

