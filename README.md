![Grocery delivery](grocery-delivery.jpg)
<sub><sub>Photo by Kindel Media, released under the [Pexel license](https://www.pexels.com/license/)</sub></sub>

# PTSPC Instances

Instances for the **Probabilistic Travelling Salesman Problem with Crowdsourcing**.

## Citation

If you use these instances, please cite the paper as follows:

```bib
@article{ptspc,
  title={The probabilistic {Travelling Salesman Problem} with crowdsourcing},
  author={Santini, Alberto and Viana, Ana and Klimentova, Xenia and Pedroso, João Pedro},
  journal={{Computers \& Operations Research}},
  volume={142},
  doi={10.1016/j.cor.2022.105722},
  year={2022}
}
```

You can also cite this repository via Zenodo.

[![DOI](https://zenodo.org/badge/295767031.svg)](https://zenodo.org/badge/latestdoi/295767031)

```bib
@misc{ptspc_github,
    title={Instances for the Probabilistic Travelling Salesman Problem with Crowdsourcing},
    author={Santini, Alberto},
    date={2020-09-15},
    howpublished={Github repository},
    doi={10.5281/zenodo.4031192},
    url={https://github.com/alberto-santini/ptspc-instances/}
}
```

## Format

The format follows the classical TSPLIB format, with new sections `ACCEPTED_PROBABILITIES` for the probabilities and `OUTSOURCING_COSTS` for the fees.
The size reported in the filename of each instance refers to the total number of vertices, including the depot.
So an instance file starting with `sz-13-` will have thirteen vertices: twelve delivery points and one depot.
The depot is also listed in the probabilities and fees sections mentioned above, as the first entry; it always has probability 0 and fee 0.
Furthermore, the coordinates of the depot are always (0, 0).

## License

The instances are released under the GNU Public License version 3.0 (see file `LICENSE`).
