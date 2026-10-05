# From Laptop to Cluster

An interactive first look at research computing for people with no background. One story: your storm simulation is too big for your laptop. There are two ways forward.

**Start**
1. **Why scale up.** Sharpen a storm forecast map and watch the work multiply.

**Bigger laptop (ICRN)**
2. **ICRN.** Illinois Computes Research Notebooks: same speed as one core, but nothing to install and it keeps running when you close the lid (up to 24 hours).

**Cluster**
3. **Parallel jobs.** Add cores across nodes. A job array speeds up perfectly; one giant MPI job does not.
4. **Communication.** Domain decomposition: cut the map into patches and watch the halo exchange eat the gains.
5. **Job placement.** The same job packed on one node, or spread across nodes that share the network.
6. **Batch jobs.** Write a job script, submit it, wait in the queue, run, collect.
7. **Sizing a job.** Meet a 30-hour deadline inside a 3,000 core-hour budget.

**Decide**
8. **Which resource.** Pick a job and compare laptop, ICRN, and cluster.

Each step fits on one screen on a laptop display. Each cluster step has an "In HPC terms" box that maps the analogy to real terms. Use the tabs, Back/Next, or the arrow keys. "Words to know" opens a glossary.

All numbers are illustrative teaching values, not benchmarks of any system. ICRN limits come from the [Illinois Computes ICRN page](https://computes.illinois.edu/resources/icrn/) and may change.

## Run it

Open `index.html` in a browser. No build step.

## Host it

Enable GitHub Pages on the `main` branch, root folder.
