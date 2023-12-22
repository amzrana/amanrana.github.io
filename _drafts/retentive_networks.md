# [Blog] A look at Retentive Networks

> **21th Januray, 2024**

### [HOME](../index.md)

&nbsp;

## Some background
Transformer [VSP+17] has become the de facto architecture for large language mod- els [BMR+20], which was initially proposed to overcome the sequential training issue of recurrent models [HS97]. However, training parallelism of Transformers is at the cost of in- efficient inference, because of the O(N) com- plexity per step and memory-bound key-value cache [Sha19], which renders Transformers un- friendly to deployment. The growing sequence length increases GPU memory consumption as well as latency and reduces inference speed.
Numerous efforts have continued to develop the next-generation architecture, aiming at retain- ing training parallelism and competitive perfor- mance as Transformers while having efficient O(1) inference. It is challenging to achieve the above goals simultaneously, i.e., the so-called
“impossible triangle” as shown in Figure 2.

## Intuitive mental model of Retentive Networks

< Add intuitive explanation >

## Lets test it out in practice

### Baseline model
> Code is available [HERE]()

### RetNet model
> Code is available [HERE]()
