# Module 9B - Custom Profile Component

## Description
This is a React app built with Vite. It contains a profile component styled with inline CSS.

## What I Learned
- How to use JSX: I learned that I could customize React functions by adding arguments, or "props", which is the data for a React component.
- How to style with inline CSS: When I added a second component, a Skills card, I had initially copied the stylings from the Profile card over hoping that it would make my components aligned with each other from top to bottom and left to right, but it didn't. I ended up having to use fixed widths to force alignment. I imagine that this is not the approach used in advanced applications, so I hope to learn how to achieve alignment among components without using fixed settings.
- How to create and render functional components: I went for the bonus challenges and created a Skills card to complement the Profile card. To render, I made sure I returned the 'function' in the component's .jsx file, then import it in the app.jsx file, and finally Saving and checking my opened browser to see how it appeared.

## Challenges
I encountered several issues, not when rendering the Profile card but when creating the second component, a Skills card, which I described above.
Additional challenges I faced: 
- Adding a div section for my second component, which threw errors because, as I would learn, you can have only one root element, yet I had two 'simultaneous' elements. I ultimately put a larger div around these two sections, where each section was dedicated to each component type.
- Using mixed bold / non-bold within the same line in order to set apart header text from detail text. I learned that I had to wrap the bold text in 'strong'.


## Screenshot
Include a screenshot of your component.
<img width="1363" height="716" alt="image" src="https://github.com/user-attachments/assets/e1744212-c6d7-4c7d-bdea-abad50ed9cad" />
