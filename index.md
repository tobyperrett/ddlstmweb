<p align="center" style="font-size:30px">
<a href="https://tobyperrett.github.io/">Toby Perrett</a> and <a href="https://dimadamen.github.io/">Dima Damen</a>
</p>

![Image](2x3.pdf)

## Abstract

Domain alignment in convolutional networks aims to learn the degree of layer-specific feature alignment beneficial to the joint learning of source and target datasets. While increasingly popular in convolutional networks, there have been no previous attempts to achieve domain alignment in recurrent networks. Similar to spatial features, both source and target domains are likely to exhibit temporal dependencies that can be jointly learnt and aligned.

In this paper we introduce Dual-Domain LSTM (DDLSTM), an architecture that is able to learn temporal dependencies from two domains concurrently.  It performs cross-contaminated batch normalisation on both input-to-hidden and hidden-to-hidden weights, and learns the parameters for cross-contamination, for both single-layer and multi-layer LSTM architectures. We evaluate DDLSTM on frame-level action recognition using three datasets, taking a pair at a time, and report an average increase in accuracy of 3.5%. The proposed DDLSTM architecture outperforms standard, fine-tuned, and batch-normalised LSTMs.

## Video


<iframe align="center" width="640" height="360" src="https://www.youtube.com/embed/8MtC6X4w4jE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## Paper

[PDF](ddlstm.pdf)

[ArXiv](https://arxiv.org/)

## Bibtex

```markdown
@InProceedings{perrettdamen19ddlstm,
    author    = {Perrett, Toby and Damen, Dima},
    title     = {DDLSTM}: {D}ual-{D}omain {LSTM} for {C}ross-{D}ataset {A}ction {R}ecognition,
    booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year      = {2019}
}
```

## Acknowledgements
This research is supported by [EPSRC LOCATE (EP/N033779/1)](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/N033779/1).
