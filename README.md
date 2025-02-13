# OPTIMIZATION-MODEL

*COMPANY*: CODTECH IT SOLUTIONS PVT.LTD

*NAME*: SOHAM MAJUMDER

*INTERN ID*: CT6WMIS

*DOMAIN*: DATA SCIENCE

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

So, I run a small manufacturing business that produces two products—let’s call them Product A and Product B. The problem? I have limited resources—raw materials and labor. Obviously, I want to maximize my profit, but I need to figure out how many units of each product I should produce without exceeding the available resources. Instead of guessing, I decided to use linear programming, which is a way to mathematically optimize decision-making. I used Python and the PuLP library to help automate this process and make my life easier.
First, I had to define a few things. Decision variables represent how many units of Product A and B I should produce. The objective function is what I’m trying to maximize—in this case, profit. This means I take the profit per unit of each product and multiply it by the number of units I decide to produce. Then come the constraints, which are basically the real-world limits—like how much material and labor I have available. These constraints ensure that my production plan is actually possible.
After setting all this up, I used PuLP to solve the optimization problem. The library does the heavy lifting and finds the best possible solution while staying within the constraints. But, of course, things didn’t work perfectly on the first try. I ran into an error because PuLP requires an external solver, and mine wasn’t working. To fix it, I installed and used GLPK, a different solver. Once I did that, the program ran successfully and gave me an optimal production plan—it told me exactly how many units of each product I should manufacture to maximize profit while staying within my resource limits.
But I didn’t stop there. I wanted more insights into my results. So, I did a sensitivity analysis, which basically tells me how changes in resources (like adding more raw materials or labor) would impact my profit. This is super useful for business decisions because it helps me understand what changes would make the biggest difference before actually making them. I also added a visualization using Matplotlib, which plots the feasible region and highlights the best production strategy. This made it way easier to see what’s going on instead of just looking at numbers.
At the end of the day, this whole project isn’t just about coding or math—it’s about solving real business problems in a smarter way. Businesses, whether big or small, always deal with limited resources, and making the best use of them is the key to success. Instead of relying on intuition, this optimization model helps make data-driven decisions—ensuring that every resource is used in the most efficient way possible. If I wanted to take this further, I could add more constraints, factor in costs, or even optimize production for multiple factories. There’s a lot more to explore, but for now, I’ve got a solid, automated system to maximize profits—and that’s a win in my book! 

#OUTPUT

![Image](https://github.com/user-attachments/assets/4a93fe19-7386-4244-9ffd-d118d577d251)

![Image](https://github.com/user-attachments/assets/1d69f9a9-dd3b-467e-843e-287330898fdf)
