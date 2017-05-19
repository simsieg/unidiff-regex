# Unidiff-Regex
Contains a regex for the unidiff format.
https://en.wikipedia.org/wiki/Diff#Unified_format

# Regex
This Regex captures the whole unidiff. It can be modified to capture all groups/lines.

\-{3}.*\n\+{3}.*\n(?:@@\s*\-\d*,\d*\s*\+\d*,\d*\s*@@(?:.*?\n?)*)+

Try at: https://regex101.com/r/CtHqPQ/3
|
