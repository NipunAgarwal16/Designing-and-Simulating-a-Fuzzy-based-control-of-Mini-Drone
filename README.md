# Designing and Simulating a Fuzzy based control of Minidrones/Satellite Altitude
This is a group project done during the course INSTR F343 (Industrial Instrumentation and Control) at the [Birla Institute of Technology and Science, Pilani](https://www.bits-pilani.ac.in/). Under the guidance of [Dr.Puneet Mishra](https://www.bits-pilani.ac.in/pilani/puneetmishra/Profile)

#### Team Members:
- **Nipun Agarwal** ([LinkedIn](https://www.linkedin.com/in/nipun-agarwal-16052000/) - [GitHub](https://github.com/NipunAgarwal16))
- **Udit Agrawal**
- **Deepesh Bansal**


## Motivation :
The geostationary satellite's location drifts owing to a range of factors pushing on it. In nature, these forces are additive. Because satellite communication relies heavily on line of sight, attitude (drift in position) must be managed. It is required to periodically ascertain the exact position of the satellite for this purpose. Once the satellite's location has been calculated, an appropriate correction can be performed using an appropriate attitude control system. A satellite's attitude can be controlled using a variety of approaches. Traditional approaches such as proportional, BangBang controllers, and so on are in use. These controllers have some drawbacks like mathematical complexity, inflexibility, slow response, etc. To overcome some of these drawbacks, fuzzy theory, and fuzzy controllers can give quicker control than standard ones.

The attitude control system determines and regulates a vehicle's orientation in space. An estimator state processes and filters the information given by attitude sensors. As a result, this signal is compared to a reference. The control algorithm will utilize the error between the estimated state and the reference to correctly activate the actuators in order to decrease or eliminate this error. 

Generally, a satellite contains three translation motions vertical, horizontal and transverse, and three rotational motions pitch, yaw, and roll by controlling the aileron, rudder, and elevator. To reduce the complexity of analysis, the satellite is usually assumed as a rigid body, and satellite motion consists of a small deviation from its equilibrium flight condition. In addition, the control system of a satellite can be divided into two groups, namely longitudinal and lateral control. In longitudinal control, the elevator controls pitch or the longitudinal motion of the satellite system. The pitch of the satellite is controlled by an elevator which is usually situated at the rear of the satellite running parallel to the wing that houses the ailerons. Pitch control is a longitudinal problem, and this work presents the design of an autopilot that controls the pitch of a satellite.

## Description :
This work presents an investigation into the development of pitch control schemes for the pitch angle of a satellite by using a fuzzy logic control. Performance of control strategy, PID, and fuzzy logic tuned PID controller with respect to the pitch angle of satellite longitudinal dynamics are investigated. Simulation is developed within MATLAB/SIMULINK for the evaluation of both control strategies.

## Discussion :
From the study performed on the altitude control of a satellite using conventional PID Controller, and Fuzzy Logic based PID controller, it can be seen that the Fuzzy Logic-based controller archives a better performance in terms of Peak Overshoot. Where the other parameters like the peak time, and rise time is similar as compared to the conventional PID controller. The only area where Fuzzy based controller’s performance is inferior to the conventional PID controller is settling time.

## Conclusion :
In this study, the conventional PID controller and Fuzzy based PID controller was developed to control the pitch angle of a satellite. Modeling is done on a satellite pitch angle control and a fuzzy controller is proposed successfully. The proposed control schemes have been implemented within a simulation environment in MATLAB /SIMULINK. Pitch control of a satellite is a system that requires a pitch controller to maintain the angle at its desired value. Based on the results, the system responses indicate the performance of the pitch control system using PID-fuzzy logic controller has been improved and satisfied compared to conventional PID controller.

## Future Work :
The possible future work on this topic could be to develop a fuzzy control system by using interval type 2 fuzzy logic controllers to tune the disturbance rejection of the pitch autopilot system in satellite. Also, the parameters of the fuzzy controller could be optimized using non-conventional optimization techniques like Particle Swarm Optimization (PSO), Genetic Algorithm (GA), Ant Colony Optimization (ACO), etc.

## References :

[1] Wu, S-F., et al. "Fuzzy logic based attitude control of the spacecraft X-38 along a nominal re-entry trajectory." Control Engineering Practice 9.7 (2001): 699-707.

[2] Valdez, Fevrier, Juan Carlos Vazquez, and Fernando Gaxiola. "Fuzzy dynamic parameter adaptation in ACO and PSO for designing fuzzy controllers: the cases of water level and temperature control." Advances in Fuzzy Systems 2018 (2018).

[3] Chu, Cheng-Wei, et al. "Design of self-heating test platform for sulfide corrosion and oxidation based on Fuzzy PID temperature control system." Measurement and Control 54.5-6 (2021): 1082-1096.

[4] Gomes, Willer, and Evandro Marconi Rocco. "Design of a fuzzy PID controller for application in satellite attitude control system." Proc. Workshop on Space Engineering and Technology. 2012.

[5] Hazza, Ali Ahmed Hani, M. Y. Mashor, and Mohammed Chessab Mahdi. "Fuzzy PD and Fuzzy $\text {PD}+\mathrm {I} $ Controllers Design for Attitude Control of Innovative Nano-Satellite." 2021 IEEE 17th International Colloquium on Signal Processing & Its Applications (CSPA). IEEE, 2021.

[6] Pokle, S. B., K. D. Kulat, and A. G. Keskar. "MATLAB Simulation of a Fuzzy Controller for Attitude Control of a Geostationary Satellite." IETE Journal of Education 45.4 (2004):203-209.

[7] Ali, Fawaz Elsiddig Ahmed. Fuzzy Control System Design for an Aircraft Attitude in Longitudinal Motion. Diss. Sudan University of Science and Technology, 2017.

[8] Zhao, Zhen-Yu, Masayoshi Tomizuka, and Satoru Isaka. "Fuzzy gain scheduling of PID controllers." IEEE transactions on systems, man, and cybernetics 23.5 (1993): 1392-1398.
