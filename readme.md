# Computation of motivic Hilbert scheme of curve singularities

The goal of this paper is to develop an algorithm for computing the motivic Hilbert zeta function for curve singularities with a monomial local ring.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

Instructions for installing your project.

```bash
# Clone the repository
git clone https://github.com/chenyizi086/hilbert

# Navigate to the directory
cd hilbert

# Create new environment
conda create -n "hilbert" python=3.x.x

# Activate conda environment
conda activate hilbert

# Install dependencies
pip install numpy
```

## Usage
To calculate the hibert from list_all, please use following example:

```bash
python calculate_hilbert.py --list_all 4, 6, 13
```

## Example output
These are the outputs generate from the previous command: 

```
[4, 6, 13]
1-th 1.0
2-th 1.0 + 1.0·x + 1.0·x²
3-th 1.0 + 2.0·x + 1.0·x²
4-th 1.0 + 1.0·x + 3.0·x² + 1.0·x³
5-th 1.0 + 1.0·x + 3.0·x² + 2.0·x³
6-th 1.0 + 1.0·x + 3.0·x² + 3.0·x³ + 2.0·x⁴
7-th 1.0 + 1.0·x + 2.0·x² + 4.0·x³ + 3.0·x⁴
8-th 1.0 + 1.0·x + 2.0·x² + 4.0·x³ + 4.0·x⁴ + 2.0·x⁵
9-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 5.0·x⁴ + 3.0·x⁵
10-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 5.0·x⁴ + 4.0·x⁵ + 2.0·x⁶
11-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 4.0·x⁴ + 5.0·x⁵ + 3.0·x⁶
12-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 4.0·x⁴ + 5.0·x⁵ + 4.0·x⁶ + 1.0·x⁷
13-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 4.0·x⁴ + 4.0·x⁵ + 5.0·x⁶ + 2.0·x⁷
14-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 4.0·x⁴ + 4.0·x⁵ + 6.0·x⁶ + 3.0·x⁷
15-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 4.0·x⁴ + 4.0·x⁵ + 6.0·x⁶ + 3.0·x⁷
16-th 1.0 + 1.0·x + 2.0·x² + 3.0·x³ + 4.0·x⁴ + 4.0·x⁵ + 6.0·x⁶ + 3.0·x⁷ + 1.0·x⁸
```

## Features
- List the key features of your proejct
- Additional details

## contributing
Contributions are welcome! Please follow these steps:

- Fork the project.
- Create your feature branch: ```git checkout -b feature/AmazingFeature```.
- Commit your changes: ```git commit -m 'Add some AmazingFeature'```.
- Push to the branch: ```git push origin feature/AmazingFeature```.
- Open a pull request.

Please ensure your code adheres to the project’s code style and includes relevant tests.

## License
This project is licensed under the MIT license.

## Contact
Wenhao Zhu [wenhao.zhu.alg@gmail.com](wenhao.zhu.alg@gmail.com)
