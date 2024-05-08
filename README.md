## Caching and pre-fetching: the role of hazard rates.

### Resumen:

Consider a caching system receiving requests from a given catalog. The cache objective is to maximize its hit rate, i.e. the number of items that are served directly from the cache. Two main alternatives have been studied: replacement policies (such as LRU) and timer-based policies (TTL).
In previous work, we have explored the role of the hazard rate function of the inter-request times in the optimal TTL policy. Recently, Towsley et al. also identified that the optimal non-anticipative replacement policy involves the hazard rate function.
In this talk we will discuss how these two concepts relate, in the case of decreasing hazard rates. In particular, we show that, in large scale systems, the optimal non-anticipative policy converges to a fixed threshold policy, and that this threshold is exactly the dual value of the convex optimization problem that defines the optimal TTL policy. Therefore, we can approximate the optimal hit rate by the TTL policy fluid limit, allowing us to compute a universal performance bound. In particular, for decreasing hazard rates caching is the optimal policy, while for increasing hazard rates, a dual situation occurs and pre-fetching becomes optimal.


**Note**: Talk given in the ISyE department, Georgia Tech University, May 2024.