
## Aim: 
To design, evaluate, and optimize a role-based, constraint-driven AI prompt that simulates an enterprise retail recommendation engine

## Requirement ai tool:

ChatGPT,Google Gemini.

## Basic Prompt:

Recommend products for a 21-year-old student who previously bought laptop accessories and is browsing programming books, with a total budget of ₹2,000. 
For each product, include:
- Product name
- Estimated price
- Reason for recommendation
- Personalization logic
Do not recommend anything unrelated to programming, tech, or laptop accessories.

## Refined Prompt:

Act as an enterprise AI retail recommendation engine for an e-commerce platform.

Customer Profile:
- Age: 21
- Role: Student
- Past Purchases: Laptop accessories
- Browsing History: Programming books
- Budget: ₹2,000 (Hard limit for the total combined cost of all recommended items)

Task:
Generate a personalized recommendation bundle of 2 to 3 complementary physical products that directly match this student's profile.

Required Deliverables:
For each recommended product, provide:
1. Product Name
2. Estimated Price (in ₹)
3. Reason for Recommendation (practical value and utility for a 21-year-old student)
4. Personalization Logic (explicitly explain how this product connects to their past purchases of laptop accessories and their browsing history of programming books)

At the end, calculate:
- Total Bundle Price (must be ≤ ₹2,000)
- Remaining Balance

- Strictly do not recommend items outside of programming literature, developer tools, or laptop desk accessories.
- Strictly exclude fashion, gaming, general stationery, home decor, and digital subscriptions/courses.
- The cumulative total of all items must not exceed ₹2,000.
## Output
1. Product Name: Automate the Boring Stuff with Python (Paperback)
Estimated Price: ₹750

Reason for Recommendation: Perfect for a 21-year-old student entering software development. It teaches practical, real-world scripting that saves time on academic tasks, data handling, and coursework without bogging the reader down in dry academic theory.

Personalization Logic: Directly converts their active browsing history in programming books into an actionable, industry-standard learning resource tailored to their academic stage.

2. Product Name: Portronics Foldable Aluminum Laptop Riser
Estimated Price: ₹649

Reason for Recommendation: Promotes healthy ergonomic posture by raising the screen to eye level, reducing neck fatigue and thermal throttling during long coding and reading sessions in a dorm or library.

Personalization Logic: Directly reinforces their prior purchasing pattern of laptop accessories, serving as a functional companion piece to their portable computing setup.

3. Product Name: Extended Desk & Keyboard Mat (800 mm × 300 mm)
Estimated Price: ₹399

Reason for Recommendation: Provides a clean, dedicated surface that organizes their laptop, external mouse, and open textbooks while dampening typing vibrations in shared student study spaces.

Personalization Logic: Bridges their accessory history with their learning activities, creating a focused, slip-free workstation for coding alongside physical programming references.

Financial Summary:
Total Bundle Price: ₹1,798
Remaining Balance: ₹202 (well within the ₹2,000 hard budget ceiling)
## Result
The AI successfully generated three personalized products (*Automate the Boring Stuff with Python*, an aluminum laptop riser, and a desk mat) with clear reasons and personalization logic tied to the student's tech and reading history. The bundle strictly adhered to all constraints, totaling ₹1,798 with a ₹202 buffer under the ₹2,000 budget cap while excluding unrelated items.

