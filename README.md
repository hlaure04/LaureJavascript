# LaureJavascript
https://github.com/hlaure04/LaureJavascript.git


// create a variable to hold your NFT's 

const NFTs = [];

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata,
// and store it in the variable above.

function mintNFT(name, StudentID, age) {
 
  const newNFT = {
   
    name: name,
    StudentID: StudentID,
    age: age,
 
  };
 
  NFTs.push(newNFT);
  
  console.log('Minted: ' + name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()

function listNFTs() {}

// print the total number of NFTs we have minted to the console

function getTotalSupply() {
  for (let i = 0; i < NFTs.lenght; i++) {
    console.log(NFTs.lenght);
  }
}

// call your functions below this line
mintNFT('Leyna', '8213709','19');
mintNFT('Kathy', '202100000799', '20,');
mintNFT('Krystal', '20210113578', '19');
listNFTs();
getTotalSupply();
