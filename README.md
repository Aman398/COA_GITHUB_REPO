# COA_GITHUB_REPO
Computer Organisation and Architecture
(**Group-12**) <br /> <br />
This repo is created to contain the implementation of *KAWS: Coordinate Kernel-Aware Warp Scheduling* (ENDSEM) and the implementation to print different warp states as described in *Equalizer: Dynamic Tuning of GPU Resources for Efficient Execution* (MIDSEM) <br />

# Results 
| **Benchmark** | **Scheduler** | **IPC** |        | 
|---------------|---------------|---------|--------|
|               |               | w WS    | w/o WS |
| PF            | lrr           | 701.25  | 698.72 |           
|               | gto           | 728.78  | 716.78 |           
|               | KAWS          | 739.32  | 722.63 |  
| HS            | lrr           | 2157.7  | 2091.5 |           
|               | gto           | 2432.66 | 2113.9 |           
|               | KAWS          | 2441.84 | 2174.8 |  
| 3DC           | lrr           | 269.86  | 250.63 |           
|               | gto           | 279.38  | 256.84 |           
|               | KAWS          | 293.38  | 253.79 |  
| 3MM           | lrr           | 298.59  | 291.3  |           
|               | gto           | 298.59  | 291.32 |           
|               | KAWS          | 315.7   | 292.18 |  
| BFS           | lrr           | 97.84   | 96.99  |
|               | gto           | 101.37  | 97.7   |            
|               | KAWS          | 102.39  | 96.1   |                   
| NW            | lrr           | 22.65   | 22.11  |           
|               | gto           | 22.64   | 22.25  |           
|               | KAWS          | 22.64   | 21.81  |                    
| NN            | lrr           | 186.45  | 177.91 |           
|               | gto           | 185.42  | 176.2  |           
|               | KAWS          | 183.54  | 173.31 |                   


# Normalised to LRR
| **Benchmark** | **Scheduler** | **IPC** |        | 
|---------------|---------------|---------|--------|
|               |               | w WS    | w/o WS |
| PF            | lrr           | 100     | 100    |            
|               | gto           | 103.85  | 102.57 |            
|               | KAWS          | 105.42  | 103.43 | 
| HS            | lrr           | 100     | 100    |            
|               | gto           | 112.72  | 101.07 |            
|               | KAWS          | 113.14  | 103.98 |  
| 3DC           | lrr           | 100     | 100    |            
|               | gto           | 103.52  | 102.47 |            
|               | KAWS          | 108.71  | 101.26 | 
| 3MM           | lrr           | 100     | 100    |            
|               | gto           | 100     | 100    |            
|               | KAWS          | 105.73  | 100.3  | 
| BFS           | lrr           | 100     | 100    |
|               | gto           | 103.61  | 100.73 |            
|               | KAWS          | 104.65  | 99.08  |                                 
| NW            | lrr           | 100     | 100    |            
|               | gto           | 100     | 100.63 |            
|               | KAWS          | 100     | 98.64  |            
| NN            | lrr           | 100     | 100    |            
|               | gto           | 99.44   | 98.92  |            
|               | KAWS          | 98.43   | 97.41  |               
| AVERAGE       | lrr           | 100     | 100    |   
|               | gto           | 103.30  | 100.91 |           
|               | KAWS          | 105.15  | 100.58 |

# Performance Graphs

![Screenshot 2023-11-10 023431](https://github.com/Aman398/COA_GITHUB_REPO/assets/94309830/74d9505d-a268-4c10-886f-9056f162940c)

![Screenshot 2023-11-10 022501](https://github.com/Aman398/COA_GITHUB_REPO/assets/94309830/0dbb9123-5776-4a7c-adf3-7d34d6b8780c)

![Screenshot 2023-11-10 014735](https://github.com/Aman398/COA_GITHUB_REPO/assets/94309830/73623eb3-7bfa-4af7-9214-912ccec323e3)
