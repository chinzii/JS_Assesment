/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
const NFTs=[]
// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (d1,d2,d3) {
    const nft={
        name: d1, 
        style: d2, 
        colour: d3
    }
    NFTs.push(nft);
    console.log(nft.name+" is minted");
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
    console.log("\nList of all NFTs : ");
    for(let i=0;i<NFTs.length;i++)
    {
        console.log("\nName of the NFT is : "+NFTs[i].name);
        console.log("Style of the NFT is : "+NFTs[i].style);
        console.log("Colour of the NFT is : "+NFTs[i].colour);
    }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
    const number=NFTs.length;
    console.log('\nTotal Number of NFTs created : '+number);
}

mintNFT("mukess","bent","pink");
mintNFT("rajess","outside","black");
mintNFT("mahess","dalla","brown");
mintNFT("rex","straight","orange");
listNFTs();
getTotalSupply();
