# Topology

`topology` field captures the shape of the network one wants to model or simulate.

## Basic Network Building Blocks
Analytical network simulator supports 3 basic network building blocks.
- Ring
- FullyConnected
- Switch

Below image visualizes the shape of basic network building blocks.

![Network Building Blocks](/_static/images/input-format/network-building-blocks.svg)

Below is an example 1D Switch topology.
:::{code-block} yaml
topology: [ Switch ]
:::

## Multi-dimensional Network Topology
By stacking up multiple network building blocks, one can also represent multi-dimensional network topologies.

Below image visualizes sample 2D and 3D topologies.

![Multi-dimensional Network Samples](/_static/images/input-format/multidim-network-example.svg)

Above samples can be captured as below in the `.yml` input format.
:::{code-block} yaml
topology: [ Ring, Switch ]  # 2D topology
topology: [ Ring, Ring, Ring ]  # 3D topology
:::
