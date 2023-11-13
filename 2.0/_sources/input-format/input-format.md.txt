# Input Format

The analytical network simulator uses YAML files to define multi-dimensional network characteristics.

Shown below is a sample `.yml` network input file.
:::{code-block} yaml
# 3D (Ring_FullyConnected_Switch) topology
topology: [ Ring, FullyConnected, Switch ]

# 2 x 8 x 4 = 64 NPUs
npus_count: [ 2, 8, 4 ]  # number of NPUs

# Bandwidth per each dimension
bandwidth: [ 200.0, 100.0, 50.0 ]  # GB/s

# Latency per each dimension
latency: [ 50.0, 500.0, 2000.0 ]  # ns
:::

:::{toctree}
topology.md
npus-count.md
bandwidth.md
latency.md
:::
