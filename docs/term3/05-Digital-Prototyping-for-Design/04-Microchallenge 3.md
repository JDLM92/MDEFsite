---
hide:
    - toc
---

### Reflection on Microchallenge 3: Creating the Immersive Portals Experience

**Introduction:**
Embarking on Microchallenge 3, the Portals project, was a transformative journey that integrated technical skills, design principles, and user-centered thinking. The goal was to create an immersive VR experience showcasing different urban mobility scenarios, specifically focusing on Plaza Espanya. This reflection outlines the development process, challenges encountered, solutions implemented, and the outcomes derived from the interactive voting mechanism incorporated in the project.

**Project Conception and Goals:**
The primary objective was to present three urban scenarios—each comprising a current state and a future inflection point—through an engaging VR platform. The idea was to allow users to navigate between scenarios, listen to explanatory audio tracks, and switch between the current and future images. Additionally, we aimed to enable our classmates to vote on their preferred scenarios, providing valuable insights into collective preferences and perceptions of urban mobility futures.

**Development Process:**
1. **Initial Setup:**
   We began with a basic structure for the VR experience using A-Frame, an open-source web framework for building virtual reality experiences. The initial code focused on loading and displaying images, playing corresponding audio tracks, and implementing navigation buttons for switching between scenarios and toggling between current and future images.

2. **Iterative Improvements:**
   - **Button Interactivity:** A significant challenge was ensuring that buttons were only active when visible. Initially, the "Start" button remained active in the scenario view, causing unintended behavior. This was addressed by carefully managing the button states, disabling them when not in use.
   - **Audio Management:** Another key challenge was managing the audio tracks efficiently. We needed to ensure that audio tracks looped correctly and did not restart unnecessarily when switching between current and future images within the same scenario. We introduced a mute button and implemented logic to manage audio play, pause, and restart actions.
   - **Visual and User Experience:** Ensuring the UI was intuitive and the buttons were spaced sensibly required several iterations. We adjusted the positioning and styling of buttons to ensure primary actions were clearly distinguishable and user-friendly.

3. **User Voting Mechanism:**
   The inclusion of a voting mechanism allowed users to select their preferred scenario after experiencing the VR content. This feature provided an interactive element that engaged users and collected valuable feedback on their preferences.

**Key Learnings:**
1. **Modular Code and Custom Events:**
   Implementing custom events for handling scenario transitions and button interactions made the code more modular and maintainable. This approach allowed for cleaner, more organized code, making it easier to manage and extend.

2. **Component-Based Architecture:**
   A-Frame's component-based architecture facilitated the creation of reusable components for common functionalities such as button interactions and audio controls. This approach enhanced the project's scalability and maintainability.

3. **Responsive Design:**
   Ensuring the experience was accessible on various devices, including VR headsets and mobile phones, was crucial. Using media queries and A-Frame's responsive components helped adjust the layout and functionality based on the device, providing a seamless user experience across different platforms.

**Outcome and Reflections:**
The voting results from our classmates revealed interesting preferences and insights into the scenarios. We received a lot of detailed feedback on why people voted the way they did. Many users pointed out specific details they didn't like, which influenced their choice. For instance, one local classmate mentioned that seeing certain buildings transformed made her dislike some representations, even though she appreciated other aspects of the scenarios. These insights were invaluable, offering a glimpse into collective perceptions and priorities regarding urban mobility.

The project demonstrated the importance of iterative development, user-centered design, and responsive implementation. By addressing the challenges and iterating on solutions, we were able to create an engaging and informative VR experience that aligned with the goals of the MDEF program. This project underscored the value of integrating technical skills with design thinking to produce meaningful and interactive digital experiences.

Creating an immersive voting experience based on the potential impact of each political party's electoral program was a daring but rewarding experiment. The technology and insights gained from this project will likely play a crucial role in the development of my final project. This journey has not only provided me with practical skills but also deepened my understanding of how immersive technologies can influence and reflect public opinion on urban mobility futures.

**Conclusion:**
Using VR to achieve the goal of creating an experience based on feedback was an interesting take for sure, and although it was different from other classmates' projects, it was an incredible dive into the world of coding and getting consistent results, especially for a project done in less than 5 days. Microchallenge 3, the Portals project, showcased the potential of VR in engaging users and gathering valuable insights, highlighting the importance of immersive technologies in shaping the future of urban mobility.