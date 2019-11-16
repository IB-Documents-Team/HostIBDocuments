# Peer-To-Peer Hosting

The IB Documents project uses the [Dat Project](https://dat.foundation/) for P2P
 distribution, as it supports versioning (meaning you don't have to download 
 everything again when the website is updated) and is faster for downloading 
 only single files.

## Download IB resources from Dat

## Beaker Browser (easy)

1. Install [Beaker Browser](https://beakerbrowser.com/install/).
2. Open Beaker Browser and paste 
`dat://1d57389d37f2da4722edb4d4399fac878b93b7e2a6a69b9845774a2325e66b11/` into 
your search bar (press enter 
after). Now you can view browse normally like on 
[ibdocuments.com](https://ibdocuments.com/). Be patient, the first visit may 
take some time.

## Terminal (harder)

1. Install [NodeJS](https://nodejs.org/en). Select the LTS version. Restart 
your computer after the installation.
2. Open up a terminal window and install `dat` with `npm install -g dat`.
3. Run the command `dat -h`. If you get any output, you have installed Dat 
succesfully.
4. To start a local version of the website run 
`dat dat://1d57389d37f2da4722edb4d4399fac878b93b7e2a6a69b9845774a2325e66b11/ --http --sparse`
5. To access the website, open your browser and go to `http://localhost:8080/`

## Seeding

To help distribute and seed downloads you would need 59GB of free storage space 
on a computer. Seeding makes downloading with a distributed system faster for 
everyone and means the files can not be taken down with a copyright notice. 

1. Install [NodeJS](https://nodejs.org/en). Select the LTS version. Restart 
your computer after the installation.
2. Open up a terminal window and install `dat` with `npm install -g dat`.
3. Run the command `dat -h`. If you get any output, you have installed Dat 
succesfully.
4. To start seeding and downloading all the IB resources run the command: 
`dat sync dat://1d57389d37f2da4722edb4d4399fac878b93b7e2a6a69b9845774a2325e66b11/`.
5. To keep seeding, you must keep the terminal window open.
6. If you want to browse the files in-browser _whilst_ seeding, run the above command with
`--http` at the end.

## Disclaimer

This file is merely for instructional purposes. We do not _necessarily_ endorse
 the download or seeding of any documents not published directly by the IB.  
