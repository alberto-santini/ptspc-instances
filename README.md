# PTSPC Instances

Instances for the Probabilistic Travelling Salesman Problem with Crowdsourcing.

## Format

The format follows the classical TSPLIB format, with new sections `ACCEPTED_PROBABILITIES` for the probabilities and `OUTSOURCING_COSTS` for the fees.
The size reported in the filename of each instance refers to the total number of vertices, including the depot.
So an instance file starting with `sz-13-` will have thirteen vertices: twelve delivery points and one depot.
The depot is also listed in the probabilities and fees sections mentioned above, as the first entry; it always has probability 0 and fee 0.
Furthermore, the coordinates of the depot are always (0, 0).

## Paper

The current citation for the paper is the following:

```
@article{ptspc,
  author={Santini, Alberto and Viana, Ana and Klimentova, Xenia and Pedroso, João Pedro},
  title={The Probabilistic Travelling Salesman with Crowdsourcing},
  year={2020},
  journal={Preprint}
}
```

## License

The instances are released under the GNU Public License version 3.0 (see file `LICENSE`).
