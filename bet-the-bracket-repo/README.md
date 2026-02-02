# Bet the Bracket - Interactive Pricing Model

A comprehensive financial modeling tool for March Madness bracket prediction markets. Built to demonstrate pricing structures, capital requirements, and user economics for market maker partnerships.

## Overview

This tool models "Bet the Bracket" - a March Madness product where users fill out a traditional bracket, but each selection is an independent prediction market contract. All 63 picks are bundled into a single transaction with transparent pricing.

## Features

### 🏀 Interactive Bracket
- Full 64-team NCAA tournament bracket
- Click-to-select interface with real-time pricing
- Teams auto-advance through rounds
- Live calculations of max payout and ROI

### 📊 Three Pricing Models
1. **Flat Stakes**: Equal amount per pick (simple, predictable)
2. **Progressive +50%**: Stakes increase 1.5x each round (balanced upside)
3. **Progressive 2x**: Stakes double each round (maximum excitement)

### ⚙️ Configurable Parameters
- **Entry Amount**: Variable from $15 to $100+ (default $63)
- **Max Odds**: 30-1, 50-1, or 100-1 caps
- **Auto-Fill Scenarios**: 
  - Chalk (all favorites)
  - Upset Special (#3 seed wins)
  - Chaos (all underdogs, #16 seed wins)

### 📈 Analytics Tabs
1. **Probability Table**: Historical seed performance data
2. **Capital Calculator**: Market maker exposure modeling with explicit netting scenarios

## How It Works

### Pricing Structure
Each selection in the bracket is a $X contract (based on entry amount / 63) on a binary outcome:
- Round 1: Team A beats Team B
- Later rounds: Team X advances to Round Y

Probabilities are based on historical March Madness seed performance data.

### Progressive Stakes
Instead of flat pricing, stakes can increase by round:
- **+50% model**: R1 ($0.60) → Championship ($4.55) with $63 entry
- **2x model**: R1 ($0.33) → Championship ($10.50) with $63 entry

This puts more weight on higher-ROI picks (championship longshots).

## Use Cases

### For Product Teams
- Demonstrate user economics across different configurations
- Compare pricing models side-by-side
- Visualize how entry amounts affect accessibility

### For Market Makers
- Model capital requirements under different assumptions
- Understand correlation benefits and netting opportunities
- See worst-case scenarios with explicit assumptions

### For Stakeholders
- Interactive demo of full bracket experience
- Clear visualization of risk/reward trade-offs
- Data-driven decision making on product parameters

## Technical Details

- **Pure HTML/CSS/JavaScript** - no dependencies
- **Self-contained** - single file deployment
- **Responsive design** - works on desktop and mobile
- **Real-time calculations** - instant updates on any change

## Getting Started

1. Open `bracket-full-interactive.html` in any modern browser
2. Start with default settings (Flat Stakes, 50-1 max odds, $63 entry)
3. Click "Chalk" to see a typical chalk bracket
4. Switch to "Progressive 2x" and click "Upset Special" to see maximum upside
5. Toggle between tabs to explore different aspects

## Key Insights

### Capital Requirements
- **Naive calculation** (sum of all max payouts) significantly overstates actual need
- **Correlation benefits** from mutual exclusivity reduce requirements by 40-70%
- **Pick concentration** is key driver of actual capital needs
- Requires Monte Carlo simulation with realistic bracket distributions

### Pricing Model Trade-offs
- Flat stakes: Lower capital requirement, simpler UX
- Progressive models: Higher upside on upsets, increased capital needs
- 2x model can create $1,000+ max payouts on realistic upset brackets

## Data Sources

Seed advancement probabilities based on historical March Madness tournament data (1985-present):
- Seed performance by round
- All probabilities capped at minimum based on max odds setting
- Historical data ensures realistic modeling

## Project Context

Built for market maker partnership discussions (particularly SIG Trading Partners) to demonstrate:
1. Product feasibility with real pricing
2. Capital requirement modeling
3. User experience across different configurations

## License

Internal use only - Proprietary

## Contact

Built for Bet the Bracket product development
