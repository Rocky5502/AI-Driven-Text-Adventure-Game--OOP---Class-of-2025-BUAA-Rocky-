# AI-Driven-Text-Adventure-Game--OOP---Class-of-2025-BUAA-Rocky-
OOP Java experiment on AI-driven text adventure games with infinite narratives and community sharing – BUAA 2025.


# AI-Driven Text Adventure Games and Communities-ROCKY

An innovative web-based text adventure game powered by AI language models, featuring dynamic narratives, random events, and a sharing community. This project explores infinite storytelling, where players, AI, and the community co-control the experience.

## About the Project
This is a java project developed by Rocky (文浩), Class of 2025, School of Computer Science and Engineering, Beihang University (BUAA). Created as part of the Object-oriented Programming in Java Experiment course under Prof. Dr. Runhua Xu, December 2025， Beijing, China.

The project addresses the evolution of story-driven games:
- **Product Story**: Story-driven games advance through compelling narratives, with vivid characters and player-influenced directions. Examples include *The Last of Us* (2013, >37M sales), *Detroit: Become Human* (2019, ~10M sales), and *Death Stranding* (2019, >16M sales).
- **Audience Needs**: Satisfies curiosity for fresh stories amid busy lives, fragmented time, and mental exhaustion. Targets "cloud gamers" who experience stories via streams/videos without playing, due to time constraints and fixed storylines.
- **Challenges**: In today's busy world, greater life pressure leads to less time/energy, more "cloud gamers," and lower conversion rates – a key industry issue.
- **Innovation**: Enhances story richness from linear (fixed path) to non-linear (multiple endings) to infinite narratives (unique per player, varying greatly).
- **Core Question**: Who controls the story – the player, the AI, or the community?
- **AI Role**: Generative AI enables unlimited storylines, making games highly replayable and personalized.
- **Features**:
  - Custom game backgrounds (e.g., alien exploration, post-apocalyptic survival, magic worlds).
  - AI-generated scenes, images, random events, and choices.
  - Cross-platform community for one-click sharing, downloading creations, and discussions.
- **Market Opportunity**: Text-based AI games are rising, especially among creative players, story enthusiasts, tech fans, and casual users. Global games market: ~USD 238B in 2024, projected 268–282B in 2025.
- **Business Model**: Revenue via ads, subscriptions (ad-free, VIP), and in-game purchases (e.g., revival cards).
Ensure files are organized as follows:<img width="1920" height="1080" alt="Technical Architecture" src="https://github.com/user-attachments/assets/ed701394-e974-4e40-b8a3-3e31ca17a289" />
<img width="1920" height="1080" alt="Technical -System Architecture" src="https://github.com/user-attachments/assets/e333b615-6adf-437c-994f-a1ffc530341d" />
<img width="1920" height="1080" alt="Game Features" src="https://github.com/user-attachments/assets/c26f5a3b-97fe-45c0-8e83-016be3d1c6d5" />


This project demonstrates OOP principles in Java (encapsulation, inheritance, polymorphism) applied to game logic, AI integration, and community backend.

The project was developed using NVIDIA RTX 5070 Ti for GPU-accelerated AI computations and MacBook Air M2 for general development and testing.

## File Structure


- `algo/`: Algorithm-side source code (e.g., AI model integration).
- `backend/`: Backend source code (e.g., Spring Boot logic).
- `frontend/`: Frontend source code (e.g., Vue.js interfaces).
- `docs/`: Documents, including experiment reports and PPTs (e.g., final presentation).

## Project Origin
Traditional text adventures rely on fixed scripts, limiting playability. AI-driven games introduce randomness and unpredictability, depending on event design and frameworks for quality.

## Overall Design
Web app with two parts:
1. **AI Text Adventure Game**: Uses language models for plot evolution and interactive random events.
2. **Sharing Community**: Users share events, reproduction steps, and discuss explorations.

## Implementation Steps
Developed solo in parallel:
- **Game Core**:
  1. Built framework, random events, resources; analyzed requirements.
  2. Debugged AI outputs; packaged APIs.
  3. Designed frontend; implemented game.
- **Community**:
  1. Analyzed user needs; designed interfaces.
  2. Designed frontend; built platform.
  3. Integrated with game for backend sync.

## Project Implementation
### Existing Foundations
- High-performance Chinese language model for NLP.
- GPU cluster for computations.
- Spring Boot for Java backend.
- Vue.js for frontend.

### Tools Used
- Apifox: API management.
- Spring Boot: Backend development.
- Vue (with Vuex, Vue Router): Frontend SPAs.
- Feishu: Document management.
- Git: Version control.

### Workload Statistics
Used Intermediate COCOMO model:
- Effort: \( Effort = EAF \times a \times (KLOC)^b \)
- Duration: \( Duration = c \times (Effort)^d \)
- Organic Mode (code): a=2.4, b=1.05, c=2.5, d=0.38
- Semi-Detached Mode (docs): a=3.0, b=1.12, c=2.5, d=0.35

## Getting Started
1. Clone the repo: https://github.com/Rocky5502/AI-Driven-Text-Adventure-Game--OOP---Class-of-2025-BUAA-Rocky-.git.
2. Install dependencies (Java, Node.js, etc.).
3. Run backend: `mvn spring-boot:run` (or similar).
4. Run frontend: `npm run serve`.
5. Access at `localhost:8080` (adjust ports as needed).

## Demo
Input a worldview (e.g., "Magic world: Defeat the demon king") and make choices in AI-generated scenarios. Share standout moments in the community!

## License
MIT License – feel free to use and contribute.


## Acknowledgments
I am grateful to the School of Computer Science and Engineering at Beihang University for the excellent resources and environment.
Special thanks to Prof. Dr. Runhua Xu for his guidance and feedback throughout the Object-Oriented Programming in Java Experiment course.
I also thank my labmate Kerney and others for their valuable help during implementation, including brainstorming and debugging support.
Finally, I appreciate all the contributions that made this project possible.

## Contact
Rocky (文浩) –sahchandan98@buaa.edu.cn
