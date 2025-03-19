Under data/

`1.aln.phy`: Phylip-formatted alignment

`1.aln`: Fasta-formatted alignment

`1.sim.treefile`: the tree used in simulation (the "true" tree)

# command on server
`iqtree -s 1.aln -m LG+G -prefix LG+G`

`iqtree -s 1.aln -m LG -prefix LG`

`iqtree -s 1.aln -m POISSON -prefix POISSON`
