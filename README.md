# fluid-hopfield-network
This repository contains a Python implementation of the Fluid Hopfield Network, which is a model for retrieving stored memories. It an extension of the well-known Modern Hopfield Network (Krotov & Hopfield, 2020) in that assigns dynamically-updating slope parameters to each vector that is stored in the network. Then, when partial / incomplete memories are passed into the network, the model tends to retrieve the corresponding completed memory vector that was stored in the network more quickly and robustly than the Modern Hopfield Network. Like the Modern Hopfield Network, the Fluid Hopfield Network could potentially be incorporated into larger AI models that need to make use of stored memories.
For any questions, please email Shaunak Bhandarkar (shaunakb@stanford.edu). 
