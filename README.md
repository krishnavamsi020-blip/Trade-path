# 🎮 TradePath

> **Master the supply chain, one turn at a time**

An interactive educational game that transforms complex supply chain management concepts into an exciting 4-player race. Learn inventory management, cash flow, and strategic planning through hands-on gameplay.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-brightgreen)](https://github.com/yourusername/tradepath)

![TradePath Game Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=TradePath+Game+Screenshot)

---

## 📖 Table of Contents

- [About](#about)
- [Game Features](#game-features)
- [How to Play](#how-to-play)
- [Educational Value](#educational-value)
- [Quick Start](#quick-start)
- [Game Mechanics](#game-mechanics)
- [Player Roles](#player-roles)
- [Technologies](#technologies)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 About

**TradePath** is a browser-based supply chain simulation game where 4 players compete to successfully manage their role in a complete supply chain. From manufacturing to retail, players experience real-world business challenges including:

- 📦 **Inventory Management** - Balance stock levels to meet demand
- 💰 **Cash Flow** - Manage limited resources wisely
- ⏰ **Delivery Lag** - Plan ahead with 2-turn order delays
- 🎲 **Market Uncertainty** - Adapt to random demand and events
- 🏆 **Strategic Planning** - Compete to reach success first

Perfect for **students**, **educators**, **business learners**, and anyone curious about how products flow from factory to customer!

---

## ✨ Game Features

### 🎭 4 Unique Player Roles
Each player represents a critical link in the supply chain:

| Role | Icon | Responsibility |
|------|------|----------------|
| **Manufacturer** | 🏭 | Creates products in the factory |
| **Distributor** | 🚚 | Ships products to multiple locations |
| **Wholesaler** | 🏪 | Buys in bulk and sells to stores |
| **Retailer** | 🛒 | Sells directly to customers |

### 🎮 Engaging Gameplay
- **Simple 3-Step Turns** - Roll dice → Order inventory → Fulfill demand
- **Visual Supply Chain** - See the flow from factory to customer
- **Real-Time Stats** - Track cash, inventory, demand, and orders
- **Random Events** - Black Friday sales, supply shortages, market booms
- **Mobile Optimized** - Play on any device, anywhere

### 📊 Learning Objectives
- Supply chain dynamics and interdependencies
- Inventory management and stockout prevention
- Cash flow planning and budgeting
- Strategic forecasting and planning
- Risk management and adaptation

---

## 🎲 How to Play

### Game Setup
- **4 Players** - Each takes a unique supply chain role
- **Starting Resources** - $1,000 cash + 20 units inventory
- **Win Condition** - Complete 8 turns with positive cash, zero demand, and no pending orders

### Each Turn (3 Simple Steps)

#### 1️⃣ Roll the Dice 🎲
- Click "Roll Dice" to see your customer demand
- Dice result + random factor = total units demanded

#### 2️⃣ Place Order 📦
- Choose how many units to order
- **Cost:** $10 per unit
- **Delivery:** Arrives in 2 turns (plan ahead!)
- Can skip if you have enough inventory

#### 3️⃣ Fulfill Demand ✅
- Sell inventory to meet customer demand
- **Revenue:** $20 per unit sold
- **Stockout Penalty:** Lose 10% of cash if you can't fulfill demand

### Special Events ⚡
Random events add excitement and challenge:
- 🛍️ **Black Friday** - Demand +50%
- 📉 **Supply Shortage** - Delivery delayed +1 turn
- 📈 **Market Boom** - Demand +40%
- 🐌 **Economic Slowdown** - Demand -20%

---

## 📚 Educational Value

### For Students (Grade 5+)
- Learn business fundamentals through play
- Understand cause and effect in supply chains
- Practice mental math and planning skills
- Experience real-world decision-making

### For Educators
- **Classroom Ready** - No installation, just open and play
- **Curriculum Aligned** - Business, economics, math concepts
- **Collaborative Learning** - 4-player cooperative/competitive gameplay
- **Discussion Starter** - Debriefing opportunities after each game

### For Business Learners
- Visualize supply chain complexity
- Experience the bullwhip effect
- Understand inventory vs. cash trade-offs
- Practice strategic forecasting

### Key Concepts Taught
✅ Supply chain structure and flow  
✅ Inventory management (just-in-time vs. safety stock)  
✅ Cash flow and working capital  
✅ Lead time and planning horizons  
✅ Demand variability and forecasting  
✅ Risk management and contingency planning  

---

## 🚀 Quick Start

### Play Instantly (No Installation)

1. **Download the game file:**
   ```bash
   git clone https://github.com/yourusername/tradepath.git
   cd tradepath
   ```

2. **Open in browser:**
   - Double-click `supply-chain-race-simple.html`
   - Or drag the file into your browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js
     npx serve
     ```

3. **Start playing!**
   - Navigate to `http://localhost:8000`
   - Game loads instantly - no dependencies needed

### Mobile Play (Android/iOS)

1. Transfer the `.html` file to your mobile device
2. Open with any browser (Chrome, Safari, Firefox)
3. Tap to play - fully touch-optimized!

---

## 🎯 Game Mechanics

### Core Economics
- **Starting Capital:** $1,000
- **Starting Inventory:** 20 units
- **Order Cost:** $10 per unit
- **Sales Revenue:** $20 per unit
- **Profit Margin:** $10 per unit (100%)
- **Delivery Lag:** 2 turns
- **Stockout Penalty:** 10% of current cash

### Winning Strategy Tips 💡
1. **Plan Ahead** - Orders take 2 turns to arrive
2. **Keep Safety Stock** - Avoid stockouts at all costs
3. **Watch Your Cash** - Don't over-order and run out of money
4. **Track Pending Orders** - Know what's coming
5. **Adapt to Events** - Adjust your strategy when events occur

### Advanced Concepts
- **Bullwhip Effect** - Small demand changes amplify upstream
- **Inventory Turnover** - Balance stock levels with sales
- **Working Capital** - Manage the cash-to-inventory cycle
- **Risk Mitigation** - Build buffers for uncertainty

---

## 👥 Player Roles (Detailed)

### 🏭 Manufacturer (Player 1 - Blue)
**Position:** Start of the supply chain  
**Challenge:** Produce enough to meet distributor demand  
**Key Learning:** Production planning, capacity management

### 🚚 Distributor (Player 2 - Green)
**Position:** Middle of the chain (logistics)  
**Challenge:** Balance orders from manufacturer vs. wholesaler needs  
**Key Learning:** Logistics coordination, buffer inventory

### 🏪 Wholesaler (Player 3 - Orange)
**Position:** Bulk buyer/seller  
**Challenge:** Buy large quantities, sell to multiple retailers  
**Key Learning:** Bulk purchasing economics, demand aggregation

### 🛒 Retailer (Player 4 - Red)
**Position:** End of the supply chain (closest to customer)  
**Challenge:** Directly face customer demand volatility  
**Key Learning:** Demand forecasting, customer service

---

## 🛠️ Technologies

This game is built with **zero dependencies** for maximum accessibility:

- **HTML5** - Semantic structure
- **CSS3** - Responsive design with gradients, animations
- **Vanilla JavaScript** - Pure JS, no frameworks
- **Mobile-First Design** - Touch-optimized controls
- **Offline-Ready** - Works without internet after download

### Browser Compatibility
✅ Chrome 90+  
✅ Firefox 88+  
✅ Safari 14+  
✅ Edge 90+  
✅ Mobile browsers (iOS Safari, Chrome Android)

---

## 📥 Installation

### Option 1: Direct Download
1. Download `supply-chain-race-simple.html`
2. Open in any modern browser
3. Start playing immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/tradepath.git
cd tradepath
open supply-chain-race-simple.html
```

### Option 3: Fork and Customize
```bash
# Fork the repository on GitHub
git clone https://github.com/YOUR_USERNAME/tradepath.git
cd tradepath

# Make your changes
# Commit and push
git add .
git commit -m "Your awesome changes"
git push origin main
```

---

## 📖 Documentation

### Game Files
```
tradepath/
├── supply-chain-race-simple.html    # Main game file (standalone)
├── game-instructions.docx           # Printable instructions
├── README.md                        # This file
└── LICENSE                          # MIT License
```

### For Educators
📄 **Lesson Plan Ideas:**
- Pre-game: Discuss real-world supply chains (smartphones, food, clothing)
- During: Observe player decisions and challenges
- Post-game: Debrief on what worked, what didn't, and why
- Extension: Research real companies' supply chain strategies

📄 **Assessment Opportunities:**
- Understanding of supply chain roles
- Decision-making under uncertainty
- Resource management skills
- Strategic thinking and planning

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Report Bugs 🐛
Found a bug? [Open an issue](https://github.com/yourusername/tradepath/issues) with:
- Description of the problem
- Steps to reproduce
- Expected vs. actual behavior
- Browser and device info

### Suggest Features 💡
Have ideas? [Open an issue](https://github.com/yourusername/tradepath/issues) with:
- Feature description
- Use case / benefit
- Any examples or mockups

### Submit Pull Requests 🔧
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly
5. Commit (`git commit -m 'Add amazing feature'`)
6. Push (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Development Guidelines
- Keep code simple and readable
- No external dependencies
- Mobile-first approach
- Comment complex logic
- Test on multiple browsers

---

## 🎓 Use Cases

### 🏫 Education
- **Business Classes** - Supply chain management, economics
- **Math Classes** - Applied arithmetic, planning, budgeting
- **STEM Programs** - Systems thinking, optimization
- **After-School Programs** - Fun educational activity

### 💼 Training
- **Corporate Training** - Onboarding for supply chain roles
- **Team Building** - Collaborative problem-solving
- **Workshops** - Interactive supply chain seminars
- **Case Studies** - Debrief on real scenarios

### 🏠 Personal Learning
- **Self-Study** - Understand business concepts
- **Family Game Night** - Educational entertainment
- **Skill Building** - Strategic thinking practice

---

## 🌟 Roadmap

### Planned Features
- [ ] Multiplayer online mode
- [ ] Difficulty levels (Easy, Medium, Hard)
- [ ] Custom scenarios and events
- [ ] Save/load game progress
- [ ] Analytics dashboard (post-game stats)
- [ ] Sound effects and music
- [ ] Achievement system
- [ ] Leaderboard
- [ ] AI opponent mode
- [ ] Multiple language support

### Community Requests
Vote for features in [Discussions](https://github.com/yourusername/tradepath/discussions)!

---

## 📊 Stats & Impact

Since launch:
- 🎮 **Games Played:** Track your impact!
- 👥 **Players:** Growing community
- 🏫 **Schools Using:** Educational reach
- 🌍 **Countries:** Global accessibility

*Share your story! Let us know how you're using TradePath.*

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What this means:
✅ Free to use  
✅ Free to modify  
✅ Free to distribute  
✅ Commercial use allowed  
✅ No warranty provided  

---

## 🙏 Acknowledgments

- Inspired by the classic **Beer Game** (MIT Sloan School of Management)
- Built for educators and learners worldwide
- Thanks to all contributors and players!

---

## 📞 Contact & Support

### Questions?
- 📧 Email: your.email@example.com
- 💬 [Discussions](https://github.com/yourusername/tradepath/discussions)
- 🐛 [Issue Tracker](https://github.com/yourusername/tradepath/issues)

### Share Your Experience
- ⭐ Star this repo if you find it useful!
- 🐦 Tweet about it: `#TradePath #SupplyChain #EdTech`
- 📝 Write a review or blog post
- 🎓 Share with your students or colleagues

---

## 🎉 Ready to Play?

**[📥 Download the game](https://github.com/yourusername/tradepath/releases)** and start your supply chain journey today!

**[📖 Read the instructions](game-instructions.docx)** - Perfect for first-time players

**[🎮 Play Demo](https://yourusername.github.io/tradepath)** - Try it online now!

---

<div align="center">

**Built with ❤️ for learners everywhere**

[⬆ Back to Top](#-tradepath)

</div>
