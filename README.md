# MMWD Manager - 16-bit Water District Simulation

A retro-style browser game where you manage the Marin Municipal Water District, balancing water supply, customer satisfaction, and budget constraints.

## About Marin Municipal Water District

The Marin Municipal Water District (MMWD) was established in 1912 as California's first municipal water district. It serves 191,000 customers across 147 square miles in southern and central Marin County.

### Real MMWD Facts Implemented in Game

- **7 Reservoirs**: Alpine, Bon Tempe, Kent, Lagunitas, Phoenix, Nicasio, and Soulajule
- **Total Capacity**: 79,566 acre-feet (enough for 3 years of water supply)
- **Active Reservoirs**: Kent, Alpine, Bon Tempe, and Nicasio provide regular supply
- **Reserve Reservoirs**: Phoenix, Lagunitas, and Soulajule held in reserve
- **Water Sources**: 75% from Mt. Tamalpais watershed rainfall, 25% supplemented by Russian River
- **Infrastructure**: 908 miles of pipes, 130 storage tanks, 97 pump stations
- **Seasonal Patterns**: Wet winters, dry summers typical of California climate

## How to Play

1. Open `index.html` in any modern web browser
2. Manage water supply across seasons
3. Balance your budget with conservation programs
4. Keep customer satisfaction above 10%
5. Don't go bankrupt!

## Game Features

### Water Management
- Monitor 7 historically accurate reservoirs with real capacities
- Track seasonal rainfall patterns (heavy winter rains, dry summers)
- Toggle Russian River supply ($800K/month for 2,500 AF)
- Click reservoirs to toggle between Active and Reserve status

### Conservation Programs
- **Turf Conversion** ($2M): Reduces demand by 350 AF/month
- **Public Campaign** ($500K): Reduces demand by 200 AF/month
- **Rebate Program** ($1.5M): Reduces demand by 300 AF/month

### Challenges
- Seasonal demand fluctuations (higher in summer)
- Random events (pipe breaks, heat waves, grants, conservation success)
- Drought conditions when supply drops below 30%
- Budget management (monthly revenue vs costs)
- Customer satisfaction tied to water availability

### Controls
- **PAUSE/PLAY**: Pause or resume simulation
- **FAST/NORMAL**: Toggle between normal and 3x speed
- **RUS RIVER ON/OFF**: Enable/disable Russian River supply
- **Conservation buttons**: Purchase programs to reduce water demand
- **Click reservoirs**: Toggle between Active and Reserve status

## Game Mechanics

### Monthly Cycle
1. Rainfall added to all reservoirs based on season
2. Russian River supply distributed to active reservoirs (if enabled)
3. Water demand calculated based on season and conservation
4. Water withdrawn from active reservoirs first, then reserves if needed
5. Customer satisfaction adjusted based on shortage
6. Monthly revenue collected ($4.2M) and costs deducted
7. Random events may occur (5% chance)

### Win Conditions
- Keep satisfaction above 10%
- Maintain budget above -$10M
- Survive as many years as possible

### Strategy Tips
- Activate Russian River supply during droughts
- Invest in conservation programs before summer
- Keep total water supply above 30% to avoid drought penalties
- Watch your budget - conservation saves money long-term
- Toggle reserve reservoirs to active during emergencies

## Technical Details

### 16-bit Aesthetic
- Pixel art graphics using HTML5 Canvas
- Retro color palette (16-32 colors)
- Press Start 2P font for authentic feel
- Pixelated rendering with crisp-edges
- 960x720 resolution optimized for retro look

### Technologies
- Pure HTML5, CSS3, and JavaScript
- No external dependencies
- Runs entirely in browser
- Canvas API for graphics
- RequestAnimationFrame for smooth 60 FPS

## Research & Design

This game was created with attention to three key aspects:

1. **Factual Accuracy**: All reservoir names, capacities, and operational details are based on actual MMWD data
2. **16-bit Sensibility**: Graphics, UI, and aesthetics follow classic 16-bit gaming conventions
3. **Engaging Gameplay**: Despite simulation accuracy, the game balances challenge and fun through:
   - Progressive difficulty (droughts, events)
   - Strategic decision-making (when to use reserves, conservation timing)
   - Resource management (water vs budget tradeoffs)
   - Real-time feedback (visual reservoir levels, satisfaction changes)

## Credits

Game design and implementation based on public information from:
- Marin Municipal Water District official resources
- California water management data
- Historical MMWD operations and infrastructure

Created as an educational simulation to raise awareness about water district management challenges.
