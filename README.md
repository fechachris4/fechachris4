# Christian Akabueze

Robotics engineer. MSc Human and Biological Robotics, Imperial College London (2026).
I build controllers for real robots, test them on hardware, and report what didn't work.

### World-stable end-effectors on a walking wearer (MSc thesis)
Two Kinova Gen3 arms worn on the torso hold their end-effectors fixed in the room while the wearer walks.
Hardware trials on an instrumented treadmill with Vicon tracking, plus a MuJoCo study of what limits
the controller. Python simulation with a C++20 port, tests and CI. The repository and results are
private until the thesis is marked.

### SRL control stack (C++)
The C++ control stack I wrote for the same dual-arm rig: a 500 Hz world-frame Cartesian loop on
Kinova Kortex, mount velocity estimated from Vicon, and separate planning, runtime and tracking layers.
Private for now, alongside the thesis.

### [SAC vs PID for propofol anaesthesia](https://github.com/fechachris4/Reinforcement_learning_for_Anesthesia)
30 held-out simulated patients, noisy BIS delayed by 20 s. Residual SAC tied a tuned PID (85.3% vs 84.9% in range);
pure SAC lost (70%). It first exploited a loophole in induction, which I closed before these results.
Tests in CI reproduce the PID results exactly.

**Before robotics:** mechanical engineer on data-centre infrastructure; technical co-founder
of a community events platform (3,500 members in three months).

fecha412@gmail.com · [LinkedIn](https://www.linkedin.com/in/christian-akabueze-6621651b8/)
