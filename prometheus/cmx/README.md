## To run

docker build --tag cmx-remote-storage-adapter:1.0 .

docker run --publish 9201:9201 --name cmx-remote-storage-adapter cmx-remote-storage-adapter:1.0
