# Christian Akabueze

Robotics engineer in London, interested in bringing AI into the physical world. I trained as a mechanical engineer and did my MSc in Human and Biological Robotics at Imperial College London (2026), working across control, machine learning, and hardware. I build controllers for real robots and test them on hardware.

<img src="https://github.com/fechachris4/msc_project/raw/main/media/rig.jpg" width="480" alt="A participant walking on a treadmill wearing two robot arms on the torso, with Vicon cameras around the rig">

## Projects

### [Wearable robot arms that hold still while you walk](https://github.com/fechachris4/msc_project) (MSc thesis)

Two Kinova Gen3 arms worn on the torso keep their end-effectors fixed in the room while the wearer walks. In treadmill trials with seven participants, the arms removed 56-71% of the mount motion, depending on walking speed. A MuJoCo study traces most of what is left to a late estimate of the mount's velocity. Python simulation, C++20 port, and unit tests in CI.

### [C++ control stack for the same rig](https://github.com/fechachris4/HumanSL_MAIN/tree/master/Christian_control)

A 500 Hz world-frame Cartesian controller on the Kinova Kortex API, with the mount velocity estimated from Vicon, and separate planning, runtime, and tracking layers. The planning, control, and panel tests run without the robot.

### [Reinforcement learning vs a tuned PID for anaesthesia dosing](https://github.com/fechachris4/Reinforcement_learning_for_Anesthesia)

During surgery, the propofol dose has to keep a patient at the right depth of anaesthesia. I tested Soft Actor-Critic against a well-tuned PID controller on 30 simulated patients it had never seen, with a noisy monitor signal delayed by 20 s. SAC learning corrections on top of the PID tied with it (85.3% vs 84.9% of time in the target range). Along the way the agent exploited a loophole in the induction phase, which I found and closed before the final results. Tests in CI reproduce the PID results exactly.

## Before robotics

Mechanical engineer in building services, including a data-centre project, where I wrote an AutoCAD automation tool that cut project setup from 2 days to minutes. Before that, technical co-founder of a community events platform that grew to 3,500 members in three months.

## Contact

- Email: fecha412@gmail.com
- [LinkedIn profile](https://www.linkedin.com/in/christian-akabueze-6621651b8/)
- [Personal website](https://christianakabueze.com)
