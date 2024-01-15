# Ultrasoud Dataset for Collision Avoidance in Industrial Machinery

This repository contains...    M. Zanghieri *et al*. [[1]](#1)
For a **technical report** about an earlier stage of the same research project, please refer to F. Conti *et al*. [[2]](#2).



## Usage

To run this small project, clone this repository:
```
git clone git@github.com:pulp-bio/tcn_under_review.git
```
The files expose the TCN's implementation and PyTorch and the file ``tcn_table.txt`` already contains the generated TCN's structure table.

The requirements (see ``requirements.txt``) are the Python packages PyTorch 1.9.0 and torchinfo 1.8.0, quickly installable via the shell with
```
python -m pip install -r requirements.txt
```
The TCN is implemented in the module ``tcn.py``.
1. Run ``visualize_tcn_table.ipynb`` (or equivalently ``visualize_tcn_table.py``) to generate the TCN, its ``torchinfo.ModelStatistics``, and the printed table.
2. See the printed table in the standard output or in the file ``tcn_table.txt``.

The generated output file is identical to the one already available in the repository.



## Authors

- [Marcello Zanghieri](https://scholar.google.com/citations?user=WnIqQj4AAAAJ&hl=en) (University of Bologna)
- Fabrizio Indirli (work conducted when working at Politecnico di Milano and STMicroelectronics)
- Antonio Latella (SCM Group)
- Francesco Papariello (STMicroelectronics)
- Giulio Urlini (STMicroelectronics)
- [Prof. Luca Benini](https://scholar.google.com/citations?user=8riq3sYAAAAJ&hl=en) (University of Bologna, ETH Zürich)
- [Prof. Francesco Conti](https://scholar.google.it/citations?user=A70PCXoAAAAJ&hl=en)  (University of Bologna)



## Citation

When using the dataset, please cite its supporting paper:
```
@article{zanghieri2024extreme,
  author={Zanghieri, Marcello and Indirli, Fabrizio and Latella, Antonio and Papariello, Francesco and Urlini, Giulio and Benini, Luca and Conti, Francesco},
  journal={IEEE Access (ACCEPTED: TO APPEAR)}, 
  title={An Extreme-Edge {TCN}-Based Low-Latency Collision-Avoidance Safety System for Industrial Machinery}, 
  year={2024},
  volume={},
  number={},
  pages={},
  doi={}}
```



## References

<a id="1">[1]</a>
M. Zanghieri *et al*., "An Extreme-Edge TCN-Based Low-Latency Collision-Avoidance Safety System for Industrial Machinery," in *IEEE Access* (ACCEPTED: TO APPEAR). 2024.

<a id="2">[2]</a>
F. Conti *et al*., "AI-powered collision avoidance safety system for industrial woodworking machinery," in *AI4DI – Applications*. River Publishers, 2021. DOI: [10.1201/9781003337232-17](https://www.doi.org/10.1201/9781003337232-17).



## License

All files are released under the LGPL-2.1 license (`LGPL-2.1`) (see `LICENSE`).
