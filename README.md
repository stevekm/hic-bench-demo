# Demo HiC-Bench ChIP-Seq Pipeline

designed for use in NYU Langone Medical Center

# Installation

## HiC-Bench

Make sure you've got [HiC-Bench](https://github.com/NYU-BFX/hic-bench) installed. This is typically installed in your home directory. 

```
cd
git clone https://github.com/NYU-BFX/hic-bench.git
```

If you're working on the phoenix server at NYU, make sure you have your `data` directory linked to Aris's.

```
cd hic-bench
ln -s /ifs/home/at570/disk1/Resources/Code/pipeline-master/data data
```

NOTE: you might have to delete the broken `data` symlink before you can reset it.

## This Demo

Clone this demo repository, and change to its directory

```
git clone ...
cd ...
```

# Usage