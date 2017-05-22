# Colley
Script to compute Colley bias-free ranking, for personal amusement.
Language: Octave / MATLAB
Data format. Requries that game data be entered in a plain text file.
The file has one line per contest.
Each line has three fields:
a - team_1 name (typically the visiting team)
b - game result: 'd' means 'team_1' defeated 'team_2'. Use 'l' for loss.
c - team_2 name (typically the home team)
Text lines with '-' in first column are ignored

