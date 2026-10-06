# From Laptop to Cluster

An interactive introduction to research computing for graduate students and other researchers who are new to it. The pages follow one example, a storm simulation that has outgrown a laptop, and show when an ICRN notebook is enough and when you need a cluster.

**Start**
1. **Why scale up.** Make the forecast grid finer and see how quickly the work grows.

**Bigger laptop (ICRN)**
2. **ICRN.** Illinois Computes Research Notebooks run at about the speed of one core, but there is nothing to install and they keep running after you close your laptop (up to 24 hours).

**Cluster**
3. **Parallel jobs.** Add cores across nodes. A job array speeds up almost perfectly, and a single large MPI job does not.
4. **Communication.** Split a map into patches and see how the halo exchange cuts into the speedup.
5. **Job placement.** Run the same job on one node or spread across nodes that share the network.
6. **Batch jobs.** Write a job script, submit it, wait in the queue, run, and collect the output.
7. **Sizing a job.** Meet a 30-hour deadline within a 3,000 core-hour allocation.

**Decide**
8. **Which resource.** Pick the kind of work and how much of it, and see whether your laptop, ICRN, the Illinois Campus Cluster, Delta, DeltaAI or Radiant fits best.

Each step fits on one screen on a laptop display. Use the tabs, the Back and Next buttons, or the arrow keys. "Words to know" opens a glossary.

The simulation numbers are illustrative teaching values, not benchmarks of any system. Resource details come from the Illinois Computes, Campus Cluster and NCSA documentation pages and may change.

## Run it

Open `index.html` in a browser. No build step.

## Host it

Enable GitHub Pages on the `main` branch, root folder.
