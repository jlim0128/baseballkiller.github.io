# Baseball-Killer Project Report

## Introduction
Baseball-Killer emerges as a pivotal solution in baseball management, introducing a statistical-driven approach to optimize batting orders. Traditional reliance on intuition is replaced by a user-friendly tool, offering managers an efficient means to experiment with lineups and make informed decisions. 

The project's scope encompasses developing a realistic baseball simulator, intuitive UI, and statistical visualizations, with a focus on user interaction and seamless data retrieval. Testing protocols ensure a robust user experience, while the project's boundaries exclude advanced analytics beyond batting order optimization. 

The chosen Agile project management approach, specifically Scrum, aligns seamlessly with the dynamic nature of Baseball-Killer.  Prioritizing iterative development and continuous feedback, this approach allows for adaptability and responsiveness to evolving user needs. In essence, Baseball-Killer holds significance in transforming decision-making in baseball, with a clearly defined scope and a tailored Agile approach ensuring success.

## Literature Review
The evolution of baseball analytics, as depicted in key works, serves as a foundation for our project, Baseball-Killer, which aims to optimize batting orders through a statistical-driven approach. Here's a concise review of pertinent literature:

1. **"Moneyball: The Art of Winning an Unfair Game" (Michael Lewis, 2003):**
   Lewis's classic explores the Oakland Athletics' data-driven strategies, inspiring Baseball-Killer's focus on statistical insights for batting order optimization. However, our project uniquely emphasizes user-friendly interaction and realistic game simulations. 

2. **"Analyzing Baseball Data with R" (Marchi, Albert, Baumer, 2014):**
   This collaborative work guides the practical application of statistical methods in baseball using R. Baseball-Killer aligns with its analytical spirit but goes further by incorporating a user-friendly interface and a realistic baseball simulator. 

3. **"Big Data Baseball" (Travis Sawchik, 2015):**
   Sawchik's work highlights the transformative power of analytics for the Pittsburgh Pirates. Baseball-Killer shares the goal of leveraging statistical insights but distinguishes itself by offering a user-friendly tool for batting order experiments and game simulations. 

In summary, existing literature lays the groundwork for data-driven approaches in baseball, while Baseball-Killer contributes by combining advanced analytics with a user-friendly interface for optimal decision-making in batting orders.

## Software Technologies
In our project, we employ a strategic blend of technologies to ensure optimal development and project success. For the frontend, we leverage Next.js, hosted on Vercel, offering a seamless and visually appealing display of player lineups through interactive baseball cards. This choice aligns with our goal of creating an intuitive user interface. The backend, powered by Python Flask, is hosted on GCP, providing robust scalability. The use of extensive Python Flask libraries facilitates the creation of dynamic graphs, enhancing the statistical visualization of player data. GitHub serves a dual purpose, acting not only as a version control system but also as a Scrum work management tool, ensuring efficient collaboration and task tracking. 

To maintain code quality, we employ pytest for backend unit testing, allowing us to validate data retrieval accuracy. Coverage Python library aids in ensuring comprehensive code coverage. Jest, paired with Next.js, is our choice for frontend unit testing, providing a reliable framework for testing React components. This cohesive selection of technologies streamlines tasks, supports efficient collaboration, and ensures the reliability and effectiveness of our lineup analysis tool.

## Project Lifecycle
Baseball-Killer undergoes a methodical development lifecycle, embracing Agile methodologies to ensure flexibility and responsiveness to evolving requirements. The project begins with a meticulous planning phase, defining objectives, scope, and the technology stack. Next.js is selected for the frontend, hosted on Vercel, providing an interactive and visually appealing interface for player lineups. Simultaneously, Python Flask on GCP forms the backend, handling data retrieval, graph creation, and seamless communication with the frontend. 

The iterative development stages include UI design, backend implementation, and integration. Scrum, a subset of Agile, guides these stages with short sprints, fostering collaboration and adaptability. GitHub's Kanban board facilitates task management, ensuring alignment with Minimum Marketable Features (MMFs). Continuous integration and deployment streamline the development process, with Vercel handling the frontend and GCP hosting the backend. 

Testing plays a crucial role, employing pytest for backend unit testing and Jest with Next.js for frontend components. This meticulous approach ensures code quality, data accuracy, and comprehensive coverage. Regular sprint reviews and continuous user feedback drive refinement, and the iterative nature of Scrum accommodates adjustments as needed.

## Requirements
### Functional Requirements (3 MMFs):
1. **Player Data Input:**
   Users can manually input players into the system, providing essential statistics such as batting average, home runs, and other relevant metrics. Alternatively, an automated option is available through a web scraper like pybaseball, offering seamless data retrieval from sources like baseballreference.com.

2. **Game Simulation:**
   The tool facilitates the simulation of baseball games based on user-defined lineups. Users have the flexibility to specify parameters such as the ballpark, season, and whether to simulate average player performances. The simulation generates outcomes, including runs scored, contributing to strategic decision-making.

3. **Statistical Insights:**
   Users gain access to in-depth statistical insights, including expected runs produced, Win-Loss records, and hits per game. The system provides intuitive visualizations for easy interpretation, enhancing the understanding of player and team performance. Additionally, a copy/paste option allows users to conveniently transfer and analyze the generated statistical data.

### Non-Functional Requirements:
1. **Data Security:**
   The system implements robust data security measures to protect player statistics. This includes encryption protocols and secure data storage, ensuring the confidentiality and integrity of sensitive information.

2. **Reliability:**
   To ensure a reliable user experience, the system efficiently handles game simulations, providing real-time results. This reliability is crucial for managers and enthusiasts relying on the tool for strategic decision-making.

3. **User-Friendly Interface:**
   The user interface is designed to be intuitive and user-friendly. Responsive design principles are applied, ensuring a seamless experience across various devices, from desktops to mobile platforms. This emphasis on usability enhances accessibility and overall user satisfaction.

## Design
The architecture of Baseball-Killer is structured for efficiency and scalability, employing a client-server model. The frontend, developed using Next.js, is hosted on Vercel, providing a responsive and visually appealing user interface for lineup analysis. On the backend, Python Flask is deployed on GCP, handling data retrieval, game simulation, and statistical computations. This separation allows for modular development, making it easier to scale and maintain each component independently. 

The low-level design is characterized by a robust and intuitive flow. The frontend interfaces with the backend through well-defined API endpoints, ensuring seamless communication. The backend utilizes Python Flask libraries for graph creation, enhancing statistical visualizations. The decision to integrate a web scraper like pybaseball enhances data accuracy, automating player statistics retrieval from online databases. 

These design decisions impact the project positively. The modular architecture facilitates easier maintenance and future updates. The use of Next.js and Python Flask aligns with the project's goals, providing a balance between performance and development flexibility. Challenges faced during the design process mainly revolved around ensuring a smooth integration between frontend and backend components, which were mitigated through iterative testing and refinements. Overall, the design prioritizes user experience, scalability, and system efficiency, contributing to the success of Baseball
