# scripts/

Analysis scripts, numbered in the order in which they should be run.

## Scripts

| Script | Purpose | Main inputs | Main outputs |
|---|---|---|---|
| `01_[name]` | [e.g. import and clean the data] | `data/` | `outputs/` |
| `02_[name]` | [e.g. fit the models] | `outputs/` | `outputs/` |
| `03_[name]` | [e.g. produce the figures] | `outputs/` | `figures/` |

## Running the analyses
[Language and version, how to run the scripts (in order, or via a main script), and approximate run time.]

## Good practice
- Use paths relative to the repository root, not to your own computer.
- Set a random seed when the analyses involve randomness.
- Load the packages each script needs at the top of the script.
