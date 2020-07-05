[![License](https://img.shields.io/github/license/erdnaxe/kraby?style=flat-square)](LICENSE)
[![Documentation Status](https://img.shields.io/readthedocs/kraby?style=flat-square)](https://kraby.readthedocs.io/en/latest/)
[![Travis (.com)](https://img.shields.io/travis/com/erdnaxe/kraby?style=flat-square)](https://travis-ci.com/github/erdnaxe/kraby)
[![PyPI](https://img.shields.io/pypi/v/gym_kraby?style=flat-square)](https://pypi.org/project/gym-kraby/)
[![Codacy grade](https://img.shields.io/codacy/grade/537008118a7948f3bb3e596fcae9d4db?style=flat-square)](https://www.codacy.com/manual/erdnaxe/kraby)

# Kraby

![Hexapod robot](docs/img/hexapod.jpg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ferdnaxe%2Fkraby.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Ferdnaxe%2Fkraby?ref=badge_shield)

Kraby is an hexapod robot.
It is an open source development platform for educational purpose.
It was designed for a Master 1
project at [ENS Paris-Saclay](https://ens-paris-saclay.fr/).

You may read documentation at <https://kraby.readthedocs.io/>

## Build the documentation

Install `mkdocs` then run `mkdocs serve`.

## Install OpenAI environment

```bash
pip install gym_kraby --user
python -m gym_kraby.demo
```

To test servomotors communication with the robot, you may execute `python -m gym_kraby.utils.herkulex_socket`.

## License

This project is under GNU General Public License v3.0 because we believe in
open development. Please see LICENSE file for more details.


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ferdnaxe%2Fkraby.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Ferdnaxe%2Fkraby?ref=badge_large)