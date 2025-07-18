# 🚀 Fortuna's Deal

**Welcome to Gerald Badum's bar on Prospect Station - The ultimate Discord bot for The Cycle: Frontier weapon collecting and PvP dueling!**

Step into the gritty atmosphere of Fortuna III where prospectors gather to trade weapons, settle scores, and earn K-Marks in the shadow of the Cycle. With authentic TCF immersion and Gerald Badum's gruff wisdom guiding every interaction.

---

## 🎮 **What Makes This Special?**

### **🍺 Authentic Gerald Badum Experience**
- **Gerald Badum's voice** throughout all interactions with 50+ authentic TCF voice lines
- **Fortuna's Deal atmosphere** - feel like you're actually visiting Badum's bar on Prospect Station
- **TCF terminology integration** featuring TEF radiation, Cycle windows, dropships, and corps
- **Immersive character responses** that reference prospecting history and station life

### **🔫 Authentic TCF Weapon Arsenal**
- **27 real weapons** from The Cycle: Frontier with accurate stats and official icons
- **Faction-based gear** featuring Co-TEC, Osiris, ICA, and Korolev weapons
- **Rarity-based progression** from Common starter weapons to Legendary Special weapons
- **Beautiful weapon cards** with authentic weapon icons and detailed specifications

### **⚔️ Strategic Combat System**
- **TTK-based dueling** with real The Cycle: Frontier weapon performance data
- **Armor-first selection** - choose protection, then weapon for strategic depth
- **Range & accuracy mechanics** - close/medium/long range affects weapon effectiveness
- **Armor penetration system** - different armor tiers provide varying protection levels
- **Winner takes all** - pure skill + strategy with authentic prospector stakes

### **💰 Active Prospector Economy**
- **Earn K-Marks** through Discord activity (chatting, voice channels, reactions)
- **Collection crate system** with salvage stories from dropships caught in the Cycle
- **Daily/weekly bonuses** with Badum's station favors and house benefits
- **No cooldowns** - stay active like a real prospector, keep earning

---

## 📊 **Latest Updates (V2 - TTK Combat System & Armor Integration)**

### **⚔️ Revolutionary TTK-Based Combat System**
- **Real TCF weapon data** - combat system uses actual TTK values from The Cycle: Frontier weapon calculators
- **12 combat scenarios** - range (25m/50m/100m), accuracy (75%/100%), and weakspot (0%/25%) combinations
- **Data-driven balance** - 48 CSV report files with authentic weapon performance statistics
- **Engagement conditions** - dynamic range categories (close 30%, medium 50%, long 20%) affect weapon effectiveness
- **Accuracy scenarios** - poor/average/good/expert accuracy affects TTK calculations significantly

### **🛡️ Complete Armor System**
- **7 armor tiers** - No Armor (0) through Legendary (33 protection) with real damage reduction
- **Armor crates** - free armor every 4 hours with weighted drops (Common 40% → Legendary 2%)
- **Pre-duel armor selection** - strategic armor choice before weapon selection in duels
- **Armor consumption** - single-use armor system adds strategic resource management
- **Individual armor combat** - challenger and defender can use different armor tiers

### **🎨 Premium Visual Experience**
- **Custom PNG armor icons** - dedicated armor tier images for all 6 armor levels
- **Crate opening visuals** - `Armor_Crate.png` and `Weapon_Crate.png` for immersive experiences
- **Enhanced weapon crates** - weapon crate image with weapon thumbnail for perfect identification
- **Professional polish** - high-quality artwork matching TCF aesthetic throughout

### **🍺 Gerald Badum Character Integration**
- **50+ authentic voice lines** from The Cycle: Frontier
- **Immersive welcome messages** for new prospectors joining the establishment
- **Badum's commentary** on duel results, crate openings, and daily operations
- **Authentic error handling** with characteristic prospector guidance

### **🎯 Data-Driven Combat Balance**
- **Real TCF TTK values** - weapon effectiveness based on actual game performance data
- **Minimal type advantages** (1.05x) - skill and weapon choice matter more than rock-paper-scissors
- **Burst fire mechanics** - Gorgon (12-round), Phasic Lancer/Scarab (3-round) burst patterns
- **Armor penetration impact** - low-penetration weapons struggle against high-tier armor

### **🎨 Visual & Atmosphere Enhancements**
- **Weapon icons** on every card and display with authentic TCF assets
- **K-Marks currency icon** for better visual identity
- **Badum's bar atmosphere** in all command responses and interactions
- **TCF-themed messaging** with references to Cycle windows, Corps, and station life

---

## 🏗️ **Technical Features & Deployment**

### **🏰 Server Independence Architecture**
- **Per-server databases** - each Discord server maintains completely isolated data
- **Composite key system** - (user_id, guild_id) ensures zero cross-contamination
- **Automatic migration** - seamless upgrade from global to per-server system
- **Orphaned data cleanup** - automated maintenance removes legacy records

### **🐳 Docker Deployment Options**
- **Local development** - `docker-compose.yml` for testing and development
- **GitHub deployment** - `docker-compose.github.yml` for production from repository
- **Automated setup** - `setup-docker.sh` script handles entire deployment process
- **Environment configuration** - flexible database and bot token management

### **🔐 Security Model**
- **Discord native permissions** - leverages built-in administrator/manage_guild roles
- **Context-aware operations** - all commands automatically use correct server context
- **Input validation** - prevents server ID manipulation and unauthorized access
- **Error isolation** - failures in one server don't affect others

---

## 🎲 **How to Survive on Fortuna III**

### **💸 Earn K-Marks Like a Real Prospector**
- Chat in your server (2-4 K-Marks per message)
- Join voice channels (8 K-Marks per 10 minutes)
- React to messages (1 K-Mark per reaction)
- Claim daily bonuses (100 K-Marks) with Badum's favor
- Weekly bonuses (500 K-Marks) from the house fund

### **📦 Salvage Weapons & Armor from Collection Crates**
- Use `/weapon-crate` to crack open weapon crates (325 K-Marks)
- Use `/armor-crate` to claim free armor every 4 hours
- Hear Badum's stories about dropships lost to the Cycle
- Build your arsenal with weapons from all Corps factions
- Collect rare and legendary weapons for maximum firepower

### **⚔️ Challenge Other Prospectors**
- Use `/duel @player` to start a fight in Badum's bar
- Select armor first, then weapon for strategic depth
- Real TTK combat with range and accuracy factors
- Winner takes the loser's weapon - just like the old prospector days
- **Durability system**: Every weapon/armor degrades with each duel
- **Weapon destruction**: When durability hits 0, winner gets K-Marks compensation instead
- Badum provides commentary on your victory or defeat

### **📈 Track Your Prospector Progress**
- Check your K-Marks with `/k-marks`
- View your weapon collection with `/inventory`
- Check your armor collection with `/armor`
- Monitor your combat record with `/duel-stats`
- Accept challenges with `/accept` (armor & weapon selection) or `/decline`

---

## 🏆 **Weapon Tiers & Cycle Salvage Rates**

| **Rarity** | **Drop Rate** | **Examples** | **Power Level** |
|------------|---------------|--------------|-----------------|
| 🔘 **Common** | 45% | K-28, AR-55, B9 Trenchgun | Starter gear from failed prospectors |
| 🟢 **Uncommon** | 30% | Scarab, Manticore, Bulldog | Solid upgrades from station traders |
| 🔵 **Rare** | 15% | Phasic Lancer, ICA Guarantee | Strong weapons from Corp supply drops |
| 🟣 **Epic** | 7% | Advocate, Shattergun, Gorgon | Elite gear from veteran prospectors |
| 🔴 **Exotic** | 2.5% | KOR-47, Voltaic Brute | Top-tier weapons from Corp research |
| 🟡 **Legendary** | 0.5% | KARMA-1, KOMRAD, Zeus Beam | Ultimate weapons lost to the Cycle |

---

## 🔧 **Durability System - Weapons Degrade Over Time**

### **Durability Mechanics**
*"Nothing lasts forever on Fortuna III, Prospector. Even the best gear wears down."*

- **Variable durability** assigned when weapons/armor are obtained
- **Durability ranges by rarity**: Common (7-10 uses) → Legendary (2-3 uses)
- **Degradation on use**: Every duel reduces durability by 1 for both participants
- **Weapon destruction**: When durability hits 0, item is destroyed permanently

### **Scrap Compensation System**
When a weapon would be destroyed in a duel, the winner receives K-Marks instead:
- **Common**: 5 K-Marks | **Uncommon**: 10 K-Marks | **Rare**: 20 K-Marks
- **Epic**: 40 K-Marks | **Exotic**: 80 K-Marks | **Legendary**: 160 K-Marks

### **Strategic Considerations**
- **Durability lottery**: Even common weapons can roll high durability (10 uses!)
- **Risk management**: Duel with low-durability weapons at your own risk
- **Natural economy**: Prevents inventory oversaturation while maintaining rewards
- **Visible in inventory**: Check `/inventory` and `/armor` to see current durability

---

## ⚔️ **Combat Strategy Guide - Badum's Wisdom**

### **Class Effectiveness Cycle**
*"When it comes to weapons, you either know what you're doing or you don't make it back."*
```
SMG > Shotgun > AR > DMR > Sniper > Charge Rifle > LMG > Heavy Weapon > Pistol > SMG
```

### **Prospector Pro Tips**
- **Special weapons** (Legendary) have no type advantage - pure destructive power
- **15% type bonus** can swing close fights in your favor
- **RNG factor** means upsets are always possible - skill matters
- **Choose wisely** - you lose your weapon if you lose the duel!
- **One duel at a time** - Badum enforces house rules strictly

---

## 🚀 **Future Development - Extended Station Operations**

### **📦 Enhanced Collection & Trading** *(In Development)*
- **Multiple crate types** with different costs and faction loot pools
- **Weapon trading** between server members through Badum's network
- **Corp reputation** system with exclusive faction rewards

### **🏆 Competitive Prospector Features** *(Planned)*
- **Tournament brackets** for organized station competitions
- **Achievement system** with unlockable prospector badges
- **Station leaderboards** across multiple categories
- **Weapon modification** system for customization

### **🎮 Social Station Features** *(Future)*
- **Corp/faction alignment** with team benefits and rivalries
- **Weapon showcase** galleries in your prospector profile
- **Combat replay** system with detailed duel breakdowns

---

## 🎯 **Perfect For Prospectors**

- **TCF player communities** wanting to extend the Fortuna III experience
- **Gaming Discord servers** looking for authentic immersive bot activities
- **Competitive groups** who enjoy strategic PvP with real stakes
- **Collectors** who love progression and hunting rare Corp weapons

---

## ⚡ **Quick Start - Welcome to the Station**

1. **Join Fortuna's Deal** - Badum will greet you personally with server-specific welcome
2. **Check your K-Marks** with `/k-marks` - basic station courtesy gives you starter currency
3. **Buy your first crate** with `/weapon-crate` - hear Badum's salvage stories (250 K-Marks)
4. **Challenge someone** with `/duel @player` then select your weapon - settle it the old way
5. **Build your reputation** on your server and survive in the competitive prospector scene!

---

## 🔗 **Command Reference - Station Operations**

### **🎮 Player Commands** *(Per-Server Data)*
| Command | Description | Badum's Notes |
|---------|-------------|---------------|
| `/k-marks` | Check your K-Marks balance | "Know what you're worth, Prospector" |
| `/inventory [@user]` | View weapon collection | "Check your gear, Prospector" |
| `/armor [@user]` | View armor collection | "Protection's worth its weight on Fortuna" |
| `/weapon-crate` | Open a weapon crate (250 K-Marks) | "Collection crates, damn useful" |
| `/armor-crate` | Claim free armor (4hr cooldown) | "Corps gear, lost to the Cycle" |
| `/daily` | Claim daily bonus (100 K-Marks) | "Station's been good to you today" |
| `/weekly` | Claim weekly bonus (500 K-Marks) | "Consider this a favor from the house" |
| `/weapon-info <name>` | See detailed weapon stats | "Know your gear before you use it" |
| `/duel @user` | Challenge to a duel | "Settle things the old way" |
| `/accept` | Accept a duel challenge | "Time to prove yourself" |
| `/decline` | Decline a duel challenge | "Smart choice, sometimes" |
| `/duel-stats [@user]` | View win/loss record | "Reputation matters on the station" |

### **🛡️ Admin Commands** *(Requires Discord Admin Permissions)*
| Command | Description | Admin Notes |
|---------|-------------|-------------|
| `/admin-give-kmarks @user <amount>` | Grant K-Marks to a user | Server-specific currency management |
| `/admin-give-weapon @user` | Give weapon to user (dropdown) | Add weapons to player inventory |
| `/admin-reset-user @user` | Reset user's data | Removes all server data for user |
| `/admin-stats` | View server statistics | K-Marks, users, weapons summary |
| `/admin-list-weapons` | Show all available weapons | Complete weapon database reference |

---

**Ready to make your mark on Fortuna III? Step into Badum's establishment and start building your legend among the prospectors!**

*"You've proven you're capable enough down there, and I need capable people."* - Gerald Badum

*Featuring authentic weapon data and voice lines from The Cycle: Frontier* 
