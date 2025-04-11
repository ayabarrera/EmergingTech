# Emerging Technology - [LottieFiles](https://lottiefiles.com/)

- This project is made with HTML and CSS.
- Click the [Link] to go to the live webpage of the project.

---

## Todo
- [DONE] Look for an emerging tech that is new for me.
- [DONE] Learn its best use and how to implement.
- [DONE] Create a webpage to implement the technology.
    - [DONE] Create a low-level HTML
    - [DONE] Style with CSS

## What to include
- [DONE] Sample medias
- [DONE] What makes it good
- [DONE] Sample uses
- [DONE] How to use it

## Resources
- [LottieFiles Website](https://lottiefiles.com/)
- [Use Cases](https://lottiefiles.com/use-cases/website)
- [Lottie + AE](https://lottiefiles.com/plugins/after-effects)
- [Lotte + Figma](https://lottiefiles.com/plugins/figma)
- [Lottie Free Animations](https://lottiefiles.com/free-animations)
- [Lottie For React](https://developers.lottiefiles.com/docs/dotlottie-player/dotlottie-react/)
- Everything in the website is from [LottieFiles](https://lottiefiles.com/).com


## Why LottieFiles?
- I chose LottieFiles since it offers lightweight, scalable vector animations that can be easily integrated into websites and apps.
- It's great since it does not makes the website heavy since Lottie animations are exported as JSON format.
- It also provides a vast library of free and premium animations, a user-friendly editor (Lottie Editor) to customize them, and seamless cross-platform compatibility, making it a powerful tool for modern web and app development.
- It can be integrated in Figma, Canva, Adobe After Effects, Webpage, React, Vue, Webflow, and many other platforms.

## Integration - this is also explained in the Learn More page of the website.
### HTML
1. Include the @dotlottie/player-component script in your HTML's <head> or <body>
    - <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script>
2. Then, use the <dotlottie-player> custom element in your HTML where you want the animation
    - <dotlottie-player src="YOUR_LOTTIE_FILE_URL.lottie" autoplay loop controls></dotlottie-player>
*No specific dependencies beyond a web browser and an internet connection to fetch the player component and Lottie file.* 

### React
1. Install the @dotlottie/react-player npm package
    - npm install @dotlottie/react-player
2. Import and use the DotLottiePlayer component in your React components
    - import { DotLottiePlayer } from '@dotlottie/react-player';
        
        function MyComponent() {
        return (
        <DotLottiePlayer src="YOUR_LOTTIE_FILE_URL.lottie" autoplay loop controls />
        );
        }
*Requires a React project setup (Node.js, npm/yarn) and the @dotlottie/react-player package.*
*Running Locally: Navigate to your React project directory in the terminal and run npm start*
