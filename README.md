A Pokémon battle-bot that can play battles on [Pokemon Showdown](https://pokemonshowdown.com/).

Pokemon Showdown can play single battles in all generations
though currently dynamax and z-moves are not supported.


## Python version
Requires Python 3.11+.

## Getting Started

### Configuration

Command-line arguments are used to configure Pokemon-Showdown

use `python run.py --help` to see all options.

### Running Locally

**1. Clone**

Clone the repository with `git clone https://github.com/zaamrokk/Pokemon-Showdown.git`

**2. Install Requirements**

Install the requirements with `pip install -r requirements.txt`.

Note: Requires Rust to be installed on your machine to build the engine.

**4. Run**

Run with `python run.py`

Here is a minimal example that plays a gen9randombattle on Pokemon Showdown:
```bash
python run.py \
--websocket-uri wss://sim3.psim.us/showdown/websocket \
--ps-username 'My Username' \
--ps-password sekret \
--bot-mode search_ladder \
--pokemon-format gen9randombattle
```

