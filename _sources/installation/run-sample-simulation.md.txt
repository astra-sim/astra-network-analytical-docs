# Run Simulation

After the binary has been created, run the simulation.

## Congestion_Unaware Simulation
:::{code-block} console
$ ./bin/Analytical_Congestion_Unaware
:::

You'll see simulation results printed out similar to this.
:::{code-block} console
Total NPUs Count: 64
comm_delay: 23531
:::

## Congestion_Aware Simulation
:::{code-block} console
$ ./bin/Analytical_Congestion_Aware
:::

You'll see simulation results printed out similar to this.
:::{code-block} console
...
A chunk arrived at destination at time: 704116 ns
A chunk arrived at destination at time: 704116 ns
A chunk arrived at destination at time: 704116 ns
Total NPUs Count: 16
Total devices Count: 16
Simulation finished at time: 704116 ns
:::
