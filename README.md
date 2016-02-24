# etunes
Music composition using Genetic Algorithms.

## Installation
To run this program, please install timidity (from apt-get) and pyknon `sudo pip install pyknon` first.
Clone the repository into your local machine. `git clone https://github.com/sanjaybv/etunes.git`

## Running
To run the program type in "python etunes.py \<name-of-your-tune\>".

The CLI options are

1. `play <tune-number>`               - Plays the tune
2. `score <tune-number> <score>`    - Scores the tune number (feel free to use your own scale of scoring)
3. `done`                               - Moves to the next generation (selection, cross-over and mutation)
4. `choose <tune-number>`             - Selects this tune as your final tune and quits the program

The final tunes are stored in the "midi" folder.
