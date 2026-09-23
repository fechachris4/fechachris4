# Christian Akabueze

Robotics engineer. MSc Human and Biological Robotics, Imperial College London (2026).
I build controllers for real robots, test them on hardware, and report what didn't work.

<img src="https://github.com/fechachris4/msc_project/raw/main/media/rig.jpg" width="420" alt="Two Kinova Gen3 arms worn on the torso, on an instrumented treadmill with Vicon cameras">

### [World-stable end-effectors on a walking wearer](https://github.com/fechachris4/msc_project)
Two Kinova Gen3 arms worn on the torso hold their end-effectors fixed in the room while the wearer walks.
Six participants on a treadmill: 72% of mount motion removed at 0.5 m/s, 56% at 1.5 m/s.
The limit was a mount-velocity signal arriving 60-70 ms late; in simulation that delay alone
erases feedforward's benefit (2.6 mm → 8.2 mm at 1.8 Hz). MuJoCo and Python, with a C++20 port
that reproduces the Python trace to 2.4e-12. 261 Python tests and the C++ parity check run in CI.

### [SRL hardware controller](https://github.com/fechachris4/HumanSL_MAIN/tree/master/Christian_control)
C++ control stack I wrote for the same dual-arm rig (separate from the controller that ran the trials): a 500 Hz world-frame Cartesian loop on Kinova Kortex,
mount velocity estimated from 100 Hz Vicon, and separate planning, runtime and tracking layers.

### [SAC vs PID for propofol anaesthesia](https://github.com/fechachris4/Reinforcement_learning_for_Anesthesia)
30 held-out simulated patients, noisy BIS delayed by 20 s. Residual SAC tied a tuned PID (85.3% vs 84.9% in range);
pure SAC lost (70%). It first exploited a loophole in induction, which I closed before these results.

**Before robotics:** mechanical engineer on data-centre infrastructure; technical co-founder
of a community events platform (3,500 members in three months).

fecha412@gmail.com · [LinkedIn](https://www.linkedin.com/in/christian-akabueze-6621651b8/)
