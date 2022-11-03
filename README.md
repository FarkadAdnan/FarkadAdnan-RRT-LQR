# LQR-RRT*
LQR heuristic as an extension to sample based motion planning algorithms, such as RRT or  RRT*, can be a relatively low-cost distance metric and find optimal plans in domains with complex or underactuated dynamics. Below, is the phase plot propagation of the simple pendulum:

![demo](http://i58.photobucket.com/albums/g257/MahanFathi/pendrrt%202_zpsfekajg7i.gif)

#  RRT∗
- يعد الاستكشاف السريع للأشجار العشوائية (RRTs) نهجًا عشوائيًا قياسيًا لتخطيط الحركة. RRT ∗ الموضح في الخوارزمية 1 ، هو أحد أشكال هذه الخوارزمية التي لها خاصية الأمثلية المقاربة ، أي التقارب شبه المؤكد مع الحل الأمثل.

- Rapidly exploring random trees (RRTs) are a standard randomized approach to motion planning . RRT ∗ shown in Algorithm 1, is a variant of this algorithm that has the asymptotic optimality property, i.e., almost-sure convergence to an optimal solution.
![Capture](https://user-images.githubusercontent.com/35774039/199845669-25497704-da2b-4b4d-b80b-fc63ec2e2b7f.PNG)
![Capture1](https://user-images.githubusercontent.com/35774039/199845679-77da8b55-6ce2-491a-bbd5-99b8b0ae51e5.PNG)
![Capture11](https://user-images.githubusercontent.com/35774039/199845685-f7103966-ef19-4e98-9b3f-63217ca15355.PNG)


# LQR
![Capture](https://user-images.githubusercontent.com/35774039/199845807-04519b99-203b-4e6e-80f6-24a1a939075e.PNG)
- Linear quadratic regulation (LQR) is an approach to computing optimal control policies for linear systems with Gaussian process noise. In general, the problem of finding optimal control policies for arbitrary stochastic systems is has polynomial computational complexity in the number of value function parameters. However, when the system dynamics are linear, it is possible to solve for the optimal value function efficiently in closed form. Furthermore, it is possible to apply this approach to non-linear systems by linearizing the nonlinear process dynamics about an operating point.

![Capture](https://user-images.githubusercontent.com/35774039/199846314-568b3206-87f7-411c-bea7-7bb025bd99fa.PNG)
![SSSS](https://user-images.githubusercontent.com/35774039/199846318-989d1c09-a612-431f-8442-2e4f055d53e7.PNG)

![Capture1](https://user-images.githubusercontent.com/35774039/199846346-b403ff95-9586-4f2a-8bca-40bde8a1c6fc.PNG)
![SSS](https://user-images.githubusercontent.com/35774039/199846350-56a7a165-a8e9-4f86-8722-b57cf6f65768.PNG)

![Capture11](https://user-images.githubusercontent.com/35774039/199846428-c0aaa990-b0ef-4b2a-916a-18f76d8f0999.PNG)
![SSS](https://user-images.githubusercontent.com/35774039/199846432-dc69cce0-560d-4d39-9cb6-bbd903d98423.PNG)

# REFERENCES
- [1] S. Karaman and E. Frazzoli, “Sampling-based algorithms for optimal motion planning,” International Journal of Robotics Research (to appear), June 2011. 
- [2] J. T. Schwartz and M. Sharir, “On the ‘piano movers’ problem: II. General techniques for computing topological properties of real algebraic manifolds,” Advances in Applied Mathematics, vol. 4, pp. 298–351, 1983. 
- [3] S. Lavalle, Planning Algorithms. Cambridge University Press, 2006.
- [4] S. M. LaValle and J. J. Kuffner, “Randomized kinodynamic planning,” International Journal of Robotics Research, vol. 20, no. 5, pp. 378– 400, May 2001. 
- [5] L. Kavraki, P. Svestka, J. Latombe, and M. Overmars, “Probabilistic roadmaps for path planning in high-dimensional configuration spaces,” IEEE Transactions on Robotics and Automation, vol. 12, no. 4, pp. 566–580, 1996.
- [6] S. M. Lavalle, “From dynamic programming to RRTs: Algorithmic design of feasible trajectories,” in Control Problems in Robotics. Springer-Verlag, 2002. 
- [7] P. Cheng and S. M. Lavalle, “Reducing metric sensitivity in randomized trajectory design,” in In IEEE International Conference on Intelligent Robots and Systems, 2001, pp. 43–48.
- [8] E. Glassman and R. Tedrake, “A quadratic regulator-based heuristic for rapidly exploring state space,” in Proceedings of the IEEE International Conference on Robotics and Automation, May 2010. 
- [9] S. Karaman, M. Walter, A. Perez, E. Frazzoli, and S. Teller, “Anytime motion planning using the RRT*,” in IEEE International Conference on Robotics and Automation, 2011.
