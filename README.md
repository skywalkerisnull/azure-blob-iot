# azure-blob-iot
Using the Azure Blob IoT via docker-compose for rapid testing.

## Background
I found that setting up Azure IoT Hub just to test Azure Blob IoT was a long task that could be simplified by using a simple docker-compose

## Steps to deploy for testing
1. Modify the deploy.env key. I have used this site to generate a 64 byte key: https://generate.plus/en/base64
2. Run `docker-compose up`
3. Use Azure Blob Storage Explorer with the connection string: `DefaultEndpointsProtocol=http;AccountName=blobtest;AccountKey=C01YNoMR7osMHLNaPOZyKemmcwel/V+4dYacXLQTgmwNFUKP2KjUZPucLICI3EzRj38zvFEg4eOTrTKAp2omWg==;BlobEndpoint=http://localhost:11002/blobtest;` 
