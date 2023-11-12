# Bandwidth

`bandwidth` field defines the bandwidth of each (uni-directional) link in GB/s.

:::{note}
The simulator deems 1 GB as 2^30 B, and 1 s as 10^9 ns.
:::

![Example network bandwidth configuration](/_static/images/input-format/example-bandwidth.svg)

In the first example above, we have a bi-directional link, where each uni-directional link bandwidth is 50 GB/s. This can be captured in the `.yml` representation as below.

:::{code-block} yaml
bandwidth: [ 50.0 ]  # GB/s
:::

In the second example, a 2D topology is shown. The 1st dim has a bi-directinal link whose uni-directional bandwidth is 120 GB/s. Likely, the 2nd dim leverages bi-directional links, whose uni-directional link bandwidth is 20 GB/s. This can be captured in the `.yml` format as below:

:::{code-block} yaml
bandwidth: [ 120.0, 20.0 ]  # GB/s
:::
