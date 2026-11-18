# **The Instructor's Guide to EconLab's Market Mechanism**

**Application URL:** [https\://mikolajklimczak.github.io/econlab/market-mechanism/](https://mikolajklimczak.github.io/econlab/market-mechanism/)  
**Author:** Mikołaj Klimczak ([ORCID: 0000-0003-4761-3421](https://orcid.org/0000-0003-4761-3421))

# **1\. Purpose and modular workshop design**

EconLab's Market Mechanism is a browser-based interactive companion for introductory and intermediate microeconomics workshops covering demand, supply, and market equilibrium. Rather than imposing a rigid lesson script, the application is organized into independent modules that instructors can introduce at any point during a seminar or problem-solving session.

Instructors do not need to use every module in a single class. Depending on group size, student preparation, and available time, you can project the simulator for a five-minute visual check, assign one analytical task as a mid-workshop break, or run an entire ninety-minute session around the tool. Each component works on its own without requiring students to complete earlier sections first.

# **2\. Technical setup and interface overview**

The application runs directly in any modern web browser without installation, user accounts, or institutional logins. Students can open the page on laptops, tablets, or smartphones, while instructors can display it on a classroom projector or interactive whiteboard.

A language toggle in the top header switches the entire interface – including theoretical definitions, graph labels, algebraic steps, tasks, and quiz questions – between English and Polish. This makes the tool suitable for both Polish-language groups and international tracks taught in English, and allows bilingual students to verify terminology in both languages during class.

The workspace is arranged vertically into four self-contained blocks:

* **Market equilibrium theory and price shocks:** Concise definitions of equilibrium, excess demand, excess supply, non-price determinants of demand and supply, and the four canonical comparative statics outcomes under ceteris paribus.  
* **Interactive market simulator:** Controls for linear demand and supply equations, one-click shock presets, parallel curve shift sliders, a market price probe, a live coordinate graph, equilibrium summary cards, an adjustment pressure indicator, and a step-by-step algebraic solver.  
* **Market problem-solving tasks:** Structured applied scenarios requiring students to predict the direction of equilibrium changes and calculate new equilibrium prices and quantities.  
* **Self-assessment quiz:** A randomized twelve-question multiple-choice test covering equilibrium conditions, disequilibrium adjustment, and single or simultaneous shifts.

# **3\. Module-by-module classroom integration**

Each module fits different pedagogical goals and moments within a workshop. The table below summarizes when to deploy each part and how to use it with a group.

| Module | Best workshop timing | Primary teaching use | Instructor facilitation mode |
| :---- | :---- | :---- | :---- |
| Equilibrium theory reference | Opening recap (first 5–10 minutes) or mid-session terminology check | Standardizing notation (PE, QE, QD, QS) and reviewing non-price shifters before solving problems | Optional reference; skip if students already covered the theory in a recent lecture |
| Equation parameters and simulator | Core analytical block (minutes 15–50) | Visualizing how slope and intercept parameters shape curves and verifying algebraic solutions live | Projector demonstration led by the instructor, or individual student verification after pen-and-paper work |
| Price probe and adjustment panel | Early equilibrium intuition check (10–15 minutes) | Demonstrating why prices below or above PE generate shortages or surpluses that push the market back to balance | Interactive polling: ask students to calculate QD minus QS at a given price before moving the slider |
| Quick scenarios and curve shift sliders | Comparative statics practice (15–25 minutes) | Testing single and simultaneous shifts (ΔD and ΔS) and observing indeterminate outcomes | Small-group prediction exercise before revealing the new equilibrium E1 on screen |
| Problem-solving tasks | Applied workshop practice (20–30 minutes) | Bridging qualitative shift intuition with multi-step quantitative solutions in concrete markets | Individual or pair work on paper, followed by checking results in the task module |
| Randomized quiz | Closing diagnostic (final 10 minutes) or post-class homework | Checking individual retention and identifying topics that need review in the next meeting | Live rapid-fire class vote on 3–4 questions, or asynchronous self-check after class |

# **4\. Workshop timing and facilitation scenarios**

Because the modules are decoupled, you can adapt the tool to different workshop formats without restructuring your syllabus.

## **Scenario A: Traditional pen-and-paper workshop with visual verification (10–15 minutes of app use)**

In a classic problem-solving seminar where students spend most of the time working through algebraic exercises by hand, keep the app closed during the initial calculation phase. Once students finish solving a system of linear demand and supply equations on paper, open the simulator, enter the exact slope and intercept parameters from the worksheet, and project the step-by-step algebraic solution alongside the graph. This gives immediate visual confirmation and lets you discuss edge cases without redrawing axes on the board.

## **Scenario B: Interactive comparative statics workshop (45–60 minutes of app use)**

When the workshop focuses on market shocks and ceteris paribus reasoning, start with the baseline equilibrium E0 \= (50, 50\) already loaded in the simulator. Present a real-world news event – such as a rise in energy prices combined with a shift in consumer preferences – and ask groups to decide which curves move, in what direction, and whether PE or QE becomes ambiguous. Have students test their hypotheses using the Demand shift (ΔD) and Supply shift (ΔS) sliders, then use the Market problem-solving tasks to practice quantitative simultaneous shocks.

## **Scenario C: Flipped classroom or diagnostic review session (60–90 minutes of app use)**

If students review the theory section and complete the self-assessment quiz before arriving at the workshop, begin class by asking which quiz items or simulator scenarios caused confusion. Spend the first half of the session reproducing those exact parameter combinations on the projector, and dedicate the second half to having students design their own market shock scenarios for peers to solve.

# **5\. Common student misconceptions and live demonstrations**

Several recurring errors appear during microeconomics workshops on market equilibrium. Each can be addressed directly on screen in under three minutes.

## **Confusing a movement along a curve with a shift of the curve**

Students frequently assume that a change in the good's own price shifts the demand or supply curve. To address this, keep ΔD \= 0 and ΔS \= 0 in the simulator and move only the Market price (P) slider away from 50\. Point out on the graph that both curves remain stationary while the horizontal gap between QD and QS widens into a shortage or surplus.

## **Assuming simultaneous shifts always produce definite changes in both PE and QE**

When both demand and supply shift at the same time, students often predict definite directions for both price and quantity without checking magnitudes. Use Task 1 (the artisan bakery market starting at E0 \= (50, 50\) with ΔD \= \+30 and ΔS \= \-20) or adjust the ΔD and ΔS sliders manually. Show how two rightward shifts of equal or unequal size leave the change in PE uncertain until exact parameter values are specified.

## **Mixing up inverse and direct demand/supply equations**

In textbook exercises, students encounter both Q(P) and P(Q) forms and often misread slopes and intercepts. Direct their attention to the baseline equation box in the simulator, which explicitly writes QD \= b \- a·P and QS \= d \+ c·P, and compare how changing the slope slider alters the steepness of the plotted lines while changing the shift slider moves the intercept.

# **6\. Assessment and post-workshop follow-up**

The application supports both ungraded formative checks during class and structured follow-up work afterward:

* **In-class quick checks:** Project three questions from the randomized quiz in the final ten minutes of the seminar and ask students to commit to an answer before revealing feedback.  
* **Custom parameter homework:** Assign students a specific set of baseline parameters (a, b, c, d) and two sequential shocks, asking them to submit written derivations verified against the simulator's step-by-step algebraic output.  
* **Exam preparation:** Encourage students to revisit the problem-solving tasks and retake the randomized quiz independently before midterms, since the question order and item selection refresh on each attempt.

