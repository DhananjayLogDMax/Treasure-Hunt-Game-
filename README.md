<h1 align="center"> 🏰✨ MAGICAL TREASURE HUNT ✨🗡️ </h1>

<p align="center">
*"Bazinga! Just kidding, this isn't about pranks - it's about TREASURE!"*
</p>

<div align="center">
<img src="https://github.com/DhananjayLogDMax/Treasure-Hunt-Game-/blob/main/image/Voldemort.jpg" width="30%">
</div>

<br>

Hey there, fellow code warrior! 👋 Welcome to what might just be the most ridiculously awesome text-based adventure you'll stumble upon today. This baby right here? It's a magical treasure hunt that'll have you questioning your life choices while simultaneously having the time of your life! 🎢

**🎓 Academic Achievement Unlocked**: This epic creation emerged from a DSA (Data Structures and Algorithms) project assignment, demonstrating that education becomes entertaining when you sprinkle in magical elements and cringe-worthy wordplay. Developed alongside my awesome buddy <a href="https://github.com/hritik-kumar" target="_blank">Hritik Kumar</a> 👦 who likely wonders about our sanity just as much as I question mine! 🤝💻

<br>

## 🤔 So... What Even IS This Thing?

Imagine you're stuck in a terminal (shocking, I know), but instead of staring at boring system logs, you're exploring a freaking CASTLE! 🏰 This isn't your grandma's text adventure - oh no, this is a full-blown quest where you get to:

- 🚶‍♀️ Wander around 10 different spooky/magical rooms
- 🧙‍♂️ Get quizzed by wizards who are WAY too smart for their own good
- 💀 Try not to die (spoiler alert: you might die)
- 💎 Actually find some legendary treasure if you're not completely hopeless

Think of it as Dungeons & Dragons meets Harry Potter meets "Why Did I Choose Computer Science Again?" 🎲⚡

<br><br><br>

## 🎯 What Makes This Game Absolutely Bonkers (In a Good Way)

- 🏠 **10 Wild Locations**: From creepy dungeons to fancy libraries (because even adventurers need to read sometimes)
- 🧙 **5 Wizard Encounters**: Each one more determined to stump you than the last
- 💖 **Lives System**: You get exactly 2 chances to not mess up completely
- 🗺️ **Map Feature**: Because getting lost in real life is bad enough
- 🎨 **Pretty Colors**: Your boring terminal just got a makeover!
- ⏰ **Timer**: So you can see exactly how long it took you to either win or fail miserably
- 👣 **Step Tracker**: For people who like numbers (you know who you are)

<br><br><br>

## 🧙‍♀️ The Wizard Lineup (AKA Your New Worst Enemies)

<div align="center">
<img src="https://github.com/DhananjayLogDMax/Treasure-Hunt-Game-/blob/main/image/wizards.jpg" width="60%" alt="The Wizard Squad">
</div>

<br>

### 🎩 Dumbledore (The "Easy" One)
*Asks about levitation charms*
- Difficulty: Kindergarten level (supposedly)

### 🦇 Snape (The Grumpy One)
*Tests your Horcrux knowledge*  
- Difficulty: "Did you actually read the books?" level

### 🐺 McGonagall (The Riddle Master)
*Classic brain teaser incoming*
- Difficulty: "I need to think about this" level

### 🕷️ Hagrid (The Animal Guy)
*Magical creatures pop quiz*
- Difficulty: "Why do I need to know this?" level

### 🐍 Voldemort (The Final Boss)
*Dark magic expertise required*
- Difficulty: "I should have studied harder" level

<br><br><br>

## 🚀 How to Actually Play This Thing

<div align="center">
<img src="https://github.com/user-attachments/assets/45d4a9c6-aac4-4a55-b308-72a132f4b608" width="50%" alt="Coding in action">
</div>

### What You Need:
- A computer (obviously)
- A C compiler (GCC works great)
- Some basic Harry Potter knowledge (seriously, go watch the movies at least)
- Patience (more than Sheldon has for people who don't understand theoretical physics)
- Coffee (optional but highly recommended) ☕

<br>

### 📥 Getting It Running:

```bash
# Grab the code
git clone https://github.com/DhananjayLogDMax/magical-treasure-hunt.git

# Jump into the folder
cd magical-treasure-hunt

# Compile it (cross your fingers)
gcc -o treasure_hunt treasure_hunt.c

# Let the chaos begin!
./treasure_hunt
```

### For Windows Users (Our Condolences):
```cmd
# Use WSL or suffer in silence
# Or try: gcc treasure_hunt.c -o treasure_hunt.exe
```

<br><br>

### 🕹️ Actually Playing:

1. **Start**: Run the thing and get ready for an adventure
2. **Move**: Pick a direction (1=North, 2=South, 3=East, 4=West)
3. **Survive**: Answer wizard questions without having a mental breakdown
4. **Map**: Hit 5 to see where you've been (lifesaver!)
5. **Win**: Find that treasure room and claim victory
6. **Quit**: Press 6 if you need to rage quit (no judgment here)

### Controls (Because Apparently This Needs Explaining):
- **1** - Go North ⬆️ (up, away from your problems)
- **2** - Go South ⬇️ (down, toward your destiny)  
- **3** - Go East ➡️ (right, because left is wrong)
- **4** - Go West ⬅️ (left, but we don't talk about that)
- **5** - Show Map 🗺️ (for when you're hopelessly lost)
- **6** - Quit 🚪 (coward's way out)

<br><br><br>

## 📸 In-Game Screenshots

<div align="center">
<img src="https://github.com/DhananjayLogDMax/Treasure-Hunt-Game-/blob/main/image/gameplay1.jpg" width="50%"><img src="https://github.com/DhananjayLogDMax/Treasure-Hunt-Game-/blob/main/image/gameplay2.jpg" width="50%">
</div>

<div align="center">
<img src="https://github.com/DhananjayLogDMax/Treasure-Hunt-Game-/blob/main/image/gameplay3.jpg" width="50%">
</div>

<br><br><br>

## 🔧 The Nerdy Technical Stuff

For my fellow programming enthusiasts who care about the behind-the-scenes magic:

This isn't just some thrown-together code from a late-night coding session (although those definitely happened). We've got:

### 🏗️ Architecture That Actually Makes Sense:

- **Language**: C (because we hate ourselves and love pointers)
- **Room System**: Each location connects to others through a network of possibilities
- **Wizard Logic**: Questions with multiple choice answers and proper validation
- **Path Memory**: Stack-based tracking so you know where you've been
- **Input Handling**: Because users will try to break everything (it's a law of nature)
- **Pretty Output**: Color-coded text because plain white text is for quitters

```c
// Making terminals beautiful since forever
#define BLUE "\033[1;34m"    // For important headings
#define GREEN "\033[1;32m"   // For when you don't mess up
#define RED "\033[1;31m"     // For when you definitely mess up
```

### Code Statistics (That Nobody Asked For):
- **Lines of Code**: 400+ (every single one fought for)
- **Functions**: 15+ (decomposition is key, kids)
- **Structs**: Room, Wizard, Question (the perfect trio)
- **Debugging Hours**: We don't talk about those dark times
- **Caffeine Intake**: Probably unhealthy levels
- **Fun Factor**: Through the roof! 🚀

<br><br><br>

## 🐞 Things That Might Not Work Perfectly

Look, we're honest about our code:

1. **Hagrid's Answer**: Might be slightly off, but he's always been a bit confused anyway
2. **Memory Management**: We allocate things... freeing them is a work in progress
3. **Spelling**: "Dumbeldore" instead of "Dumbledore" - it's called character building!
4. **Wizards might judge your life choices** (working as intended)
5. **You might get addicted to this pointless game** (seek help)

These aren't bugs, they're "personality traits" of the software! 😅

<br><br><br>

## 🎓 What You'll Learn

This project is actually educational (surprise!):
- **Data Structures**: Arrays, structs, linked lists
- **Algorithms**: Pathfinding, validation, game state management  
- **C Programming**: Pointers, memory, modular design
- **Problem Solving**: Game logic and user experience
- **Pop Culture**: Harry Potter trivia (arguably the most important skill)

<br><br><br>

## 🤝 Want to Help Make It Better?

<div align="center">
<img src="https://github.com/user-attachments/assets/88c3409c-505d-474e-b4ce-e2cb4dbc8705" width="40%" alt="Join the madness">
</div>

<br>

Got ideas? Found bugs? Think our jokes are terrible? 

Jump in and contribute! Just remember:
- Keep it fun and nerdy
- Harry Potter references are always welcome
- Big Bang Theory quotes get bonus points
- Don't roast our variable names too hard

### How to Contribute:
1. Fork this repository (hit that button like it owes you money)
2. Create a branch (`git checkout -b feature/amazing-addition`)
3. Make your changes (try not to break everything)
4. Test thoroughly (please, for the love of Dijkstra)
5. Submit a pull request (explain your genius)

<br><br><br>

## 📱 Find the Creators

<div align="center">
<img src="https://github.com/user-attachments/assets/0c4c1c7a-3844-4760-8519-1faeedf0ca36" width="40%" alt="Contact us">
</div>

<br>

### 🧑‍💻 DhananjayLogDMax

- **GitHub**: [https://github.com/DhananjayLogDMax](https://github.com/DhananjayLogDMax) *(Where all the code magic happens)*
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/your-profile) *(For professional stuff and networking)*
- **Email**: your.email@example.com *(Professional inquiries and existential programming discussions)*

*Fun Fact: I avoid most social media platforms because they're like infinite loops - easy to get stuck in and hard to break out of! LinkedIn is the exception because networking is important, unlike knowing what someone had for breakfast.* 🤓

<br><br><br>

## 📚 The Story Behind This Madness

This whole project started as a **Data Structures and Algorithms assignment** that me and my awesome coding buddy decided to tackle together. Because nothing says "true friendship" like debugging pointer errors at 2 AM while running on nothing but determination and way too much caffeine! 👥💻

*"The best code is written by friends who aren't afraid to tell each other when their logic is completely wrong."* 🤝

Here's the thing: *"Every great programmer started with a simple game, a lot of curiosity, and an unhealthy relationship with their compiler."*

<br><br><br>

## 📄 Legal Stuff

This project lives under the "Use It However You Want But We're Not Responsible If Things Go Wrong" license. Learn from it, change it, or just appreciate our amazing comments. (Actually, it's probably MIT, but the sentiment remains.)

<br><br><br>

## 🙏 Acknowledgments

- **Harry Potter Universe** - For providing riddle inspiration and childhood magic
- **My Terminal** - For enduring countless compilation errors
- **Stack Overflow** - My real programming teacher
- **Coffee** - The true MVP of this project ☕
- **My Sanity** - Sacrificed for your entertainment
- **Anyone who actually plays this** - You're the real heroes

<br><br><br>

## 🎉 Final Words

<div align="center">
<img src="https://github.com/user-attachments/assets/55458d1b-58a8-40af-9bd0-b01b64192e3a" width="30%" alt="Victory dance">
</div>

<br>

This game represents approximately 47 hours of our lives that we'll never get back, 23 cups of coffee, 8 existential crises, and 1 moment of pure satisfaction when it finally compiled without warnings.

May your code compile without warnings, your logic flow like butter, and your treasure hunt be absolutely legendary! 🏆

Now go forth and hunt some treasure, you magnificent code wizard! ⚔️🏰✨

*May your pointers never be null, and may your segfaults be few.*

**Happy Adventuring! 🎮✨**

---

*P.S. If you made it through this entire README, you're officially part of the "I Actually Read Documentation" club. Membership perks include our respect and maybe a LinkedIn connection if you're lucky!* 🏅

*P.P.S. - If you actually read this entire README, you either have too much time on your hands or you're procrastinating on something important. Either way, welcome to the club! 🤓*
