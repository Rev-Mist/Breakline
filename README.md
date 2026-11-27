# BreakLine v2 — Interactive Canteen Counter & Token Prototype (P20)

**Project:** P20 — Fifteen Minutes, One Samosa (INT335 Design Thinking, LPU)  
**Team 13:** Krish Roy, Celina Raj, Priyanshi Yadav, Vanshika Yadav

## Overview
A zero-commission, interactive digital simulation of **BreakLine v2** designed for live classroom/viva demonstration and Vercel static deployment.

### Key Features Simulated
1. **Step 1 — Queue-Entry Menu & Live Wait-Time Board:** Real-time stock flip-tags (`AVAILABLE` / `SOLD OUT`) and prep-time estimates before students join a line.
2. **Step 2 — Color-Coded 3-Zone Counter Split:**
   - **Green Zone:** Express Grab-and-Go Rack (`<60s` checkout + eye-level Delay Snack-Swap rule).
   - **Yellow Lane 1:** Walk-In Billing with simulated **UPI Audio Soundbox** verification (`<2s`, eliminating manual phone screen checks).
   - **Blue Lane 2:** Dedicated Token Pickup Counter with timestamped `"Order Time / Ready By"` stubs.
3. **Live Visual Token Status Board & Vendor Console:** Interactive 3-inch high-contrast `PREPARING` vs. `READY FOR PICKUP` board with 1-tap vendor stock toggles.
4. **v1 vs. v2 Impact Metrics:** Side-by-side summary of CP6 silent testing results (`82.3s → 64.0s` order-to-pickup time, `25% → 0%` wrong-lane errors).

## Deploy to Vercel in 30 Seconds
1. **Drag & Drop (Fastest):** Go to [vercel.com/new](https://vercel.com/new), drag and drop the unzipped `breakline-v2` folder (or push this folder to a GitHub repository and import it into Vercel).
2. **CLI:** Run `npx vercel --prod` inside the extracted folder.
