# Supply chain & data auditing

## Architecture
UML diagrams (activity, state, sequence and class) can be found in the /project-root/uml directory.

Screenshots of the frontend in action can be found in/project-root/screenshots directory.

### Contract address
Contract is published on the Rinkeby public test network here:

Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 29970676


2_deploy_contracts.js
=====================

   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0xc501688053465b2295991616effe84294c330e2fd3e0428c7eef30c2ffc409b4
   > Blocks: 0            Seconds: 4
   > contract address:    0x3E0C0029bE03f658096300dEc16B507e89Ee44db
   > account:             0x43B5Fc58e4028e40533032C17fc628389Fc9ae7D
   > balance:             18.652400228
   > gas used:            336663
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00336663 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0xce8fc6ee4f6efc787fb683aa2380fb46bdf0e6cd2f56f1814e2228494456e2e3
   > Blocks: 0            Seconds: 12
   > contract address:    0xac7295DFBB9f307a0DD8d3E5Ce16F5375b7C0206
   > account:             0x43B5Fc58e4028e40533032C17fc628389Fc9ae7D
   > balance:             18.649205798
   > gas used:            319443
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00319443 ETH


   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0xe07ea677299ef76e2040bd9fcbca5d64231400e02a760837a20c9ff6fcbf0ff4
   > Blocks: 1            Seconds: 12
   > contract address:    0x2cED3F34371f300B4Eb8Fa6EbcA7603276781553
   > account:             0x43B5Fc58e4028e40533032C17fc628389Fc9ae7D
   > balance:             18.645838688
   > gas used:            336711
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00336711 ETH


   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0x8b556745341b52b496eacdf9c7861f187c033a103e4aa29ca3992c62e280a217
   > Blocks: 1            Seconds: 12
   > contract address:    0x76850e1dD654f0e9BA80b8D7eB89dd0cA230b0aF
   > account:             0x43B5Fc58e4028e40533032C17fc628389Fc9ae7D
   > balance:             18.642471938
   > gas used:            336675
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00336675 ETH


   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0x68caf1cb1a92d35869e4169a4756525bbe7eeb222b7928d1630deabc99d18b98
   > Blocks: 0            Seconds: 12
   > contract address:    0x118314b102585c5b7E1ef1E2F71a3979D7931E1a
   > account:             0x43B5Fc58e4028e40533032C17fc628389Fc9ae7D
   > balance:             18.617543058
   > gas used:            2492888
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02492888 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:           0.0382238 ETH


Summary
=======
> Total deployments:   5
> Final cost:          0.0382238 ETH

### Libraries
No additional libraries were included.

### Versions
Truffle v5.0.2 (core: 5.0.2)
Solidity v0.5.0 (solc-js)
Node v15.5.1

### IPFS
IPFS was not used for this project.