 # To deploy the Go chaincode implementation
 cd ../../test-network
./network.sh down
 ./network.sh up createChannel -c mychannel -ca

./network.sh deployCC -ccn basic -ccp ../asset-transfer-basic/hackathon-javascript/ -ccl javascript