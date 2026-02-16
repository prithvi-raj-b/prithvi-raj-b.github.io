---
date: '2024-08-20T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Parallelized RRT Connect using Hybrid OpenMP, MPI architecture'
draft: false # set to "true" if you want to hide the content 

# link: "https://www.adrianmoreno.info" # optional URL to link the logo to

params:
    image:
        src: "images/works/parallel.png"
        scale: 1.1

## The content is used for the description of the project
---

This project explores parallel implementations of RRT-Connect, an asymptotically optimal sampling-based motion planning algorithm, to address the computational bottlenecks of nearest-neighbor search and collision checking.We designed two hybrid MPI-OpenMP strategies: an incremental approach using vector-based storage and a more advanced implementation leveraging a K-D tree for logarithmic-time neighbor queries. Both methods parallelize tree expansion and bidirectional connection while managing synchronization, race conditions, and non-blocking communication. Benchmarking against a serial baseline demonstrated dramatic improvements in node generation throughput, with the K-D tree strategy achieving orders-of-magnitude efficiency gains.

```