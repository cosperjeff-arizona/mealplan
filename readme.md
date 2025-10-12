# Mise en Place 🍽️

An AI-powered meal planning app designed to reduce decision fatigue and distribute the mental load of home economics for busy families.

**Live Demo:** [https://cosperjeff-arizona.github.io/mealplan/](https://cosperjeff-arizona.github.io/mealplan/)

## 🎯 The Problem

Meal planning is exhausting for families with young kids. Parents are already stretched thin on time and energy, and the constant cycle of deciding what to cook, shopping, and preparing meals creates:
- **Decision fatigue** from endless "what's for dinner?" questions
- **Mental load imbalance** when one person handles all the planning
- **Family conflict** around meal decisions and execution
- **Time waste** without a clear structure or process

Most meal planning apps still require YOU to do all the thinking. This one is different.

## 💡 The Solution

**Mise en Place** (French for "everything in its place") shifts meal planning from *ideation → execution* to *approval → execution*. Instead of planning meals yourself, you work with an AI assistant to generate a personalized weekly plan, then use this app to execute it beautifully.

### How It Works

1. **Generate Your Plan**: Send a prompt to your preferred AI (ChatGPT, Claude, Gemini, etc.) describing your preferences, dietary needs, cooking skill level, time constraints, and family dynamics
2. **Refine Together**: The AI chats with you to understand your needs and creates a tailored weekly meal plan
3. **Get Your JSON**: The AI outputs a structured JSON file containing your complete meal plan, recipes, shopping list, and prep tasks
4. **Upload & Go**: Upload the JSON file to your GitHub Pages repository
5. **Access Anywhere**: Open the app on your phone, tablet, or computer - your plan is ready to follow

### Why This Approach?

- **Novice-Friendly**: Whether you're a casual home cook or a trained chef, the AI tailors the plan to YOUR skill level
- **Outsources Decisions**: No more staring at the fridge wondering what to make - the AI handles the creative work
- **Reduces Conflict**: Shifts the conversation from "What should we eat?" to "Does this plan work for us?"
- **Distributes Mental Load**: Anyone in the household can execute the plan without needing to know all the context

## ✨ Features

- **📅 Weekly Planning**: See your entire week's meals at a glance
- **🛒 Smart Shopping Lists**: Organized by grocery store section for efficient shopping
- **🔪 Sunday Prep**: Batch prep tasks to make weeknight cooking easier
- **📖 Recipe Cards**: Step-by-step instructions with ingredients and timing
- **🖨️ Print-Friendly**: Print your plan for easy kitchen reference
- **📱 Mobile-Responsive**: Access on any device, anywhere

## 🛠️ Built With

- **HTML/CSS/JavaScript**: Core web technologies
- **JSON**: Simple data storage format for meal plans
- **GitHub Pages**: Free hosting for the web app
- **AI Assistants**: ChatGPT, Claude, and Gemini for generating meal plans

### What's JSON?

JSON (JavaScript Object Notation) is just a simple way to store information in a text file that websites can read. Think of it like a digital recipe card - it's organized, structured, and easy for the app to understand. When you upload a JSON file with your meal plan, the app reads it and displays everything nicely formatted.

## 🚀 Getting Started

### For Users

1. Visit the [live app](https://cosperjeff-arizona.github.io/mealplan/)
2. Use an AI assistant to generate your weekly meal plan (see example prompt below)
3. Upload the resulting JSON file to view your personalized plan

### Example AI Prompt

```
I need a weekly meal plan for my family. Here's our context:

- Family size: [number of people, ages]
- Dietary restrictions: [vegetarian, allergies, preferences]
- Cooking skill level: [beginner, intermediate, advanced]
- Available time: [how much time you have on weeknights]
- Kitchen equipment: [slow cooker, instant pot, etc.]
- Budget: [low, medium, high]
- Cuisine preferences: [Italian, Mexican, Asian fusion, etc.]
- Other notes: [picky eaters, meal prep preferences, etc.]

Please chat with me to refine the details, then output a JSON file 
with a weekly meal plan including recipes, shopping list organized 
by store section, and Sunday prep tasks.
```

### For Developers

```bash
# Clone the repository
git clone https://github.com/cosperjeff-arizona/mealplan.git
cd mealplan

# Open index.html in your browser or run a local server
# For example, with Python:
python -m http.server 8000
# Then navigate to http://localhost:8000
```

## 📂 Project Structure

```
mealplan/
├── index.html          # Main app page
├── css/
│   └── styles.css      # Styling for the app
├── js/
│   └── app.js          # JavaScript to load and display JSON data
└── data/
    └── weekly-plan.json # Your current meal plan
```

The app reads `weekly-plan.json` and displays it in a user-friendly format. Replace this file with your AI-generated plan to update the app.

## 💾 How Data Storage Works

- The app uses **JSON files** stored in the GitHub repository
- Each week, you upload a new JSON file with your updated meal plan
- The data is static (doesn't change unless you upload a new file)
- Your plan is accessible from any device via the web URL
- No database required - keeps things simple and free!

## 🎓 The Learning Journey

This project was built over the course of a year+ as a learning experience. With no formal coding training, I used AI assistants (ChatGPT, Claude, Gemini) iteratively to:
- Learn HTML, CSS, and JavaScript fundamentals
- Understand how web apps work
- Figure out GitHub Pages hosting
- Design a user-friendly interface
- Solve real problems for real people

This app represents hundreds of conversations with AI, lots of trial and error, and the persistence to keep improving something useful. If you're thinking about learning to code, know that you can build real things without formal training - just curiosity and determination.

## 🐛 Known Limitations

- Requires manual JSON file upload for each new plan (no automatic sync)
- Data doesn't persist across different JSON files (each week is independent)
- Works best on tablet/desktop for full recipe view
- No built-in AI integration (requires using external AI assistant)

## 🚧 Future Ideas

- [ ] Direct AI integration (generate plans within the app)
- [ ] Recipe scaling based on servings
- [ ] Leftover tracking and suggestions
- [ ] Shopping list checkbox feature
- [ ] Export/print individual recipes
- [ ] Mobile app version
- [ ] Family member task assignment
- [ ] Meal history and favorites

## 🤝 Who This Is For

- **Busy parents** drowning in the mental load of meal planning
- **Couples** wanting to share household responsibilities more equitably  
- **Anyone** experiencing decision fatigue around meals
- **New cooks** who want guidance without feeling overwhelmed
- **Experienced cooks** who want to try new things without the planning work

## 📝 License

This is a personal project. Feel free to fork, adapt, and use for your own meal planning needs!

## 🙏 Acknowledgments

- Built with extensive help from AI coding assistants (ChatGPT, Claude, Gemini)
- Inspired by the real challenges of family meal planning
- Thanks to everyone who gave feedback and encouragement along the way

---

*Made with ❤️ and a lot of AI assistance to help families reclaim their time and reduce stress around meals.*
