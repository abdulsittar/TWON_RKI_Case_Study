# TWON RKI case study application
A MERN stack based social media application (MongoDB Express React Redux NodeJs).

## Overview
This tool allows researchers to run controlled social media experiments with real users in a realistic but fully managed environment. It is designed to study how people interact with scientific content, misinformation, and different communication strategies online.

In one example study conducted in Germany in collaboration with the Robert Koch Institute, the platform was used to examine two main topics: pre-bunking misinformation and communicating statistical uncertainty. The study was based on real social media posts previously developed by the institute. These posts focused on vaccines, including mRNA vaccines for pre-bunking scenarios and the Monkeypox vaccine for uncertainty communication.

The study was conducted over several days in March 2025. Participants were recruited through Prolific and were required to be located in Germany, fluent in German, and have a high prior approval rate. More than 1,200 participants completed the study. They were randomly assigned to different groups, including control and treatment conditions, to test the effects of different messaging strategies.

Overall, this platform enables researchers to design and evaluate social media interventions, conduct randomized experiments, compare different communication approaches, and collect structured interaction data. It provides a flexible and modular environment for studying online behavior in a controlled setting.

Website : [(https://socialapp.ijs.si/)](https://socialapp.ijs.si/)

# Study Flow in the App
1. Landing page
2. Consent form
3. Pre-survey
4. Username choice
5. Feed (participants must write at least 3 comments and give some likes)
6. Post-survey

### Flow Screenshots
1. Landing page
![landing page](screenshots/rki%20screenshots/landingpage.png)

2. Consent form
![consent form](screenshots/rki%20screenshots/consent_form.png)

3. Pre-survey
![pre-survey](screenshots/rki%20screenshots/presurvey.png)

4. Username choice
![username choice](screenshots/rki%20screenshots/username_choice.png)

5. Feed
![feed](screenshots/rki%20screenshots/feed.png)

6. Post-survey
![post-survey](screenshots/rki%20screenshots/postsurvey.png)

# Project Structure
The repository is organized into two main applications:
- `server/`: Node.js + Express backend, API routes, controllers, models, middleware, and admin views.
- `client/`: React frontend application, pages, components, context, and static assets.

At the root:
- `docker-compose.yml`: container orchestration.
- `package.json`: root-level scripts/dependencies.
- `README.md`: project documentation.


# How to Run
1. Make sure MongoDB is available and configured.
2. Install dependencies:
    - Run `npm install` in `/server`.
    - Run `npm install` in `/client`.
3. Start backend:
    - In `/server`, run `npm start`.
4. Build frontend:
    - In `/client`, run `npm run build`.


