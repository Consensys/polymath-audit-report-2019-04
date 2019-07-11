### Truffle-Suite
```console
#> npx truffle version
Truffle v5.0.13 (core: 5.0.13)
Solidity - native (solc-js)
Node v11.6.0
Web3.js v1.0.0-beta.37
```

### Output
```console
Compiling your contracts...
===========================
> Compiling ./contracts/FeatureRegistry.sol
> Compiling ./contracts/Migrations.sol
> Compiling ./contracts/ModuleRegistry.sol
> Compiling ./contracts/Pausable.sol
> Compiling ./contracts/PolymathRegistry.sol
> Compiling ./contracts/ReclaimTokens.sol
> Compiling ./contracts/STRGetter.sol
> Compiling ./contracts/SecurityTokenRegistry.sol
> Compiling ./contracts/datastore/DataStore.sol
> Compiling ./contracts/datastore/DataStoreFactory.sol
> Compiling ./contracts/datastore/DataStoreProxy.sol
> Compiling ./contracts/datastore/DataStoreStorage.sol
> Compiling ./contracts/external/IMedianizer.sol
> Compiling ./contracts/external/oraclizeAPI.sol
> Compiling ./contracts/helpers/PolyToken.sol
> Compiling ./contracts/interfaces/IBoot.sol
> Compiling ./contracts/interfaces/ICheckPermission.sol
> Compiling ./contracts/interfaces/IDataStore.sol
> Compiling ./contracts/interfaces/IFeatureRegistry.sol
> Compiling ./contracts/interfaces/IModule.sol
> Compiling ./contracts/interfaces/IModuleFactory.sol
> Compiling ./contracts/interfaces/IModuleRegistry.sol
> Compiling ./contracts/interfaces/IOracle.sol
> Compiling ./contracts/interfaces/IOwnable.sol
> Compiling ./contracts/interfaces/IPoly.sol
> Compiling ./contracts/interfaces/IPolymathRegistry.sol
> Compiling ./contracts/interfaces/ISTFactory.sol
> Compiling ./contracts/interfaces/ISTO.sol
> Compiling ./contracts/interfaces/ISecurityToken.sol
> Compiling ./contracts/interfaces/ISecurityTokenRegistry.sol
> Compiling ./contracts/interfaces/ITransferManager.sol
> Compiling ./contracts/interfaces/IUSDTieredSTOProxy.sol
> Compiling ./contracts/interfaces/IUpgradableTokenFactory.sol
> Compiling ./contracts/interfaces/IVoting.sol
> Compiling ./contracts/interfaces/token/IERC1410.sol
> Compiling ./contracts/interfaces/token/IERC1594.sol
> Compiling ./contracts/interfaces/token/IERC1643.sol
> Compiling ./contracts/interfaces/token/IERC1644.sol
> Compiling ./contracts/libraries/BokkyPooBahsDateTimeLibrary.sol
> Compiling ./contracts/libraries/DecimalMath.sol
> Compiling ./contracts/libraries/Encoder.sol
> Compiling ./contracts/libraries/KindMath.sol
> Compiling ./contracts/libraries/TokenLib.sol
> Compiling ./contracts/libraries/Util.sol
> Compiling ./contracts/libraries/VersionUtils.sol
> Compiling ./contracts/libraries/VolumeRestrictionLib.sol
> Compiling ./contracts/mocks/Dummy/DummySTO.sol
> Compiling ./contracts/mocks/Dummy/DummySTOFactory.sol
> Compiling ./contracts/mocks/Dummy/DummySTOProxy.sol
> Compiling ./contracts/mocks/Dummy/DummySTOStorage.sol
> Compiling ./contracts/mocks/FunctionSigClash1.sol
> Compiling ./contracts/mocks/FunctionSigClash2.sol
> Compiling ./contracts/mocks/MockBurnFactory.sol
> Compiling ./contracts/mocks/MockCountTransferManager.sol
> Compiling ./contracts/mocks/MockFactory.sol
> Compiling ./contracts/mocks/MockModuleRegistry.sol
> Compiling ./contracts/mocks/MockOracle.sol
> Compiling ./contracts/mocks/MockPolyOracle.sol
> Compiling ./contracts/mocks/MockRedemptionManager.sol
> Compiling ./contracts/mocks/MockSTGetter.sol
> Compiling ./contracts/mocks/MockSecurityTokenLogic.sol
> Compiling ./contracts/mocks/MockWrongTypeFactory.sol
> Compiling ./contracts/mocks/PolyTokenFaucet.sol
> Compiling ./contracts/mocks/SecurityTokenMock.sol
> Compiling ./contracts/mocks/SecurityTokenRegistryMock.sol
> Compiling ./contracts/mocks/TestSTOFactory.sol
> Compiling ./contracts/modules/Burn/IBurn.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/DividendCheckpoint.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpoint.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpointFactory.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpointProxy.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpointStorage.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/Ether/EtherDividendCheckpoint.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/Ether/EtherDividendCheckpointFactory.sol
> Compiling ./contracts/modules/Checkpoint/Dividend/Ether/EtherDividendCheckpointProxy.sol
> Compiling ./contracts/modules/Checkpoint/ICheckpoint.sol
> Compiling ./contracts/modules/Checkpoint/Voting/PLCR/PLCRVotingCheckpoint.sol
> Compiling ./contracts/modules/Checkpoint/Voting/PLCR/PLCRVotingCheckpointFactory.sol
> Compiling ./contracts/modules/Checkpoint/Voting/PLCR/PLCRVotingCheckpointProxy.sol
> Compiling ./contracts/modules/Checkpoint/Voting/PLCR/PLCRVotingCheckpointStorage.sol
> Compiling ./contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpoint.sol
> Compiling ./contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpointFactory.sol
> Compiling ./contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpointProxy.sol
> Compiling ./contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpointStorage.sol
> Compiling ./contracts/modules/Checkpoint/Voting/VotingCheckpoint.sol
> Compiling ./contracts/modules/Experimental/Burn/TrackedRedemption.sol
> Compiling ./contracts/modules/Experimental/Burn/TrackedRedemptionFactory.sol
> Compiling ./contracts/modules/Experimental/Mixed/ScheduledCheckpoint.sol
> Compiling ./contracts/modules/Experimental/Mixed/ScheduledCheckpointFactory.sol
> Compiling ./contracts/modules/Experimental/TransferManager/KYCTransferManager.sol
> Compiling ./contracts/modules/Experimental/TransferManager/KYCTransferManagerFactory.sol
> Compiling ./contracts/modules/Experimental/TransferManager/SignedTransferManager.sol
> Compiling ./contracts/modules/Experimental/TransferManager/SignedTransferManagerFactory.sol
> Compiling ./contracts/modules/Module.sol
> Compiling ./contracts/modules/ModuleFactory.sol
> Compiling ./contracts/modules/PermissionManager/GeneralPermissionManager.sol
> Compiling ./contracts/modules/PermissionManager/GeneralPermissionManagerFactory.sol
> Compiling ./contracts/modules/PermissionManager/GeneralPermissionManagerProxy.sol
> Compiling ./contracts/modules/PermissionManager/GeneralPermissionManagerStorage.sol
> Compiling ./contracts/modules/PermissionManager/IPermissionManager.sol
> Compiling ./contracts/modules/STO/Capped/CappedSTO.sol
> Compiling ./contracts/modules/STO/Capped/CappedSTOFactory.sol
> Compiling ./contracts/modules/STO/Capped/CappedSTOProxy.sol
> Compiling ./contracts/modules/STO/Capped/CappedSTOStorage.sol
> Compiling ./contracts/modules/STO/PreSale/PreSaleSTO.sol
> Compiling ./contracts/modules/STO/PreSale/PreSaleSTOFactory.sol
> Compiling ./contracts/modules/STO/PreSale/PreSaleSTOProxy.sol
> Compiling ./contracts/modules/STO/PreSale/PreSaleSTOStorage.sol
> Compiling ./contracts/modules/STO/STO.sol
> Compiling ./contracts/modules/STO/USDTiered/USDTieredSTO.sol
> Compiling ./contracts/modules/STO/USDTiered/USDTieredSTOFactory.sol
> Compiling ./contracts/modules/STO/USDTiered/USDTieredSTOProxy.sol
> Compiling ./contracts/modules/STO/USDTiered/USDTieredSTOStorage.sol
> Compiling ./contracts/modules/TransferManager/BTM/BlacklistTransferManager.sol
> Compiling ./contracts/modules/TransferManager/BTM/BlacklistTransferManagerFactory.sol
> Compiling ./contracts/modules/TransferManager/BTM/BlacklistTransferManagerProxy.sol
> Compiling ./contracts/modules/TransferManager/BTM/BlacklistTransferManagerStorage.sol
> Compiling ./contracts/modules/TransferManager/CTM/CountTransferManager.sol
> Compiling ./contracts/modules/TransferManager/CTM/CountTransferManagerFactory.sol
> Compiling ./contracts/modules/TransferManager/CTM/CountTransferManagerProxy.sol
> Compiling ./contracts/modules/TransferManager/CTM/CountTransferManagerStorage.sol
> Compiling ./contracts/modules/TransferManager/GTM/GeneralTransferManager.sol
> Compiling ./contracts/modules/TransferManager/GTM/GeneralTransferManagerFactory.sol
> Compiling ./contracts/modules/TransferManager/GTM/GeneralTransferManagerProxy.sol
> Compiling ./contracts/modules/TransferManager/GTM/GeneralTransferManagerStorage.sol
> Compiling ./contracts/modules/TransferManager/LTM/LockUpTransferManager.sol
> Compiling ./contracts/modules/TransferManager/LTM/LockUpTransferManagerFactory.sol
> Compiling ./contracts/modules/TransferManager/LTM/LockUpTransferManagerProxy.sol
> Compiling ./contracts/modules/TransferManager/LTM/LockUpTransferManagerStorage.sol
> Compiling ./contracts/modules/TransferManager/MATM/ManualApprovalTransferManager.sol
> Compiling ./contracts/modules/TransferManager/MATM/ManualApprovalTransferManagerFactory.sol
> Compiling ./contracts/modules/TransferManager/MATM/ManualApprovalTransferManagerProxy.sol
> Compiling ./contracts/modules/TransferManager/MATM/ManualApprovalTransferManagerStorage.sol
> Compiling ./contracts/modules/TransferManager/PTM/PercentageTransferManager.sol
> Compiling ./contracts/modules/TransferManager/PTM/PercentageTransferManagerFactory.sol
> Compiling ./contracts/modules/TransferManager/PTM/PercentageTransferManagerProxy.sol
> Compiling ./contracts/modules/TransferManager/PTM/PercentageTransferManagerStorage.sol
> Compiling ./contracts/modules/TransferManager/TransferManager.sol
> Compiling ./contracts/modules/TransferManager/VRTM/VolumeRestrictionTM.sol
> Compiling ./contracts/modules/TransferManager/VRTM/VolumeRestrictionTMFactory.sol
> Compiling ./contracts/modules/TransferManager/VRTM/VolumeRestrictionTMProxy.sol
> Compiling ./contracts/modules/TransferManager/VRTM/VolumeRestrictionTMStorage.sol
> Compiling ./contracts/modules/UpgradableModuleFactory.sol
> Compiling ./contracts/modules/Wallet/VestingEscrowWallet.sol
> Compiling ./contracts/modules/Wallet/VestingEscrowWalletFactory.sol
> Compiling ./contracts/modules/Wallet/VestingEscrowWalletProxy.sol
> Compiling ./contracts/modules/Wallet/VestingEscrowWalletStorage.sol
> Compiling ./contracts/modules/Wallet/Wallet.sol
> Compiling ./contracts/oracles/MakerDAOOracle.sol
> Compiling ./contracts/oracles/PolyOracle.sol
> Compiling ./contracts/oracles/StableOracle.sol
> Compiling ./contracts/proxy/ModuleRegistryProxy.sol
> Compiling ./contracts/proxy/OwnedProxy.sol
> Compiling ./contracts/proxy/OwnedUpgradeabilityProxy.sol
> Compiling ./contracts/proxy/Proxy.sol
> Compiling ./contracts/proxy/SecurityTokenRegistryProxy.sol
> Compiling ./contracts/proxy/UpgradeabilityProxy.sol
> Compiling ./contracts/storage/EternalStorage.sol
> Compiling ./contracts/storage/modules/Checkpoint/Dividend/DividendCheckpointStorage.sol
> Compiling ./contracts/storage/modules/Checkpoint/Voting/VotingCheckpointStorage.sol
> Compiling ./contracts/storage/modules/ModuleStorage.sol
> Compiling ./contracts/storage/modules/STO/ISTOStorage.sol
> Compiling ./contracts/storage/modules/STO/STOStorage.sol
> Compiling ./contracts/tokens/OZStorage.sol
> Compiling ./contracts/tokens/STFactory.sol
> Compiling ./contracts/tokens/STGetter.sol
> Compiling ./contracts/tokens/SecurityToken.sol
> Compiling ./contracts/tokens/SecurityTokenProxy.sol
> Compiling ./contracts/tokens/SecurityTokenStorage.sol
> Compiling openzeppelin-solidity/contracts/cryptography/ECDSA.sol
> Compiling openzeppelin-solidity/contracts/math/Math.sol
> Compiling openzeppelin-solidity/contracts/math/SafeMath.sol
> Compiling openzeppelin-solidity/contracts/ownership/Ownable.sol
> Compiling openzeppelin-solidity/contracts/token/ERC20/ERC20.sol
> Compiling openzeppelin-solidity/contracts/token/ERC20/IERC20.sol
> Compiling openzeppelin-solidity/contracts/utils/Address.sol
> Compiling openzeppelin-solidity/contracts/utils/ReentrancyGuard.sol

    > compilation warnings encountered:

./contracts/external/oraclizeAPI.sol:320:7: Warning: Unreachable code.
      _networkID; // silence the warning and remain backwards compatible
      ^--------^
,./contracts/external/oraclizeAPI.sol:373:7: Warning: Unreachable code.
      _myid; _result; _proof; // Silence compiler warnings
      ^--------------------^
,./contracts/external/oraclizeAPI.sol:371:5: Warning: Function state mutability can be restricted to pure
    function __callback(bytes32 _myid, string memory _result, bytes memory _proof) public {
    ^ (Relevant source part starts here and spans across multiple lines).

> Artifacts written to ./build/contracts
> Compiled successfully using:
   - solc: 0.5.3+commit.10d17f24.Darwin.appleclang

```
