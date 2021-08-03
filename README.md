# Installation

- `git clone https://github.com/HarryTurner93/charge.git`
- `cd charge`
- `conda create --name charge python=3.9`
- `conda activate charge`
- `pip3 install -r requirements.txt`

# Run

If running on your own machine run:
- `jupyter notebook`

If running on a remote server run:
- `jupyter notebook --port 8888 --no-browser --ip 0.0.0.0`
- Connect to it at `<ip-of-remote>:8888` and copy in the token generated in the terminal.
