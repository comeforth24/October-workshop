Task 1.
🟣 Configuring the new HTS token …
↪️ file:///workspace/five-minute-token-launch-challenge/src/script-five-min-token-launch.js:39:18
The token create transaction ID: 0.0.4965236@1728429195.294596457
The token create transaction Hashscan URL: https://hashscan.io/testnet/transaction/0.0.4965236@1728429195.294596457

🟣 Creating the new HTS token …
↪️ file:///workspace/five-minute-token-launch-challenge/src/script-five-min-token-launch.js:68:18
The new token ID: 0.0.4965250

🟣 View the new HTS token on Hashscan …
↪️ file:///workspace/five-minute-token-launch-challenge/src/script-five-min-token-launch.js:80:18
The new token Hashscan URL: https://hashscan.io/testnet/token/0.0.4965250

🎉 5minHtsTokenLaunchChallenge task complete! …

🔢 Summary metrics …

Has completed a task: true
First task completed ID: 5minHtsTokenLaunchChallenge
Time to first task completion: 6min 58.2s
Time to all tasks completion: 6min 58.2s
Total number of task completions: 1

Completed tasks: 1
(1) Task ID: 5minHtsTokenLaunchChallenge (latest)
Time taken to complete (first): 1min 26.8s
Time taken to complete (latest): 16.1s
Errors prior to completion: 1

Attempted but incomplete tasks: 0

View HCS metrics on HashScan:
https://hashscan.io/testnet/topic/0.0.4576382
Using the anonymised key: 679104e43b7add50255baddc7249a689

Task 2
🟣 Creating new HCS topic …
↪️ file:///workspace/hello-future-world-js/hcs/script-hcs-topic.js:46:16
The topic create transaction ID: 0.0.4965267@1728429814.893518238
topicId: 0.0.4965278

🟣 Publish message to HCS topic …
↪️ file:///workspace/hello-future-world-js/hcs/script-hcs-topic.js:71:16
The message submit create transaction ID: 0.0.4965267@1728429818.984781916
topicMsgSeqNum: 1

🟣 View the topic on HashScan …
↪️ file:///workspace/hello-future-world-js/hcs/script-hcs-topic.js:109:16
Paste URL in browser:
https://hashscan.io/testnet/topic/0.0.4965278

🟣 Get topic data from the Hedera Mirror Node …
↪️ file:///workspace/hello-future-world-js/hcs/script-hcs-topic.js:120:16
The topic Hedera Mirror Node API URL:
https://testnet.mirrornode.hedera.com/api/v1/topics/0.0.4965278/messages?encoding=base64&limit=5&order=asc&sequencenumber=1
Number of messages retrieved from this topic: 1
Messages retrieved from this topic: [ '#1: Hello HCS!' ]

🎉 Hello Future World - HCS Topic - complete …

🔢 Summary metrics …

Has completed a task: true
First task completed ID: hcsTopic
Time to first task completion: 5min 15.6s
Time to all tasks completion: 5min 15.6s
Total number of task completions: 1

Completed tasks: 1
(1) Task ID: hcsTopic (latest)
Time taken to complete (first): 17.1s
Time taken to complete (latest): 17.1s
Errors prior to completion: 0

Attempted but incomplete tasks: 0

View HCS metrics on HashScan:
https://hashscan.io/testnet/topic/0.0.4573319
Using the anonymised key: 7c748b5cbfc03c683a975451d4b5c5b5

Task 3
🟣 Reading compiled smart contract artefacts …
↪️ file:///workspace/hello-future-world-js/hscs/script-hscs-smart-contract.js:44:16
Compiled smart contract ABI: [{"inputs":[],"name":"greet","ou …
Compiled smart contract EVM bytecode: 608060405234801561001057600080fd …

🟣 Deploying smart contract …
↪️ file:///workspace/hello-future-world-js/hscs/script-hscs-smart-contract.js:64:16
Smart contract deployment transaction fee 0.14541198 ℏ
Smart contract deployment address: 0x2670f4dD06cb56cEbdeb2343026FA6cCC9DF7bb0
Smart contract deployment Hashscan URL:
https://hashscan.io/testnet/contract/0x2670f4dD06cb56cEbdeb2343026FA6cCC9DF7bb0

🟣 Write data to smart contract …
↪️ file:///workspace/hello-future-world-js/hscs/script-hscs-smart-contract.js:87:16
Smart contract write transaction fee 0.07325661 ℏ
Smart contract write transaction hash 0x63f4ec748bd8ae874d4b3f7849a8714748662b1ebf2025a30ec6a569954c2d27
Smart contract write transaction Hashscan URL:
https://hashscan.io/testnet/transaction/0x63f4ec748bd8ae874d4b3f7849a8714748662b1ebf2025a30ec6a569954c2d27

🟣 Read data from smart contract …
↪️ file:///workspace/hello-future-world-js/hscs/script-hscs-smart-contract.js:106:16
Smart contract read query result: Hello future! - 0.2.1-7487be2e - hscsSC

🎉 Hello Future World - HSCS smart contract - complete …

🔢 Summary metrics …

Has completed a task: true
First task completed ID: hscsSC
Time to first task completion: 11min 14.9s
Time to all tasks completion: 11min 14.9s
Total number of task completions: 1

Completed tasks: 1
(1) Task ID: hscsSC (latest)
Time taken to complete (first): 1min 48.7s
Time taken to complete (latest): 1min 48.7s
Errors prior to completion: 0

Attempted but incomplete tasks: 0

View HCS metrics on HashScan:
https://hashscan.io/testnet/topic/0.0.4573319
Using the anonymised key: 94cec0f98956d57959d11727d878f78e
