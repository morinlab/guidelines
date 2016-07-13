## Short Description

Describe the proposed guideline in one sentence. Don't bring up the rationale just yet. 

For example: 

> Parameterize (semi-)arbitrarily chosen numbers, and explain how the default value was chosen and the use case they're intended for. 

## Rationale

Provide a more detailed description for the proposed guideline and its rationale. Ideally, mention advantages and disadvantages to expect from following the guideline. 

For example:

> Scripts commonly use thresholds, cut-offs or other (semi-)arbitrarily chosen numbers. The value of these variables typically have a significant effect on the script's output and thus they should be discoverable by the user. Parameterizing these variables is a straightforward way for exposing them to the user. Otherwise, they are concealed within the script. This also allows the user to easily edit the values according to their needs. The default value for these variables should be explained whenever possible; it's important to describe how they were obtained and the use case they're intended for. This helps the user determine whether the default is appropriate for their specific use case. 

## Example Implementations

Provide real-world scenarios where this guideline is relevant and how it should be applied. 

For example: 

> If your code consists of modular functions, every (semi-)arbitrarily chosen number should become a parameter for the function that contains it. In the case of a script, these parameters should all be made user-adjustable as command-line arguments. If default values are provided, explain how they were obtained and what use case they're intended for in the script's self-documentation (_e.g._ docstrings in Python) and/or associated README.

## Sources

Post any relevant links to the proposed guideline. 

For example: 

> http://www.jonzelner.net/statistics/make/docker/reproducibility/2016/05/31/script-is-a-program#command-line-options
