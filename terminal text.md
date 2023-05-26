Skynet@Skynet2 MINGW64 /x/Skynet/Documents/coding bootcamp/VU-VIRT-DATA-PT-02-2023-U-LOLC (main)
$ "C:\Program Files\MongoDB\Server\6.0\bin\mongod.exe"
{"t":{"$date":"2023-05-25T21:19:54.641-05:00"},"s":"I",  "c":"CONTROL",  "id":23285,   "ctx":"-","msg":"Automatically disabling TLS 1.0, to force-enable TLS 1.0 specify --sslDisabledProtocols 'none'"}
{"t":{"$date":"2023-05-25T21:19:54.646-05:00"},"s":"I",  "c":"NETWORK",  "id":4915701, "ctx":"-","msg":"Initialized wire specification","attr":{"spec":{"incomingExternalClient":{"minWireVersion":0,"maxWireVersion":17},"incomingInternalClient":{"minWireVersion":0,"maxWireVersion":17},"outgoing":{"minWireVersion":6,"maxWireVersion":17},"isInternalClient":true}}}
{"t":{"$date":"2023-05-25T21:19:54.655-05:00"},"s":"I",  "c":"NETWORK",  "id":4648602, "ctx":"thread1","msg":"Implicit TCP FastOpen in use."}
{"t":{"$date":"2023-05-25T21:19:54.668-05:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"thread1","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"TenantMigrationDonorService","namespace":"config.tenantMigrationDonors"}}
{"t":{"$date":"2023-05-25T21:19:54.668-05:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"thread1","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"TenantMigrationRecipientService","namespace":"config.tenantMigrationRecipients"}}
{"t":{"$date":"2023-05-25T21:19:54.668-05:00"},"s":"I",  "c":"REPL",     "id":5123008, "ctx":"thread1","msg":"Successfully registered PrimaryOnlyService","attr":{"service":"ShardSplitDonorService","namespace":"config.tenantSplitDonors"}}
{"t":{"$date":"2023-05-25T21:19:54.669-05:00"},"s":"I",  "c":"CONTROL",  "id":5945603, "ctx":"thread1","msg":"Multi threading initialized"}
{"t":{"$date":"2023-05-25T21:19:54.669-05:00"},"s":"I",  "c":"CONTROL",  "id":4615611, "ctx":"initandlisten","msg":"MongoDB starting","attr":{"pid":15564,"port":27017,"dbPath":"X:/data/db/","architecture":"64-bit","host":"Skynet2"}}
{"t":{"$date":"2023-05-25T21:19:54.669-05:00"},"s":"I",  "c":"CONTROL",  "id":23398,   "ctx":"initandlisten","msg":"Target operating system minimum version","attr":{"targetMinOS":"Windows 7/Windows Server 2008 R2"}}
{"t":{"$date":"2023-05-25T21:19:54.670-05:00"},"s":"I",  "c":"CONTROL",  "id":23403,   "ctx":"initandlisten","msg":"Build Info","attr":{"buildInfo":{"version":"6.0.6","gitVersion":"26b4851a412cc8b9b4a18cdb6cd0f9f642e06aa7","modules":[],"allocator":"tcmalloc","environment":{"distmod":"windows","distarch":"x86_64","target_arch":"x86_64"}}}}
{"t":{"$date":"2023-05-25T21:19:54.670-05:00"},"s":"I",  "c":"CONTROL",  "id":51765,   "ctx":"initandlisten","msg":"Operating System","attr":{"os":{"name":"Microsoft Windows 10","version":"10.0 (build 22621)"}}}
{"t":{"$date":"2023-05-25T21:19:54.670-05:00"},"s":"I",  "c":"CONTROL",  "id":21951,   "ctx":"initandlisten","msg":"Options set by command line","attr":{"options":{}}}
{"t":{"$date":"2023-05-25T21:19:54.673-05:00"},"s":"E",  "c":"CONTROL",  "id":20557,   "ctx":"initandlisten","msg":"DBException in initAndListen, terminating","attr":{"error":"NonExistentPath: Data directory X:\\data\\db\\ not found. Create the missing directory or specify another path using (1) the --dbpath command line option, or (2) by adding the 'storage.dbPath' option in the configuration file."}}
{"t":{"$date":"2023-05-25T21:19:54.673-05:00"},"s":"I",  "c":"REPL",     "id":4784900, "ctx":"initandlisten","msg":"Stepping down the ReplicationCoordinator for shutdown","attr":{"waitTimeMillis":15000}}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"REPL",     "id":4794602, "ctx":"initandlisten","msg":"Attempting to enter quiesce mode"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"-",        "id":6371601, "ctx":"initandlisten","msg":"Shutting down the FLE Crud thread pool"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"COMMAND",  "id":4784901, "ctx":"initandlisten","msg":"Shutting down the MirrorMaestro"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"SHARDING", "id":4784902, "ctx":"initandlisten","msg":"Shutting down the WaitForMajorityService"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"NETWORK",  "id":20562,   "ctx":"initandlisten","msg":"Shutdown: going to close listening sockets"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"NETWORK",  "id":4784905, "ctx":"initandlisten","msg":"Shutting down the global connection pool"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"CONTROL",  "id":4784906, "ctx":"initandlisten","msg":"Shutting down the FlowControlTicketholder"}
{"t":{"$date":"2023-05-25T21:19:54.675-05:00"},"s":"I",  "c":"-",        "id":20520,   "ctx":"initandlisten","msg":"Stopping further Flow Control ticket acquisitions."}
{"t":{"$date":"2023-05-25T21:19:54.676-05:00"},"s":"I",  "c":"NETWORK",  "id":4784918, "ctx":"initandlisten","msg":"Shutting down the ReplicaSetMonitor"}
{"t":{"$date":"2023-05-25T21:19:54.676-05:00"},"s":"I",  "c":"SHARDING", "id":4784921, "ctx":"initandlisten","msg":"Shutting down the MigrationUtilExecutor"}
{"t":{"$date":"2023-05-25T21:19:54.676-05:00"},"s":"I",  "c":"ASIO",     "id":22582,   "ctx":"MigrationUtil-TaskExecutor","msg":"Killing all outstanding egress activity."}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"COMMAND",  "id":4784923, "ctx":"initandlisten","msg":"Shutting down the ServiceEntryPoint"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":4784925, "ctx":"initandlisten","msg":"Shutting down free monitoring"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":4784927, "ctx":"initandlisten","msg":"Shutting down the HealthLog"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":4784928, "ctx":"initandlisten","msg":"Shutting down the TTL monitor"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":6278511, "ctx":"initandlisten","msg":"Shutting down the Change Stream Expired Pre-images Remover"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":4784929, "ctx":"initandlisten","msg":"Acquiring the global lock for shutdown"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"-",        "id":4784931, "ctx":"initandlisten","msg":"Dropping the scope cache for shutdown"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":20565,   "ctx":"initandlisten","msg":"Now exiting"}
{"t":{"$date":"2023-05-25T21:19:54.677-05:00"},"s":"I",  "c":"CONTROL",  "id":23138,   "ctx":"initandlisten","msg":"Shutting down","attr":{"exitCode":100}}

Skynet@Skynet2 MINGW64 /x/Skynet/Documents/coding bootcamp/VU-VIRT-DATA-PT-02-2023-U-LOLC (main)
$ mongoimport --type json -d uk_food -c establishments --drop --jsonArray "X:\Skynet\Documents\coding bootcamp\modules\n
osql-challenge\Resources\establishments.json"
bash: mongoimport: command not found

Skynet@Skynet2 MINGW64 /x/Skynet/Documents/coding bootcamp/VU-VIRT-DATA-PT-02-2023-U-LOLC (main)
$ PATH=$PATH:"/C/Program Files/MongoDB/Tools/100/bin"

Skynet@Skynet2 MINGW64 /x/Skynet/Documents/coding bootcamp/VU-VIRT-DATA-PT-02-2023-U-LOLC (main)
$ export PATH=$PATH:"/C/Program Files/MongoDB/Tools/100/bin"

Skynet@Skynet2 MINGW64 /x/Skynet/Documents/coding bootcamp/VU-VIRT-DATA-PT-02-2023-U-LOLC (main)
$ mongoimport --type json -d uk_food -c establishments --drop --jsonArray "X:\Skynet\Documents\coding bootcamp\modules\nosql-challenge\Resources\establishments.json"
2023-05-25T21:25:12.787-0500    connected to: mongodb://localhost/
2023-05-25T21:25:12.788-0500    dropping: uk_food.establishments
2023-05-25T21:25:15.788-0500    [#####################...] uk_food.establishments       35.1MB/39.3MB (89.2%)
2023-05-25T21:25:16.186-0500    [########################] uk_food.establishments       39.3MB/39.3MB (100.0%)
2023-05-25T21:25:16.186-0500    39779 document(s) imported successfully. 0 document(s) failed to import.

Skynet@Skynet2 MINGW64 /x/Skynet/Documents/coding bootcamp/VU-VIRT-DATA-PT-02-2023-U-LOLC (main)
$