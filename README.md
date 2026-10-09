# LifeSkills Hub

Learn It. Practise It. Live It.

LifeSkills Hub is a web-based learning platform designed to help Nigerian students and adults develop practical life skills that are essential for everyday life but may not receive enough attention in traditional classroom education.

The platform focuses on practical learning, interactive challenges, and personal development to help learners build confidence, make informed decisions, and apply what they learn in real-world situations.

## 🎯 Project Goal

The goal of LifeSkills Hub is to make practical life-skills education accessible, engaging, and useful for learners at different stages of life.

The platform aims to bridge the gap between academic knowledge and the practical skills people need to succeed in school, work, business, and everyday life.

## ✨ Features

- **Learner Dashboard:** A central place to access learning activities and view progress.
- **Learning Paths:** Structured learning experiences tailored to different learner levels.
- **Financial Literacy:** Learn budgeting, saving, responsible spending, and money management.
- **Communication Skills:** Develop effective communication and listening skills.
- **Public Speaking:** Build confidence in expressing ideas and speaking to an audience.
- **Leadership and Teamwork:** Develop collaboration, leadership, and responsibility.
- **Critical Thinking:** Practise problem-solving, evaluating information, and decision-making.
- **Interactive Challenges:** Apply knowledge through practical scenarios and activities.
- **Progress Tracking:** Monitor lesson completion, skill development, and learning milestones.
- **Achievements:** Recognise learning milestones and encourage consistent practice.
- **Responsive Design:** Support desktop, tablet, and mobile screen sizes.

## 👥 Target Audience

LifeSkills Hub is designed for:

- Junior Secondary School (JSS) students.
- Senior Secondary School (SSS) students.
- Tertiary institution students.
- Adults seeking to improve their practical life skills.

## 🛠️ Technology Stack

The project is being developed with beginner-friendly web technologies.

| Technology         | Purpose                                        |
| ------------------ | ---------------------------------------------- |
| HTML5              | Page structure and content                     |
| CSS3               | Styling, layout, and responsive design         |
| Vanilla JavaScript | Interactivity and client-side functionality    |
| Supabase           | Planned authentication and PostgreSQL database |
| Git and GitHub     | Version control and project collaboration      |
| Netlify or Vercel  | Planned website deployment                     |

The frontend uses plain HTML, CSS, and JavaScript without React or other frontend frameworks.

## 🎨 Brand Identity

LifeSkills Hub uses a consistent colour palette across its pages.

| Colour           | Hex Code  | Usage                                 |
| ---------------- | --------- | ------------------------------------- |
| Primary Blue     | `#2563EB` | Buttons, links, and active navigation |
| Deep Blue        | `#1E40AF` | Headings and emphasis                 |
| Light Blue       | `#DBEAFE` | Highlights and information cards      |
| Teal Accent      | `#14B8A6` | Progress indicators and milestones    |
| Accent Light     | `#CCFBF1` | Soft teal backgrounds                 |
| Background White | `#F8FAFC` | Main page background                  |
| Surface White    | `#FFFFFF` | Cards and content surfaces            |
| Slate Text       | `#0F172A` | Primary text                          |
| Secondary Text   | `#475569` | Supporting text                       |
| Border           | `#E2E8F0` | Borders and dividers                  |

**Brand tagline:** Learn It. Practise It. Live It.

## 🚀 Getting Started

### Prerequisites

You will need:

- A modern web browser.
- [Visual Studio Code](https://code.visualstudio.com/).
- [Git](https://git-scm.com/) for version control.
- The VS Code Live Server extension (recommended for local development).

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project folder:

   ```bash
   cd LifeSkills-Hub
   ```

3. Open the folder in Visual Studio Code.

4. Run `index.html` using the Live Server extension, or open the file directly in your browser for basic static-page testing.

5. Explore the available pages and test the responsive layouts and JavaScript interactions.

Replace `YOUR_GITHUB_REPOSITORY_URL` with the actual URL of your GitHub repository.

## 🗄️ Database and Authentication

Supabase is planned as the backend service for LifeSkills Hub.

The intended backend functionality includes:

- Learner account registration and login.
- Secure user authentication.
- Storage of learner profiles with minimal necessary information.
- Tracking completed lessons and challenges.
- Saving learning progress and achievements.
- Retrieving learner-specific information.

Until these features are connected and tested, any progress figures, learner profiles, activities, or achievements displayed by the frontend should be treated as sample data.

### Security Considerations

- Use Supabase Row Level Security (RLS) to protect learner records.
- Use the Supabase publishable key, or the legacy anon key where applicable, in the frontend only with appropriate RLS policies.
- Never expose the Supabase service-role key or other secret credentials in client-side code.
- Never store passwords in `localStorage` or `sessionStorage`.
- Collect only the personal information necessary for the platform to function.
- Consider appropriate privacy and safeguarding requirements because the platform is intended to serve minors as well as adults.

## 🌍 Future Improvements

Potential future improvements include:

- More learning paths and practical scenarios.
- Personalised learning recommendations.
- Improved progress analytics.
- Additional achievements and milestones.
- Accessibility enhancements.
- More content relevant to Nigerian students and everyday life.
- Teacher, mentor, or facilitator features where appropriate.

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test the changes on desktop and mobile screen sizes.
5. Submit a pull request describing your improvements.

Please maintain the existing brand palette, accessible design principles, and plain HTML, CSS, and vanilla JavaScript approach.

## 🔒 Privacy

LifeSkills Hub aims to provide a safe and useful learning environment. Any production deployment should have appropriate privacy disclosures, secure access controls, and suitable safeguards for younger learners.

Do not submit real learner personal information, passwords, API secrets, or other sensitive data to the repository.

## 📄 License

No license has been selected yet. Unless a license is added to the repository, the project should not be assumed to be available for unrestricted reuse or redistribution.

## 👨‍💻 Project Vision

LifeSkills Hub is built on the belief that education should prepare people not only to pass examinations, but also to navigate everyday life with confidence.

By combining structured learning with practical challenges, the platform aims to help learners develop skills they can use in school, at work, in business, and in their communities.

**LifeSkills Hub — Learn It. Practise It. Live It.**
