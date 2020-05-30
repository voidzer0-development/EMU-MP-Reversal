# EMU-MP-Reversal
Reverse engineering documentation of the emuMP project. 

| GeneratedName       | ReadableName              | description                                                                      | ver: 0.12.4.6716                                                                      |
|---------------------|---------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| Class1000           | BaseSessionClass          | login, register and session functions                                            | latest edit: 27-4-2020 11:13 GMT+1                                                    |
| Class1013           | TradeController           | trading offers, assort and wear                                                  | Rick: Im coloring everything we need to pack into an Libary in red.                   |
| Class1001           | MainMenuController        | matchmaking, group leadership, lots of shit that should be split in diff classes | Rick: If it is not red its a maybe add.                                               |
| GInterface23        | clientBackendSession      | stores all session info for client                                               |                                                                                       |
| GClass1210          | WeatherClass              | something to do with weather                                                     |                                                                                       |
| Class945            | GroupMatcher              | matching group on backend                                                        |                                                                                       |
| GClass718           | ProfileNetworkLocation    | profid with IP, port and location                                                |                                                                                       |
| GInterface9         | BackendStatusInterface    |                                                                                  |                                                                                       |
| GInterface22        | BackendInterface          |                                                                                  |                                                                                       |
| GClass1224          | MetricEventClass          | timers, game started etc.                                                        |                                                                                       |
| GClass735           | MapLocations              |                                                                                  |                                                                                       |
| GClass743           | MapLocationPath           |                                                                                  |                                                                                       |
| GClass737           | CurrentLocation           | current location?                                                                |                                                                                       |
| Class1048           | NetworkingHandler         | something network client related                                                 |                                                                                       |
| Interface5          | iNetSession               | NetworkClient and onconnect / ondisconnect handlers                              |                                                                                       |
| GInterface73        | iFirearmControls          | firearm controls                                                                 |                                                                                       |
| GInterface85        |                           | XP related interface                                                             |                                                                                       |
| GClass1303          | EntityEffectsClass        | bodypart and effects                                                             |                                                                                       |
| GClass1040          | ProfileStatusManager      | profileID with network info                                                      |                                                                                       |
| GClass391           |                           | player profile token                                                             |                                                                                       |
| GStruct94           | PlayerDataStructure       | data structure of a player!                                                      |                                                                                       |
| GClass1544          | InventoryController       | inventory logic                                                                  |                                                                                       |
| GClass343           |                           | General Player Profile Data (Acc Lifetime)                                       |                                                                                       |
| GInterface164       |                           | item related stuff                                                               |                                                                                       |
| GClass1057          | baseCommonPacket          | Serialized Packets, items; PS: COMMON PACKET XD                                  |                                                                                       |
| GInterface140       | iCharacterEffect          | effects on character                                                             |                                                                                       |
| GInterface42        | iRaidPlayer               | playerinraid interface,GroupId, InfiltrationZone etc                             |                                                                                       |
| GClass203           |                           | ai boss class                                                                    |                                                                                       |
| GClass135           | BossPatrolData            | boss patrolling data                                                             |                                                                                       |
| GClass46            | BotOwnerClass             | bot owner                                                                        |                                                                                       |
| GInterface45        |                           | general object serialzier interface                                              |                                                                                       |
| Class612            | x509CertValidator         | Contains Certificate/ valdiates x509 cert                                        |                                                                                       |
| GClass1127          |                           | Interactable Containers and Items                                                |                                                                                       |
| Class780            | packetDataType            | packet related, size and type                                                    |                                                                                       |
| Interface3          | interfacePacket           | packet something interface                                                       |                                                                                       |
| Interface6          | iGameServer               | game network session interface !!!!!!!! BINGOOOO  [ used by abstractgamesession] |                                                                                       |
| Interface7          | iGameSession              | game session interface [ used by abstractgamesession]                            |                                                                                       |
| GClass878           | GameTime                  |                                                                                  |                                                                                       |
| GClass1062          | skillManager              | skill manager                                                                    |                                                                                       |
| GClass1063          | WeaponSkillStruct         | structure containings weapon skills                                              |                                                                                       |
| GClass1004          |                           | process plr movement packet, animations                                          |                                                                                       |
| GClass1523          |                           | create fragment                                                                  |                                                                                       |
| GClass992           | GenericPacketSerializer   | (generic) serialize a bunch of stuff                                             |                                                                                       |
| GClass390           | ReadJsonFromRequest       | read json from network stream                                                    |                                                                                       |
| GClass871           | ServerLogger              | log server stuff                                                                 |                                                                                       |
| GClass541           | ChatServer                |                                                                                  |                                                                                       |
| GClass542           | ChatInstance              |                                                                                  |                                                                                       |
| GClass1222          | clientMetrics             | metrics that get parsed to bsg                                                   |                                                                                       |
| GClass1088          | gameChangeableSettings    | setting you can change in options menu                                           |                                                                                       |
| GClass746           | ItemWithId                |                                                                                  |                                                                                       |
| GClass867           | BotsController            |                                                                                  |                                                                                       |
| GStruct64           | DisconnectInfoStruct      | disconnect info                                                                  |                                                                                       |
| Class611            | cTarkovVersion            | version num string                                                               |                                                                                       |
| GClass72            | BotGrenadeBehaviour       | bot grenade controller                                                           |                                                                                       |
| Class946            | ExitRaidController        | raid exit                                                                        |                                                                                       |
| GClass23            | BotNavigation             | BotNavigation in botzones                                                        |                                                                                       |
| GInterface105       | iTradeSession             | contains trader info, assort etc.                                                |                                                                                       |
| GClass425           | LoginCallbackClass        | callback from logic func                                                         |                                                                                       |
| GClass730           | GroupManager              | manages grouping and invites                                                     |                                                                                       |
| GClass733           | GroupInvite               | class with group invite data                                                     |                                                                                       |
| GClass731           | GroupPlayer               | class with group player data                                                     |                                                                                       |
| GClass732           | GroupPlayerInfo           |                                                                                  |                                                                                       |
| NetworkGameSession  |                           | Internal game server?, uses igameserver (interface6)                             |                                                                                       |
| NetworkGame         |                           | seems to be a network game instance                                              | server start: // Token: 0x06005E86 RID: 24198 RVA: 0x0028071C File Offset: 0x0027E91C |
| AbstractGameSession | !!!                       | abstract session, contains server logic                                          |                                                                                       |
| Class580            | ResponseMessage           | response in networkgameseesion                                                   |                                                                                       |
| GClass1120          | NetworkLogger             | logs network errors etc.                                                         |                                                                                       |
| Class782            | ConnectionConfigManager   | contains ConnectionConfig stuff                                                  |                                                                                       |
| GClass983           | DeferredDataStream        | channel and message id, memory stream inside, used to pass player info to server |                                                                                       |
| GStruct128          | PlayerNetworkDataStruct   | struct that contains info of player sent over network                            |                                                                                       |
| GStruct138          | SyncPositionPacket        |                                                                                  |                                                                                       |
| GClass451           | PlayerPacketInterpolation |                                                                                  |                                                                                       |
| GStruct127          | PlayerPacketStruct        |                                                                                  |                                                                                       |
| GInterface34        | iInterpolation            |                                                                                  |                                                                                       |
| GStruct165          | pHealthPacket             |                                                                                  |                                                                                       |
| GClass453           |                           | command interp                                                                   |                                                                                       |
| GClass1095          | HardwareIdStruct          |                                                                                  |                                                                                       |
| LocalGame           |                           |                                                                                  |                                                                                       |
| BaseLocalGame       |                           |                                                                                  |                                                                                       |
| GInterface177       | InterfaceInputNode        |                                                                                  |                                                                                       |
| GClass301           | GameEventHandler          |                                                                                  |                                                                                       |
| GClass870           | SpawnPointSelector        |                                                                                  |                                                                                       |
| GClass666           | ExfiltrationManager       |                                                                                  |                                                                                       |
| GClass768           | TimeConversionClass       |                                                                                  |                                                                                       |
| GInterface46        | generalGameInterface      |                                                                                  |                                                                                       |
| GInterface11        | iBotGame                  |                                                                                  |                                                                                       |
| GInterface14        | iBotCreator               |                                                                                  |                                                                                       |
| GClass190           | BotGroupManager           |                                                                                  |                                                                                       |
| GInterface48        | FrameIndexer              |                                                                                  |                                                                                       |
| Class582            | netwByteMsg               |                                                                                  |                                                                                       |
| GClass706           | ExGameServer_struct       |                                                                                  |                                                                                       |
| GClass705           | ExternalGameServer        |                                                                                  |                                                                                       |
| Class169            | BackendCommunicator       |                                                                                  |                                                                                       |
| Class168            | protoBackendCommunicator  |                                                                                  |                                                                                       |
| Class178            | BackendSender             |                                                                                  |                                                                                       |
