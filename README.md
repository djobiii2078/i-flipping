# i-flipping
i-flipping patch. This is a small patch to tweak the network reception mechanism used by Xen running on NUMA machines to reduce the impact of zero-copy. Check out our paper at INFOCOM'2019 . ♦ Memory flipping: a threat to NUMA virtual machines in the Cloud for more information.

## Apply the patch

The patch can be applied on Linux 4-4.12 (https://cdn.kernel.org/pub/linux/kernel/v4.x/). To apply the patch, in the linux folder: 
  patch -s p0 < i-flipping.patch

## Get in touch 
We would love any feedback to improve this work. Please, ping us at mvondodb@univ-grenoble-alpes.fr
