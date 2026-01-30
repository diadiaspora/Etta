# **Web & Mobile App Design Workflow (Without UX Research)**

---

## **Phase 1 — Prep & Planning (10–15 min)**

Even without formal research, you need clarity.

1. **Define the goal / problem**

   * One sentence: *“This app lets users track their fitness progress quickly and easily.”*
2. **Identify the primary user flows**

   * Example: `Sign up → Dashboard → Log Activity → Review Progress`
3. **Set constraints**

   * Platforms (web, iOS, Android)
   * Brand colors / typography (if any)
     
   * Time or page limits
   * Time Limits
        Example:

            Wireframes: 30–45 minutes

            Full UI screens: 1–2 hours

        Purpose:

            Forces quick decisions → trains speed + efficiency

            Prevents “design paralysis” (tweaking forever)

            Helps simulate real-world constraints recruiters expect

💡 Optional: Sketch a quick flow on paper or Figma “00 – Flow” page.

4. __Sketch rough sitemap on paper__

    * Lists screens / flows / navigation relationships

---


## **Phase 2 — Sitemap Creation (5–10 min)**
___

1. Create a **“00 – Flow” page** in Figma

    __What “00 – Flow” Means__

    * **“00”** → the page order

      * Prefixing with numbers forces Figma to display pages in the order you want
      * “00” means it comes **first**, before wireframes, UI screens, or components
    * **“Flow”** → the content of that page

  * This page contains your **sitemap, user flows, or navigation diagrams**
  * Shows how screens connect and how users move through the app



### **Example Page Structure in Figma**

| Page Name       | Purpose                                       |
| --------------- | --------------------------------------------- |
| 00 – Flow       | Sitemap & flow diagrams                       |
| 01 – Wireframes | Grayscale frames of screens                   |
| 02 – UI         | High-fidelity screens with color & typography |
| 03 – Components | Buttons, cards, inputs, modals, variants      |
| 04 – Prototype  | Interactive prototype & links                 |

💡 Recruiters immediately see:

* You **plan before designing**
* You **think in systems**, not just individual screens
* Your file is **organized and professional**
* Makes files **easy to navigate** for teammates, PMs, or recruiters
* Signals **intentional workflow** without extra explanation
* Lets you separate **structure (Flow) from visuals (UI)** clearly


## **Phase 2 — Wireframing (20–40 min)**
___
Focus on **structure and hierarchy**, not visuals.

1. **Create frames for screens**

   * Mobile: 375x812 (iPhone X) or common sizes
   * Web: 1440px width
     
2. **Use grayscale only**
   * Keep focus on layout, content hierarchy, and interaction
   * Focus on hierarchy, spacing, layout
   * Avoid color and stylistic choices for now
     

3. **Include key elements**
   * Buttons, inputs, navigation, content blocks
     
4. **Add minimal annotations**
   * Optional: one-line notes for interactions

💡 Goal: anyone opening the file understands **what happens where** without color.

---

## **Phase 3 — Component Creation**

1. Identify **repeatable UI elements**

   * Buttons, cards, inputs, modals, navbars
2. Convert each to **Components**

   * Cmd/Ctrl + Alt + K
3. Add **variants** for states

   * Button: Default / Hover / Disabled
   * Card: Normal / Selected
4. Put components in a **Components page or section**

💡 Rule: If you use something more than twice, make it a component.

---

## **Phase 4 — Layout with Auto Layout**

1. Apply **Auto Layout** to:

   * Buttons, inputs, lists, cards
2. Nest Auto Layout where needed

   * E.g., Card contains vertical Auto Layout for header, body, footer
3. Set padding & spacing

   * Use consistent spacing (8px or 4px grid)
4. Hug contents vs Fill container

   * Buttons: Hug
   * Inputs: Fill
   * Cards: Fill

💡 Recruiters notice **responsive and adaptable layouts**.

---

## **Phase 5 — Visual Design / Styling**

1. **Add color only after layout is locked**

   * Primary / Secondary / Background / Text
2. **Typography**

   * Headings, body, captions
   * Use variables if possible
3. **Icons**

   * Use consistent icon set
4. **Spacing & hierarchy**

   * Fix any misalignments, padding inconsistencies

💡 Do a **“Zoomed out check”** — can you scan the UI in 5 seconds and understand hierarchy?

---

## **Phase 6 — Mobile vs Web Adaptation**

1. Start from your canonical screen
2. Adapt:

   * Navigation (bottom tabs for mobile, top for web)
   * Card width & layout
   * Responsiveness
3. Use **same components + Auto Layout** for consistency
4. Adjust touch targets

   * Mobile: 44–48px tap areas

💡 This keeps your system reusable across platforms.

---

## **Phase 7 — Prototype & Interaction**

1. Link key screens in **Prototype mode**
2. Add **main interactions only**

   * Navigation, buttons, toggles
3. Optional:

   * Overlay modals
   * Simple transitions (slide, fade)
4. Avoid over-animating — recruiters focus on structure, not motion polish.

---

## **Phase 8 — Final Polish**

1. Clean layers / frames

   * Rename anything like “Rectangle 23” → Button / Card / Header
2. Organize pages

   * 00 Flow / 01 Wireframes / 02 UI / 03 Components / 04 Prototype
3. Check consistency

   * Colors, spacing, typography
4. Optional notes for recruiter

   * Small note explaining your design decisions or constraints

---

## **Phase 9 — Export & Present**

1. Prepare **screenshots for portfolio**

   * Mobile + Web views
2. Export interactive prototype link

   * Shareable Figma link
3. Add short description

   * Purpose / Problem / Key Features / Platforms

💡 Keep the focus on **thinking and polish**, not research metrics.

---

### **Workflow Summary Table**

| Phase       | Key Actions                                     |
| ----------- | ----------------------------------------------- |
| Prep        | Goal, primary flow, constraints                 |
| Wireframe   | Grayscale, frames, hierarchy, notes             |
| Components  | Identify repeatables, variants, system page     |
| Auto Layout | Layout, spacing, nested frames                  |
| Visual      | Colors, typography, icons, hierarchy            |
| Mobile/Web  | Adaptation, navigation, touch targets           |
| Prototype   | Link screens, interactions, transitions         |
| Polish      | Clean layers, organize pages, check consistency |
| Present     | Screenshots, prototype link, brief write-up     |

---

💡 **Pro Tip for Speed + Quality**

* Design **canonical screens first**, then reuse
* Gray → Components → Auto Layout → Visuals
* Recruiters notice **intentional structure**, not tiny UI tweaks

---

If you want, I can also make a **visual step-by-step checklist specifically for Etta**, so every new project is done **fast, clean, and recruiter-ready**, for both mobile and web.

Do you want me to do that next?
