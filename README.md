# etunes
Music composition using genetic Algorithms.

## Installation
To run this program, please install timidity (from apt-get) and pyknon (sudo pip install pyknon) first.
Clone the repository into your local machine. (git clone https://github.com/sanjaybv/etunes.git)

## Running
To run the program type in "python etunes.py <some-name>".

The CLI options are
play <tune-number>            - Plays the tune
score <tune-number> <score>   - Scores the tune number (feel free to use your own scale of scoring)
done                          - Moves to the next generation (selection, cross-over and mutation)
choose <tune-number>          - Selects this tune as your final tune and quits the program

The final tunes are stored in the "midi" folder.
