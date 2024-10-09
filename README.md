# SIMPLE RHMC

| INSTANCE | UNIVERSE SIZE | NUMBER OF SETS | DENSITY | FIRST FITNESS                        | LAST FITNESS                         | EXECUTION TIME |
|----------|---------------|----------------|---------|--------------------------------------|--------------------------------------|----------------|
| 1        | 100           | 10             | 0.2     | (np.False_, np.float64(-106.48413616902235)) | (np.False_, np.float64(-0.0))        | 0,0s           |
| 2        | 1000          | 100            | 0.2     | (np.False_, np.float64(-10270.667099835624)) | (np.True_, np.float64(-7210.218665896575)) | 0,1s           |
| 3        | 10000         | 1000           | 0.2     | (np.True_, np.float64(-1183391.1995854625))  | (np.True_, np.float64(-1093248.6086899177)) | 0,3s           |
| 4        | 100000        | 10000          | 0.1     | (np.True_, np.float64(-74611337.23132354))   | (np.True_, np.float64(-73757667.630550109)) | 20,0s          |
| 5        | 1000000       | 10000          | 0.2     | (np.True_, np.float64(-165086992.92953542))  | (np.True_, np.float64(-163683872.51812327)) | 24,1s          |
| 6        | 1000000       | 10000          | 0.3     | (np.True_, np.float64(-252243668.31114995))  | (np.True_, np.float64(-249552858.76361138)) | 20,2s          |

the Greedy approach gives a valid solution but Simple RHMC is more efficient for large number of "universe size" and "number of sets". Starting from four instance it takes a lot of time.
