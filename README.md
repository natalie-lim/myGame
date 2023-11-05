# Candy Crush Kinda


## Table of Contents

- [Introduction](#introduction)
- [Value/Use](#value/use)
- [User Interaction and Experience](#ui-and-experience)
- [Competitive Element](#competative-element)
- [Engagement and Addictiveness Strategies](#engagement-and-addictiveness)
- [Scalability and Expansion](#scalability-and-expansion)
- [Accessibility and Inclusivity](#accessibility-and-inclusivity)
- [Design Components](#design-components)
- [Technical Specifications](#tech-specs)

## Introduction
What do all great, addictive games have in common? Mind-numbing-ness. I dare you to tell a middle-aged woman to delete Candy Crush off her phone without getting jumped. If you made me delete my off-brand Scrabble (WordMaster) off my phone I would probably go catatonic. Thus, slight stupidity seems to be the way to go. Enter: off-brand Candy Crush! But the candies are teachers because Find Ricky C did really well last year and who doesn't have at least one teacher they would like to crush. 

## Value/Use
Games bring students together. On Community Council Mr. Church was harping on us about how the HW community is severely lacking in school spirit and none of us care about each other or our school (he may have a point) so this game could be a way for us to bond!

## User Interaction and Experience
This will probably be moderately easy to chat-GPT. We can make a several different levels, each using the faces of different department teachers. We will probably have to put a colored filter over different teachers, just so that their different candy powers are easy to discern. After winning a game, you can collect the department head, which all have different power-up capabilities. 

## Competitive Element
Expanding on those previous points– our community is also very competitive. While using money (look below) and such will get people interested, competition is what will make it fun. We can implement a point system, awarding more and more points with each level. We can also make a boss level at the end (which will be near-impossible to beat), populated with some of the hardest teachers on campus regardless of department. Think Dr. Gatey, Dr. Long, Ms. Campbell, Dr. Wade, etc.

## Engagement and Addictiveness Strategies
Real monetary benefits. While we focus on growth on campus, it would be easy to provide some sort of monetary prize to the winner(s) after each month. This would get students a lot more invested in each round, without us having to predict what kind of game is actually intrinsically the most addictive.

## Scalability and Expansion
Good question. Obviously the same appeal would not hold for other schools/users, so there are two options. Firstly, we could introduce pages with short bios on each HW teacher, or we could allow students from different schools to input their own teachers/staff as pngs, and have the app immediately resize them to fit. 

## Accessibility and Inclusivity
This game will be inclusive because all students on campus can use it. It will not discriminate on the basis of race, religious creed, color, national origin, ancestry, physical disability, mental disability, reproductive health decisionmaking, medical condition, genetic information, marital status, sex, gender, gender identity, gender expression, age, sexual orientation, or military and veteran status. 

## Design Components
1. User Interface (UI)
- Game Grid: A vibrant grid represents the school campus with different departments as levels.
- Candy/Teacher Characters: Each candy is styled after a teacher, with recognizable features and a colored filter to represent their 'powers'.
- Department Heads: Special characters that serve as power-ups or bosses, visually distinct and larger than other candies.
- Score Display: A prominently placed scoreboard showing the player's current points.
- Lives Display: An indicator of the player's remaining attempts, shown with thematic icons such as graduation caps or books.
- Power-up Display: Shows the available power-ups collected by the player, like the department heads.
2. Gameplay Mechanics
- Swiping to Match: Players swipe to align similar teacher candies vertically or horizontally.
- Teacher Powers: Matching certain teacher candies activates unique abilities, like clearing an entire row or column.
- Boss Levels: Featuring a puzzle that includes a mix of the toughest teacher candies requiring specific strategies to clear.
- Lives and Continuation: Players lose a life when they fail a level, with the option to continue by using in-game currency or watching an ad.
- Progression and Difficulty: Levels become more challenging as players advance, with new game grid configurations and tougher departments.
3. Aesthetics
- Sound Effects: Cheerful and encouraging sound cues for successful matches, special abilities, and level completions. Additionally, each department head could have a unique sound motif.
- Visual Effects: Exciting animations for special moves, level-ups, and winning streaks, such as confetti or digital fireworks.
- Character Design: Caricatures of teachers that are fun and respectful, potentially using a caricature artist to ensure a balance of humor and likeness.

## Technical Specifications
1. Technology Stack
- Programming Language: JavaScript (with a framework like React Native for mobile app development)
- Game Engine: Phaser.js, integrated within a React Native WebView for game scenes.
- Mobile Development Framework: React Native for both Android and iOS compatibility.
- Frontend: React components for mobile UI, with stylesheets written in CSS-like language (e.g., StyleSheet in React Native).
2. Architecture
- MVC Pattern: Model-View-Controller pattern will be adapted for mobile app development, separating game logic (Model), screen rendering (View), and user input handling (Controller).
3. Data Model
- Candies/Teachers: Each will be an object with attributes like type (color filter/power), grid position, and special abilities or scores. They will be managed within a grid-like data structure for gameplay.
- Levels: Defined as unique configurations and arrays of teacher objects, with metadata for difficulty settings and department themes.
- Users: Data related to player profiles, including game progress, high scores, and achievements, will be stored locally or in the cloud.
4. Security and Performance
- Client-Side Performance: Mobile devices have varying capabilities, so performance will be optimized for fluid gameplay across different hardware.
- Data Security: User data, especially when tied to potential monetary rewards, will be securely handled with encryption and secure cloud storage practices.
5. Specific Functionalities
- Touch Input and Gestures
    - - Specification: The game will support touch input for swapping teacher/candy elements. Gestures will be smooth and responsive, using the native capabilities of mobile devices.
- Scoring, Lives, and In-App Purchases
    - - Specification: Real-time score tracking with additional options for lives and power-ups, potentially including in-app purchases for monetization and extended gameplay.
- Progressive Difficulty and Unlockable Content
    - - Specification: Levels will become progressively harder. Unlockable content, including special department heads and rare teachers with unique abilities, will add depth to the game.
- Mobile-Centric Sound and Notifications
    - - Specification: Sound effects optimized for mobile devices, with options for silent mode. Push notifications to engage players and announce competitions or rewards.
- Responsive Mobile UI/UX
    - - Specification: The user interface will be designed for a range of mobile devices, ensuring readability and ease of use across different screen sizes and orientations.
- Accessibility Features
    - - Specification: Accessibility features including text-to-speech, colorblind modes, and scalable UI elements to cater to users with disabilities.
- Social and Competitive Features
    - - Specification: Integration with social media for sharing scores and achievements, a leaderboard for competitive play, and possibly a multiplayer mode.
- Personalization and Expansion
    - - Specification: Features that allow players to upload images of their teachers to be integrated into the game, with privacy and moderation guidelines in place.
