# Autistic Coders

A website dedicated to celebrating and supporting autistic programmers, highlighting the natural connection between autism and coding.

## 📌 Quick Links
- [Live Site](https://deetonn.github.io/autistic-coders/)
- [User Story Board](https://github.com/users/deetonn/projects/2/views/1)
- [Features](https://github.com/deetonn/autistic-coders?tab=readme-ov-file#-features)
- [Testing](https://github.com/deetonn/autistic-coders?tab=readme-ov-file#-testing)
- [Recent Updates](https://github.com/deetonn/autistic-coders?tab=readme-ov-file#-recent-updates)

## 🎯 Project Overview

This project aims to create a fun website, with a focus on autistic people in programming. We provide a fun quiz, to make fun of JavaScript, and some resources to help with learning programming.

### User Experience (UX)

#### User Stories

1. **First Time Visitor Goals**
   - As a first time visitor, I want to understand the connection between autism and programming
   - As a first time visitor, I want to find resources for learning programming
   - As a first time visitor, I want to see examples of successful autistic programmers

2. **Returning Visitor Goals**
   - As a returning visitor, I want to try the JavaScript quiz
   - As a returning visitor, I want to find community resources
   - As a returning visitor, I want to access learning platforms

3. **Frequent User Goals**
   - As a frequent user, I want to check for new resources
   - As a frequent user, I want to test my JavaScript knowledge, and see if there's any new questions.
   - As a frequent user, I want to find community connections

### 🎨 Features

#### 🏠 The home page

Learn about why autism and coding are a good fit. The connections between autism and coding
are really interesting to me, that's why I chose this topic. 

I chose a few examples of programmers who are autistic, to show that there's success in this field for autistic people, and also to add some relatability to the site.

#### 📚 The resources page

This page is dedicated to some resources that others may find useful. This includes learning platforms, tools for making life easier and community support, like a discord group, reddit group and advice on getting out and making real connections.

#### 🎮 The quiz page

This is a fun quiz, inspired by [JavaScript, for the haters by Fireship](https://www.youtube.com/watch?v=aXOChLn5ZdQ). I've done lots of research into the caveats of JavaScript, and have followed [Andreas Kling](https://www.youtube.com/c/andreaskling) for a while, while he builds his own browser (Ladybird). [LadyBird Browser](https://www.ladybird.org/) is a great project, and I've learned a lot from watching him.

### Design Philosophy

#### Visual Design
- **Clean Layout**: Simple design, with a focus on the page content. Also, it's bootstrap, so there's not much point in trying to make a masterpeice.
- **Consistent Navigation**: The navbar is sticky, and lives on each page. The buttons have nice, but not too in-your-face animations. (AI helped with this, as I'm no CSS god)
- **Color Scheme**: 
  - Carefully selected gradients for visual interest without overwhelming (Dark mode could be a good feature)
  - High contrast for readability
  - Soft transitions between colors
- **Typography**: 
  - Clear, readable fonts (Browser defaults)
  - Nice spacing for easy reading
  - Consistent hierarchy, keeping content easy to read, and top to bottom

#### Accessibility Features
- **Sensory Considerations**:
  - No flashing elements or sudden movements
  - Simple animations, to avoid any over-stimulation
  - Use of semantic HTML, to help with SEO and screen readers
  - We use a dyslexic friendly font, Lexend.
- **Navigation**:
  - Clear, yet simple visual feedback for elements
  - Consistent placement of the navigation buttons and icons
  - The navbar highlights the current page

![Wireframe of the website desktop](https://share.balsamiq.com/c/3pJbm6g1hoRxi9j8kP6MMA.jpg)
![Wireframe of the website mobile](https://share.balsamiq.com/c/mtYBgnksK9BrtECkpuCZd5.jpg)

### 🧪 Testing

#### Manual Testing

1. **Navigation**
   - Verified all navigation links work correctly
   - Tested responsive navbar on multiple devices
   - Confirmed active states show current page

2. **Resources Page**
   - Tested all external links
   - Verified card hover effects
   - Confirmed responsive layout

3. **Quiz Functionality**
   - Tested code execution
   - Verified answer checking
   - Confirmed progress tracking
   - Tested on multiple browsers (Chrome, Firefox)

4. **Responsiveness**
   All tests were conducted in the devtools, using the device toolbar.
   - Mobile (iPhone 12 Pro)
   - Desktop (1920x1080)
   - iPhone SE
   - iPad Air

5. **W3C HTML Validator**
   - Passed with no errors
   - ![W3C HTML Validator](https://github.com/deetonn/autistic-coders/blob/main/documentation/images/w3c-html-validator.png)

6. **W3C CSS Validator**
   - Passed with no errors
   - ![W3C CSS Validator](https://github.com/deetonn/autistic-coders/blob/main/documentation/images/w3c-css-validator.png)

7. **WCAG Accessibility**
   - Dark mode has no contrast issues
   - ![WCAG Accessibility Dark](https://github.com/deetonn/autistic-coders/blob/main/documentation/images/wcag-dark.png)
   - Light mode has contrast issues. The reason for this is the gradient, which is used for the background. I didn't adjust this, which I should have.
   - ![WCAG Accessibility Light](https://github.com/deetonn/autistic-coders/blob/main/documentation/images/wcag-light.png)

8. **Lighthouse**
   - Passed
   - ![Lighthouse](https://github.com/deetonn/autistic-coders/blob/main/documentation/images/lighthouse.png)

### 🐛 Known Bugs

1. **Quiz Page**
   - Quiz progress resets on page refresh

2. **Resources Page**
   - Card animations can stutter on slower devices

### 🚀 Deployment

The site is deployed on GitHub Pages. The deployment process was:

1. Navigate to the repository settings
2. Select Pages from the left menu
3. Choose main branch as source
4. Select root folder
5. Save the settings

The live site can be found at the github pages link (at the top of the README)

To run locally:
1. Clone the repository
2. run `python -m http.server`
3. Open the browser and navigate to `localhost:8000`

### ✨ Credits

#### Content
- Pioneer profiles information from [chatgpt.com](https://chatgpt.com)
- JavaScript quiz questions inspired by [FireShip](https://fireship.io)
- Resource links curated from [reddit.com](https://reddit.com), [youtube.com](https://youtube.com) and [google.com](https://google.com)

#### Media
- Icons from Bootstrap Icons
- Profile images from [Google Images](https://images.google.com)

#### Code
- The code was not inspired, but I did use AI to help.

**Explaination**: AI helped with the exection of the user input. I tried to be fancy, and safely execute the code, like this:

```javascript
const userInput = ...;
const functionCode = `const result = ${userInput}; return result;`;
const result = Function(functionCode)();
```

However, this did not result in the intended output, as some of the questions required to *NOT* be inside of a function context.

AI helped me to figure this out quicker.

### 🎯 Future Features

1. **Enhanced Quiz**
   - Multiple difficulty levels, instead of just ridiculously hard lol.
   - More JavaScript topics

2. **Accessibility**
   - Dark mode toggle

3. **Content**
   - More pioneer profiles
   - Additional learning resources

### AI Usage Disclosure

Different language models, such as ChatGPT and claude-3.5-sonnet were used to help with certain aspects of the project.

These are things like advanced CSS styling, like gradient backgrounds and keyframe animations.

Some of the content was discovered via the usage of AI too, like the pioneer profiles.

I have worked and studied the content generated, to ensure that no biases were introduced.

### 📝 Recent Updates

#### Alan Turing Legacy Section
- Added a dedicated section highlighting Alan Turing's contributions to computer science
- Features a picture of him
- Includes notable quotes and autistic traits that influenced his work
- Responsive design with subtle hover effects
- Accessible content structure with proper heading hierarchy

#### Footer Implementation
- Added a responsive, three-column footer design, because I think 3-column looks the best.
- Features:
  - Brand section with social media links (They dont actually link to real accounts, but they do open in new tabs)
  - Quick navigation links for easy access to the pages
  - Newsletter signup form, without any functionality.
- Accessibility features:
  - ARIA labels for all interactive elements
  - Proper color contrast in both light and dark modes
  - Semantic HTML structure
- Dark mode support with optimized text contrast
- Automatic copyright year update

#### Style Updates
- Enhanced color contrast for better accessibility
- Added new CSS variables for footer elements
- Improved form element visibility in dark mode
- Added hover effects for interactive elements
- Optimized responsive breakpoints for mobile devices

#### Performance Optimizations
- Proper semantic structure for SEO
- Lightweight implementation of footer with minimal JavaScript

---

Made with ❤️ by Deeton Rushton