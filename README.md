# COA_GITHUB_REPO
Computer Organisation and Architecture <br />
Group-12 <br />
This repo is created to contain the implementation of *KAWS: Coordinate Kernel-Aware Warp Scheduling* (ENDSEM) and the implementation to print different warp states as described in *Equalizer: Dynamic Tuning of GPU Resources for Efficient Execution* (MIDSEM) <br />

# Results 
| **Benchmark** | **Scheduler** | **IPC** |        | 
|---------------|---------------|---------|--------|
|               |               | w WS    | w/o WS |
| BFS           | lrr           | 97.84   | 96.99  |
|               | gto           | 101.37  | 97.7   |            
|               | KAWS          | 102.39  | 96.1   |
| HS            | lrr           | 2157.7  | 2091.5 |           
|               | gto           | 2432.66 | 2113.9 |           
|               | KAWS          | 2441.84 | 2174.8 |           
| SC            | lrr           | 1283.86 | 1212   |           
|               | gto           | 1301.01 | 1219.76|           
|               | KAWS          | 1314.96 | 1231.91|           
| NW            | lrr           | 22.65   | 22.11  |           
|               | gto           | 22.64   | 22.25  |           
|               | KAWS          | 22.64   | 21.81  |           
| PF            | lrr           | 701.25  | 698.72 |           
|               | gto           | 728.78  | 716.78 |           
|               | KAWS          | 739.32  | 722.63 |           
| NN            | lrr           | 186.45  | 177.91 |           
|               | gto           | 185.42  | 176.2  |           
|               | KAWS          | 183.54  | 173.31 |           
| GMM           | lrr           | 69.47   | 67.01  |           
|               | gto           | 72.16   | 67.13  |           
|               | KAWS          | 75.61   | 67.3   |           
| SMM           | lrr           | 143.21  | 142.01 |           
|               | gto           | 148.59  | 142.11 |           
|               | KAWS          | 152.56  | 142.8  |           


# Normalised to LRR
| **Benchmark** | **Scheduler** | **IPC** |        | 
|---------------|---------------|---------|--------|
|               |               | w WS    | w/o WS |
| BFS           | lrr           | 100     | 100    |
|               | gto           | 103.61  | 100.73 |            
|               | KAWS          | 104.65  | 99.08  |            
| HS            | lrr           | 100     | 100    |            
|               | gto           | 112.72  | 101.07 |            
|               | KAWS          | 113.14  | 103.98 |            
| SC            | lrr           | 100     | 100    |            
|               | gto           | 101.33  | 100.64 |            
|               | KAWS          | 102.42  | 101.64 |            
| NW            | lrr           | 100     | 100    |            
|               | gto           | 100     | 100.63 |            
|               | KAWS          | 100     | 98.64  |            
| PF            | lrr           | 100     | 100    |            
|               | gto           | 103.85  | 102.57 |            
|               | KAWS          | 105.42  | 103.43 |            
| NN            | lrr           | 100     | 100    |            
|               | gto           | 99.44   | 98.92  |            
|               | KAWS          | 98.43   | 97.41  |            
| GMM           | lrr           | 100     | 100    |            
|               | gto           | 103.87  | 100.17 |            
|               | KAWS          | 108.83  | 100.43 |            
| SMM           | lrr           | 100     | 100    |            
|               | gto           | 103.75  | 100.07 |            
|               | KAWS          | 106.52  | 100.55 |    
| AVERAGE       | lrr           | 100     |           
|               | gto           | 103.57  |            
|               | KAWS          | 104.92  | 
