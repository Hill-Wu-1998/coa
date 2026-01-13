# The Chosen-Object Attack: Exploiting the Hungarian Matching Loss in Detection Transformers for Fun and Profit
Official PyTorch implementation of the paper "The Chosen-Object Attack: Exploiting the Hungarian Matching Loss in Detection Transformers for Fun and Profit", accepted by IEEE Transactions on Information Forensics and Security (TIFS).

## Overview
This repository provides the code for the Chosen-Object Attack (COA), a novel adversarial attack targeting the fundamental design of Detection Transformers (DETRs).

Unlike traditional detectors that rely on NMS, DETRs use a Hungarian Matching algorithm for one-to-one label assignment. Our work demonstrates that this bipartite matching process introduces a unique vulnerability. By manipulating the cost matrix, COA can make the target object disappear or dislocate the target object.
