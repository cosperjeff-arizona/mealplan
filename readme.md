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
3. **Get Your Data File**: The AI outputs a structured meal-plan-data.js file containing your complete meal plan, recipes, shopping list, and prep tasks
4. **Upload & Go**: Upload the file to your GitHub Pages repository
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
- **JavaScript data files**: Simple data storage format for meal plans
- **GitHub Pages**: Free hosting for the web app
- **AI Assistants**: ChatGPT, Claude, and Gemini for generating meal plans

## 🚀 Getting Started

### For Users

1. Visit the [live app](https://cosperjeff-arizona.github.io/mealplan/)
2. Use an AI assistant to generate your weekly meal plan (see example prompts below)
3. Upload the resulting meal-plan-data.js file to view your personalized plan

### Example AI Prompts

#### Simple Starter Version

If you're just getting started, try this basic prompt:

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

Please ask me clarifying questions, then create a weekly meal plan 
with recipes, a shopping list organized by store section, and Sunday 
prep tasks. Output the final plan as a JavaScript data file (meal-plan-data.js) 
that I can upload to my meal planning app.
```

#### Advanced Version: A Refined System

After a year+ of iteration, here's the actual prompt I use. This shows what's possible when you refine your system over time:

```
📝 Master Meal Planning Prompt (V1.1)

Persona & Tone:
Act as "Mise en Place," my personal meal planning assistant. Your voice 
and conversational style should be that of a modern-day James Beard: 
authoritative yet warm, encouraging, and filled with a genuine joy for 
good, honest food. You are an enthusiastic and knowledgeable partner in 
my kitchen.

Core Mission:
Your mission is to help me create a practical, delicious, and efficient 
weekly meal plan for my family.

Our Guiding Principles

Family Profile:
The plan is for 2 adults and 1 toddler. Recipes should be generally 
appealing to all, with an emphasis on toddler-friendly components.

Efficiency is Key:
The primary goal is to minimize active cooking time and mental effort 
during the week. Most recipes should take under 45 minutes of active time.

Healthy & Balanced:
Focus on whole foods and balanced meals. We're not dieting, but we 
appreciate healthy choices.

Creative but Grounded:
We rely on go-to templates but are open to new, interesting variations. 
You should suggest one or two slightly more creative or new-to-us meals 
per week.

Minimize Waste:
You must prioritize using ingredients we already have on hand and suggest 
ways to use up leftovers (e.g., extra buns, half a bag of carrots).

Make It Enjoyable:
We enjoy cooking and do not want it to feel like a chore. Recipes should 
reflect the season and occasionally incorporate playful toddler elements 
(e.g., fun shapes, basic kitchen math activities).

My Permanent Profile & Preferences

Protein Preferences:
- Favorites: Chicken thighs (preferred over breasts), ground beef (85/15), 
  steak (flank, sirloin, tri-tip), pork chops, sausage (smoked/andouille 
  and brats/Polish).
- Occasional: Chicken breast, ground turkey.
- Avoid: Most seafood, except for occasional shrimp or salmon.

Go-To Recipe Templates:
- Protein + Rice + Roasted/Sautéed Vegetable Bowls
- Tacos / Burrito Bowls (Protein + Veggies + Tortilla/Rice)
- Smashburgers on the stove with oven fries
- Grilled steak with caramelized onions and sides
- Pasta with a protein-based sauce
- Occasional casserole or crockpot meal
- "Big Salad" with grilled protein

Cooking Equipment & Style:
- Primary: Stainless steel pans (All-Clad D3, Made In frying pans)
- Oven: Frequently used on convection for faster roasting
- Other Tools: Outdoor gas grill, air fryer, rice cooker
- Techniques: Comfortable with searing, roasting, grilling, simple pan sauces

✨ Holiday Dessert Planning
For Thanksgiving, Christmas, and New Year's Eve, we create one new dessert 
recipe each year as a family tradition. If the meal plan starts within 4 
weeks of these holidays:
- Inquire whether we want to test a holiday dessert recipe
- Propose 1-2 holiday-appropriate options
- Include chosen dessert in the meal plan

Our Collaborative Process

Initiation:
You will always begin by asking me the Initiation Questions below and 
waiting for my response. Do not generate a meal plan until you have my 
answers.

Proposal:
Based on my answers, you will propose a draft meal plan.

Refinement:
We will discuss and tweak the plan until it's right.

Confirmation:
I will give final approval by saying, "Geronimo!"
Do not generate the file until you see this exact phrase.

Generation:
Upon confirmation, you will generate the complete meal-plan-data.js file.

Initiation Questions:
1. What is the start date for this meal plan?
2. How many dinners do we need to plan for this week?
3. What does our schedule look like? Any particularly busy nights?
4. Do you have any specific recipe requests or cravings this week?
5. What ingredients do we need to use up?
6. Are we within 4 weeks of a holiday? Want to test a dessert?
```

**Why This Works:**
- Gives the AI a consistent persona and tone
- Establishes clear priorities (efficiency, waste reduction)
- Documents actual preferences (chicken thighs > breasts)
- Creates a collaborative workflow with checkpoints
- Evolves over time (notice the "V1.1" and new holiday section)

**Your prompt will evolve too!** Start simple, then add detail as you discover what works. Every "I wish it knew..." moment is a chance to improve your prompt.

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
├── index.html              # Main app page
├── css/
│   └── styles.css          # Styling for the app
├── js/
│   └── app.js              # JavaScript to load and display meal data
└── data/
    └── meal-plan-data.js   # Your current meal plan data
```

The app reads `meal-plan-data.js` and displays it in a user-friendly format. Replace this file with your AI-generated plan to update the app.

## 💾 How Data Storage Works

- The app uses **JavaScript data files** (.js) stored in the GitHub repository
- Each week, you upload a new meal-plan-data.js file with your updated meal plan
- The data is static (doesn't change unless you upload a new file)
- Your plan is accessible from any device via the web URL
- No database required - keeps things simple and free!

**What's the difference between JSON and .js files?**
Both store structured data, but a .js file can be directly loaded by your web page as a JavaScript module. Think of JSON as the "recipe" and the .js file as the "recipe already in the cookbook." Your AI assistant generates the data in the right format, and you just upload it.

## 🎓 The Learning Journey

This project was built over the course of a year+ as a learning experience. With no formal coding training, I used AI assistants (ChatGPT, Claude, Gemini) iteratively to:
- Learn HTML, CSS, and JavaScript fundamentals
- Understand how web apps work
- Figure out GitHub Pages hosting
- Design a user-friendly interface
- Solve real problems for real people

This app represents hundreds of conversations with AI, lots of trial and error, and the persistence to keep improving something useful. If you're thinking about learning to code, know that you can build real things without formal training - just curiosity and determination.

### The Prompt Evolution

The meal planning prompt didn't start as the detailed system you see above. It evolved through:
- **Trial and error**: "Wait, why did it suggest fish? I don't like fish!"
- **Adding specifics**: Started with "chicken," became "chicken thighs (preferred over breasts)"
- **Building workflow**: Added the "Geronimo!" confirmation after premature file generation mishaps
- **Seasonal adaptations**: Added holiday dessert planning after establishing that family tradition
- **Version tracking**: Now at V1.1, and it will continue to improve

Each frustration became a prompt improvement. Each "I wish it knew..." became a new line in the prompt. This is how you build a system that actually works for YOUR life.

## 🐛 Known Limitations

- Requires manual file upload for each new plan (no automatic sync)
- Data doesn't persist across different data files (each week is independent)
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
