# Latency

The `latency` field defines the latency of each (uni-directional) link in ns.

:::{note}
The simulator deems 1 s as 10^9 ns.
:::

![Example network latency configuration](/_static/images/input-format/example-latency.svg)

In the first example above, we have a bi-directional link, where each uni-directional link latency is 10 ns. This can be captured in the `.yml` representation as below.

:::{code-block} yaml
latency: [ 10.0 ]  # ns
:::

In the second example, a 2D topology is shown. The 1st dim has a bi-directional link whose uni-directional latency is 200 ns. Likely, the 2nd dim leverages bi-directional links, whose uni-directional link latency is 1600 ns. This can be captured in the `.yml` format as below:

:::{code-block} yaml
latency: [ 200.0, 1600.0 ]  # ns
:::
