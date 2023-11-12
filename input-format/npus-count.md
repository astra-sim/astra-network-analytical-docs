# NPUs Count

`npus_count` field denotes the size (i.e., number of NPUs) of the network.

![Example network topologies](/_static/images/input-format/npus-count-example.svg)

The size of of the above example 1--3D topologies can be captured in the `.yml` format as below.

:::{code-block} yaml
npus_count: [ 5 ]  # 5 NPUs
npus_count: [ 4, 2 ]  # 4 × 2 = 8 NPUs
npus_count: [ 4, 2, 2 ]  # 4 × 2 × 2 = 16 NPUs
:::

Note that we represent the number of NPUs per each dimension in the `.yml` format. Thus, if `npus_count: [ 4, 2, 2 ]`, it denotes that the number of total NPUs in the network is 4 × 2  × 2 = 16.