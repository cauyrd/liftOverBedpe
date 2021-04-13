# liftOverBedpe

This is a simple python wrapper for the tool liftOVer that allows users to liftOver BEDPE files from one genome build to another.

### Prerequisites

liftOverBedpe requires [liftOver](https://genome.sph.umich.edu/wiki/LiftOver), a liftOver chain file, and python

### Installing

None required

### Example

```
# convert to hg19 
python liftOverBedpe.py --lift ./liftOver --chain hg38ToHg19.over.chain.gz --i input.hg38.bedpe --o output.hg19.bedpe 
```
