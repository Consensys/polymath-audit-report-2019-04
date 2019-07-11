### Ethlint/Solium
```console
Solium version 1.2.2
```

### Output
```console
contracts/ModuleRegistry.sol
  44:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/STRGetter.sol
  47:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/SecurityTokenRegistry.sol
  292:8     warning    Provide an error message for require().                                    error-reason
  564:4     error      "generateNewSecurityToken": Avoid assigning to function parameters.        security/no-assign-params
  564:4     error      "generateNewSecurityToken": Avoid assigning to function parameters.        security/no-assign-params
  589:8     warning    Assignment operator must have exactly single space on both sides of it.    operator-whitespace
  594:65    warning    Avoid using 'now' (alias to 'block.timestamp').                            security/no-block-members
  598:65    warning    Avoid using 'now' (alias to 'block.timestamp').                            security/no-block-members
  630:8     warning    Assignment operator must have exactly single space on both sides of it.    operator-whitespace
  633:62    warning    Avoid using 'now' (alias to 'block.timestamp').                            security/no-block-members

contracts/datastore/DataStore.sol
  18:16    error    Only use indent of 12 spaces.    indentation

contracts/datastore/DataStoreProxy.sol
  22:16    error    Only use indent of 12 spaces.    indentation

contracts/external/oraclizeAPI.sol
  27:0       warning    Line exceeds the limit of 145 characters                                                             max-len
  31:110     warning    Line exceeds the limit of 145 characters                                                             max-len
  31:110     error      Only use indent of 4 spaces.                                                                         indentation
  46:4       warning    Line exceeds the limit of 145 characters                                                             max-len
  47:4       warning    Line exceeds the limit of 145 characters                                                             max-len
  48:4       warning    Line exceeds the limit of 145 characters                                                             max-len
  96:8       error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  131:8      error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  139:12     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  146:8      error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  166:8      error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  188:8      error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  312:8      warning    Provide an error message for require().                                                              error-reason
  314:8      warning    Provide an error message for require().                                                              error-reason
  319:6      error      Only use indent of 8 spaces.                                                                         indentation
  320:6      error      Code is unreachable.                                                                                 security/no-unreachable-code
  320:6      error      Only use indent of 8 spaces.                                                                         indentation
  372:6      error      Only use indent of 8 spaces.                                                                         indentation
  373:6      error      Code is unreachable.                                                                                 security/no-unreachable-code
  373:6      error      Only use indent of 8 spaces.                                                                         indentation
  373:13     error      Only use indent of 8 spaces.                                                                         indentation
  373:22     error      Only use indent of 8 spaces.                                                                         indentation
  376:70     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  380:86     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  384:87     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  392:104    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  400:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  400:120    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  408:103    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  411:11     error      Only use indent of 12 spaces.                                                                        indentation
  416:109    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  424:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  424:126    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  432:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  432:142    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  440:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  440:125    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  448:90     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  457:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  466:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  466:123    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  475:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  484:91     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  490:108    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  496:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  496:124    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  502:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  508:91     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  515:108    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  522:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  522:124    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  529:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  536:91     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  544:108    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  552:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  552:124    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  560:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  568:91     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  577:108    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  586:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  586:124    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  595:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  604:91     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  614:108    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  624:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  624:124    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  634:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  644:89     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  653:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  662:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  662:122    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  671:105    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  680:90     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  686:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  692:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  692:123    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  698:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  704:90     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  711:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  718:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  718:123    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  725:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  732:90     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  740:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  748:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  748:123    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  756:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  764:90     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  773:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  782:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  782:123    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  791:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  800:90     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  810:107    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  820:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  820:123    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  830:106    warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  840:57     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  845:46     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  849:45     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  850:8      error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  855:68     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  859:66     warning    Visibility modifier "internal" should come before other modifiers.                                   visibility-first
  946:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  950:4      warning    Line exceeds the limit of 145 characters                                                             max-len
  982:4      error      "safeParseInt": Avoid assigning to function parameters.                                              security/no-assign-params
  989:19     error      Only use indent of 20 spaces.                                                                        indentation
  995:35     error      'More than one decimal encountered in string!': String literal must be quoted with double quotes.    quotes
  1011:4     error      "parseInt": Avoid assigning to function parameters.                                                  security/no-assign-params
  1018:19    error      Only use indent of 20 spaces.                                                                        indentation
  1036:4     error      "uint2str": Avoid assigning to function parameters.                                                  security/no-assign-params
  1079:4     error      "oraclize_newRandomDSQuery": Avoid assigning to function parameters.                                 security/no-assign-params
  1080:8     warning    Provide an error message for require().                                                              error-reason
  1087:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1099:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1107:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1137:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1167:8     warning    Line exceeds the limit of 145 characters                                                             max-len
  1177:4     warning    Line exceeds the limit of 145 characters                                                             max-len
  1191:8     warning    Provide an error message for require().                                                              error-reason
  1192:29    warning    Single space should be either on both sides of '<' or not at all.                                    operator-whitespace
  1200:4     warning    Line exceeds the limit of 145 characters                                                             max-len
  1222:8     warning    Line exceeds the limit of 145 characters                                                             max-len
  1240:4     warning    Line exceeds the limit of 145 characters                                                             max-len
  1242:8     warning    Provide an error message for require().                                                              error-reason
  1246:12    error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1270:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1296:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly
  1328:8     error      Avoid using Inline Assembly.                                                                         security/no-inline-assembly

contracts/interfaces/IDataStore.sol
  34:73    warning    There should be no whitespace or comments before the semicolon.    semicolon-whitespace

contracts/interfaces/ISecurityToken.sol
  66:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/interfaces/token/IERC1410.sol
  11:4    warning    Line exceeds the limit of 145 characters    max-len
  12:4    warning    Line exceeds the limit of 145 characters    max-len
  28:4    warning    Line exceeds the limit of 145 characters    max-len
  49:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/libraries/BokkyPooBahsDateTimeLibrary.sol
  57:8     warning    Provide an error message for require().                                              error-reason
  62:16    warning    Operator "+" should be on the line where left side of the Binary expression ends.    operator-whitespace
  62:24    warning    Operator "-" should be on the line where left side of the Binary expression ends.    operator-whitespace
  62:57    warning    Operator "+" should be on the line where left side of the Binary expression ends.    operator-whitespace
  62:60    warning    Operator "-" should be on the line where left side of the Binary expression ends.    operator-whitespace
  62:62    warning    Operator "-" should be on the line where left side of the Binary expression ends.    operator-whitespace
  67:0     error      Only use indent of 8 spaces.                                                         indentation
  217:8    warning    Provide an error message for require().                                              error-reason
  232:8    warning    Provide an error message for require().                                              error-reason
  236:8    warning    Provide an error message for require().                                              error-reason
  240:8    warning    Provide an error message for require().                                              error-reason
  244:8    warning    Provide an error message for require().                                              error-reason
  248:8    warning    Provide an error message for require().                                              error-reason
  262:8    warning    Provide an error message for require().                                              error-reason
  277:8    warning    Provide an error message for require().                                              error-reason
  281:8    warning    Provide an error message for require().                                              error-reason
  285:8    warning    Provide an error message for require().                                              error-reason
  289:8    warning    Provide an error message for require().                                              error-reason
  293:8    warning    Provide an error message for require().                                              error-reason
  297:8    warning    Provide an error message for require().                                              error-reason
  309:8    warning    Provide an error message for require().                                              error-reason
  321:8    warning    Provide an error message for require().                                              error-reason
  325:8    warning    Provide an error message for require().                                              error-reason
  329:8    warning    Provide an error message for require().                                              error-reason
  333:8    warning    Provide an error message for require().                                              error-reason

contracts/libraries/TokenLib.sol
  35:4      warning    Line exceeds the limit of 145 characters                          max-len
  90:8      error      Avoid using Inline Assembly.                                      security/no-inline-assembly
  109:20    error      Only use indent of 16 spaces.                                     indentation
  110:20    error      Only use indent of 16 spaces.                                     indentation
  111:20    error      Only use indent of 16 spaces.                                     indentation
  117:35    error      Only use indent of 12 spaces.                                     indentation
  259:4     warning    Line exceeds the limit of 145 characters                          max-len
  321:4     error      "adjustInvestorCount": Avoid assigning to function parameters.    security/no-assign-params
  321:4     error      "adjustInvestorCount": Avoid assigning to function parameters.    security/no-assign-params
  376:69    warning    Avoid using 'now' (alias to 'block.timestamp').                   security/no-block-members
  416:4     error      "verifyTransfer": Avoid assigning to function parameters.         security/no-assign-params
  416:4     error      "verifyTransfer": Avoid assigning to function parameters.         security/no-assign-params

contracts/libraries/Util.sol
  77:10    error    Only use indent of 12 spaces.    indentation

contracts/libraries/VersionUtils.sol
  10:8    warning    Provide an error message for require().     error-reason
  11:8    warning    Provide an error message for require().     error-reason
  22:8    warning    Provide an error message for require().     error-reason
  23:8    warning    Provide an error message for require().     error-reason
  71:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/libraries/VolumeRestrictionLib.sol
  15:4     warning    Line exceeds the limit of 145 characters           max-len
  78:74    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  80:84    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

contracts/mocks/Dummy/DummySTOFactory.sol
  48:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/mocks/FunctionSigClash1.sol
  3:27    warning    Code contains empty block    no-empty-blocks

contracts/mocks/FunctionSigClash2.sol
  3:27    warning    Code contains empty block    no-empty-blocks

contracts/mocks/MockBurnFactory.sol
  40:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/mocks/MockCountTransferManager.sol
  21:8    warning    Provide an error message for require().    error-reason

contracts/mocks/MockRedemptionManager.sol
  13:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/Dividend/DividendCheckpoint.sol
  284:34    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  395:4     warning    Line exceeds the limit of 145 characters           max-len

contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpoint.sol
  25:4     warning    Line exceeds the limit of 145 characters    max-len
  165:8    warning    Provide an error message for require().     error-reason

contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpointFactory.sol
  47:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/Dividend/ERC20/ERC20DividendCheckpointProxy.sol
  12:0    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/Dividend/Ether/EtherDividendCheckpoint.sol
  130:8    warning    Provide an error message for require().    error-reason
  131:8    warning    Provide an error message for require().    error-reason

contracts/modules/Checkpoint/Dividend/Ether/EtherDividendCheckpointFactory.sol
  47:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/ICheckpoint.sol
  1:0    error    Inconsistent line-break style    linebreak-style

contracts/modules/Checkpoint/Voting/PLCR/PLCRVotingCheckpoint.sol
  55:28     warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  107:30    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  187:4     warning    Line exceeds the limit of 145 characters           max-len
  221:12    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  240:12    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  242:17    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  242:41    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  244:18    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  244:41    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  246:17    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

contracts/modules/Checkpoint/Voting/PLCR/PLCRVotingCheckpointFactory.sol
  49:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpoint.sol
  56:26     warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  57:59     warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  95:4      warning    Line exceeds the limit of 145 characters           max-len
  97:30     warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  113:16    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  113:43    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  139:4     warning    Line exceeds the limit of 145 characters           max-len
  172:23    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpointFactory.sol
  48:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/Voting/Transparent/WeightedVoteCheckpointProxy.sol
  12:0    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Checkpoint/Voting/VotingCheckpoint.sol
  35:8    warning    Provide an error message for require().    error-reason

contracts/modules/Experimental/Mixed/ScheduledCheckpoint.sol
  60:29     warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  142:8     warning    Line exceeds the limit of 145 characters           max-len
  156:33    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  162:26    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  165:82    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  168:82    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  171:84    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  175:83    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

contracts/modules/Experimental/TransferManager/KYCTransferManager.sol
  40:8    warning    Assignment operator must have exactly single space on both sides of it.    operator-whitespace

contracts/modules/Experimental/TransferManager/SignedTransferManager.sol
  50:55      warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  50:74      warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  100:123    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members
  100:142    warning    Avoid using 'now' (alias to 'block.timestamp').    security/no-block-members

contracts/modules/Experimental/TransferManager/SignedTransferManagerFactory.sol
  39:5    error      Only use indent of 4 spaces.                indentation
  40:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/Module.sol
  78:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/PermissionManager/GeneralPermissionManagerFactory.sol
  48:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/STO/Capped/CappedSTO.sol
  166:4    error    "_processTx": Avoid assigning to function parameters.    security/no-assign-params

contracts/modules/STO/Capped/CappedSTOFactory.sol
  33:8    warning    Line exceeds the limit of 145 characters    max-len
  49:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/STO/PreSale/PreSaleSTOFactory.sol
  47:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/STO/USDTiered/USDTieredSTO.sol
  325:8    warning    Provide an error message for require().     error-reason
  360:8    warning    Line exceeds the limit of 145 characters    max-len
  378:4    warning    Line exceeds the limit of 145 characters    max-len
  395:4    warning    Line exceeds the limit of 145 characters    max-len
  396:8    warning    Line exceeds the limit of 145 characters    max-len
  408:4    warning    Line exceeds the limit of 145 characters    max-len
  728:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/STO/USDTiered/USDTieredSTOFactory.sol
  50:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/STO/USDTiered/USDTieredSTOProxy.sol
  20:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/STO/USDTiered/USDTieredSTOStorage.sol
  8:4    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/TransferManager/BTM/BlacklistTransferManager.sol
  119:49    warning    Avoid using 'now' (alias to 'block.timestamp').                      security/no-block-members
  169:8     warning    Line exceeds the limit of 145 characters                             max-len
  182:4     warning    Line exceeds the limit of 145 characters                             max-len
  208:8     warning    Line exceeds the limit of 145 characters                             max-len
  235:60    warning    Single space should be either on both sides of '-' or not at all.    operator-whitespace
  334:8     warning    Line exceeds the limit of 145 characters                             max-len
  338:35    warning    Single space should be either on both sides of '-' or not at all.    operator-whitespace
  348:34    warning    Single space should be either on both sides of '-' or not at all.    operator-whitespace
  405:30    warning    Avoid using 'now' (alias to 'block.timestamp').                      security/no-block-members
  406:8     warning    Provide an error message for require().                              error-reason
  443:8     warning    Line exceeds the limit of 145 characters                             max-len

contracts/modules/TransferManager/BTM/BlacklistTransferManagerFactory.sol
  44:8    warning    Line exceeds the limit of 145 characters    max-len

contracts/modules/TransferManager/CTM/CountTransferManagerFactory.sol
  45:8    warning    Line exceeds the limit of 145 characters    max-len
```
