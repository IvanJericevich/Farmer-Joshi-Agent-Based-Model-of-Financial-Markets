# Adaptive Farmer-Joshi Agent Based Model of Financial Markets

## Authors: Ivan Jericevich & Murray McKechnie
## Supervisor: A/Prof. Tim Gebbie

### Background
The project explores the calibration and simulation of the Farmer and Joshi (2002) agent-based model of financial markets using the method of moments along with a genetic algorithm and a Nelder-Mead with threshold accepting algorithm. The is used model for understanding daily trading decisions made from closing auction to closing auction in equity markets, as it attempts to model financial market behaviour without the inclusion of agent adaptation. However, our attempt at calibrating the model has limited success in replicating important stylized facts observed in financial markets, similar to what has been found in other calibration experiments of the model. This leads us to extend the Farmer-Joshi model to include agent adaptation using a Brock-Hommes (1998) approach to strategy fitness based on trading strategy proﬁtability. The adaptive Farmer-Joshi model allows trading agents to switch between strategies, favouring strategies that have been more profitable over some period of time determined by a free-parameter determining the profit monitoring time-horizon.

### Usage
Thus this repository consists of two source files namely, the Adaptive Model and the Standard Model. Both source codes make use of South African ﬁnancial market data and demonstrate the simulation, testing and implementation of the models in a parallelised framework. Both source codes also present the results of two different model calibrations - Nelder-Mead Simplex with Threshold Accepting and a Genetic algorithm.
