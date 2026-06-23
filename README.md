# openavl - WORK IN PROGRESS
Open-Source Automatic Vehicle Location (AVL) System. Cloud-Native, Efficient, and Scalable.

# repos
OpenAVL is made up of multiple projects, which are listed below:

- Cloud: OpenAVL Cloud Stack
- [Hermes](https://github.com/gocarta/hermes): Docker Container for AWS ECS that Proxies UDP Datagrams to SQS
- [Snapshots](https://github.com/gocarta/openavl-snapshots): Serialize DynamoDB Instance to an S3 Blob
- [Daily](https://github.com/gocarta/openavl-daily): Combine Snapshots into 1 Parquet File for each Day
- [History](https://github.com/gocarta/openavl-history): Combine Daily Parquet Files into 1 Large Parquet File
- [Public History](https://github.com/gocarta/openavl-history): Filter the Combined Parquet File by Public GPS Tracks
- [Playback](https://github.com/gocarta/openavl-playback): Replay a full day of GPS Activity
