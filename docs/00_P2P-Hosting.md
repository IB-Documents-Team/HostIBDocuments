# Peer-To-Peer Hosting

The IB Documents project uses [Dat Project](https://dat.foundation/) for P2P distribution, as it supports versioning (meaning you don't have to download everything again when the website is updated) and is faster for downloading only single files.

## Download IB resources from Dat

1. Install [Beaker Browser](https://beakerbrowser.com/install/).
2. Open Beaker Browser and paste dat://xxxxxx into your search bar (press enter after). Now you can view browse normally like on [ib.redditor.website](http://ib.redditor.website). Be patient, the first visit may take some time.


## Seeding

To help distribute and seed downloads you would need 50GB of free storage space on a computer. Seeding makes downloading with a distributed system faster for everyone and means the files can not be taken down with a copyright notice. 

1. Install [NodeJS](https://nodejs.org/en). Select the LTS version. Restart your computer after the installation.
2. Open up a command prompt (Windows) or terminal (Mac/Linux) and enter the following command: `npm install -g dat`
3. Run the command `dat -h`. If you get any output, you have installed Dat succesfully.
4. To start seeding and downloading all the IB resources run the command: `dat sync dat://xxxxx`.

## Disclaimer

This file is merely for instructional purposes. We do not _necessarily_ endorse the download or seeding of any documents not published directly by the IB.  