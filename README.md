
## Building
#### Ubuntu 16.04 LTS
=====
- `sudo apt-get update && sudo apt-get upgrade --yes`
- `git clone https://github.com/rocksteadytc/ooze`
- `cd ooze/cryptonote/`
- `git clone https://github.com/turtlecoin/turtlecoin . `
- `cd ..`
- `mkdir build && cd $_`
- `cmake ..`
- `make -j4`
