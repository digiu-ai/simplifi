# Simplifi

## Project Name: Simplifi

## Short description:

Simplifi - Fully decentralized crooss-chain Dex protocol implemnting idea of heterogeneous liquidity based on Chainlink adapters as a cross-chain bridge hosting.
Protocol is designed to serve any smart-contract driven blockchains. Current Simplifi version runs on Ethereum and BSC.

## Project features:

#### Cross-chain Swaps
Users can seamlessly swap from one coin to another due to synths tokens pegged to original asset on original chain

#### Cross-chain liquidity
Liquidity provider could add and withdraw liquidity into crosschain pairs and earn fees from crosschain swaps 

#### Cross-chain Bridge
Decentralized relayer nodes network serving cross-chain contract state reads and writes requests.

### Usage

clone repo
``
git clone --recursive git@github.com:digiu-ai/simplifi.git
``

checkout all submodules to main branch
``
git submodule foreach -q --recursive 'git checkout $(git config -f $toplevel/.gitmodules submodule.$name.branch || echo main)'
``
init git summary
``
git config --global status.submoduleSummary true
``
change directory to bridge 
``
cd simplifi-bridge
``
and test it according to README


