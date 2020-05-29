# Transcoding for videoDAC on Livepeer

Here is how to run a Livepeer Transcoder to provide Transcoding capacity in videoDAC's operations in Livepeer's Transcoding Marketplace.

It assumes you have a Mac or Linux computer.

For Mac, download this: https://github.com/livepeer/go-livepeer/releases/download/v0.5.8/livepeer-darwin-amd64.tar.gz

For Linux, download this: https://github.com/livepeer/go-livepeer/releases/download/v0.5.8/livepeer-linux-amd64.tar.gz

Unzip and in Terminal, run the following command from the folder containing the `livepeer` binary:

```
./livepeer -transcoder -orchAddr 54.93.169.248:8935 -orchSecret mango
```

This will register you to perform work for the videoDAC Orchestrator. Contributing your transcoding capacity helps fund @videoDAC.

## Start on boot

If you would like to configure your system to be available for Transcoding when it starts up, follow these instructions:

This guide assumes user is `ubuntu` and that `livepeer` binary exists at `/home/ubuntu/livepeer-linux-amd64/livepeer`

```
cd /etc/systemd/system
sudo wget https://raw.githubusercontent.com/videoDAC/simple-streaming-server/master/systemd/videodac-transcoder.service
sudo systemctl enable videodac-transcoder.service
sudo systemctl start videodac-transcoder.service
```

Your system is now available to provide Transcoding services to videoDAC's Orchestrator on Livepeer's Transcoding Marketplace.

You can tail the logs of the service with this command:
```
sudo journalctl -f --unit=videodac-transcoder.service
```

## videoDAC

You can find out more about the [videoDAC Orchestrator on Livepeer's Protocol Explorer](https://explorer.livepeer.org/accounts/0xdac817294c0c87ca4fa1895ef4b972eade99f2fd/campaign), where you can stake your Livepeer Tokens to the project's node, to help it earn more work in the network, and to earn yourself a share of the rewards.

When Livepeer launched in April 2018, 63% of all Livepeer Token in existence were distributed to Ethereum community. [Watch this video](https://www.youtube.com/watch?v=7vQ7O6qX3eU) to find out more (and turn up the volume!).

![Screenshot from 2020-05-15 21-17-54](https://user-images.githubusercontent.com/2212651/82069976-b9fef500-96f1-11ea-8975-eb28657aa8a2.png)
![Screenshot from 2020-05-15 21-18-00](https://user-images.githubusercontent.com/2212651/82069980-bbc8b880-96f1-11ea-9ab1-9f8616fc5310.png)
![Screenshot from 2020-05-15 21-18-08](https://user-images.githubusercontent.com/2212651/82069985-bcf9e580-96f1-11ea-9318-6e092be428eb.png)
![Screenshot from 2020-05-15 21-18-18](https://user-images.githubusercontent.com/2212651/82069989-bf5c3f80-96f1-11ea-9841-3d1b6e233320.png)

And if you want to know more about Livepeer, here's the [10-minute Primer](https://livepeer.org/primer/).
