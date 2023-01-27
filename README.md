
# Decentralized storage - where privacy meets convenience


FileStorage is a decentralized file storage application that allows users to securely and privately store their files. Using a custom smart contract, the app is deployed on the Polygon Mumbai Testnet, ensuring that the data is immutable and tamper-proof.


## Features✔
- Uses Web3.storage and IPFS (Interplanetary File System), a peer-to-peer protocol, to ensure that the files are stored in a distributed manner, making it resistant to downtime and censorship.
- Built with ReactJS, making it easy for users to upload, manage, and share their files.
- User-friendly and intuitive interface, making it accessible to users of all technical skill levels


## Installation😎

1. Clone the repository
```bash
git clone https://github.com/Gautam-Hegde/FileStorage.git

```

2. Install with npm

```bash
  cd FileStorage
  npm install --force
```
3. Start the development server
```bash
  npm start
```
## Smart Contract Explained🚀
- We have 7 parameters that we want to save, **fileId** will be the serial number that we’ll be counting based on the number of files created, **FileHash** is basically the IPFS hash/CID which is used to identify our file on IPFS network, we’ll get this hash when we upload our file to IPFS
- Next is **FileSize, FileType** and **FileName** which we’ll get from javascript when we upload the file using the input box. 
- **UploadTime** is the time when file was uploaded and **Uploader** is the address which uploaded the file.
## Contributing😉

Contributions are always welcome!
If you have an idea for a new feature or have found a bug, please open an issue or submit a pull request.



## License

[MIT](https://choosealicense.com/licenses/mit/)

