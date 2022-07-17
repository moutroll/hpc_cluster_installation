# Description

Creation of a simple HPC cluster based on SLURM and Enroot. All jobs will be executed in a container to keep the host integrity over time.

The configuration of the cluster is:

| Hostname |       IP        | CPU | Memory |
|----------|:---------------:|----:|--------|
| master   | 192.168.122.214 |   5 | 4Go    |
| node1    | 192.168.122.178 |   5 | 4Go    |
| node2    | 192.168.122.132 |   5 | 4Go    |


| Type   | version |
|--------|---------|
| Debian | 11.4.0  |
| Slurm  | 20.11.4 |
| Enroot | 3.4.0   |
| Pyxies | 0.13.0  |

# Roadmap

- [ ] Installation of the SLURM cluster
    - [x] Installation script description
    - [ ] Description and explanation of parameters
- [ ] Installation of the distributed and shared filesystem and Docker Registry
  - [ ] Installation of Docker Registry
  - [ ] Installation of the distributed and shared filesystem
- [x] Documentation of basic usages
