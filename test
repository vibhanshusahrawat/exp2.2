let nftCount = 0;
const nfts = [];
 
function mintNFT(_name, _eyecolor, _bling, _shirtType) {
  const nft = {
    name: _name,
    eyecolor: _eyecolor,
    bling: _bling,
    shirtType: _shirtType
  };
  nfts.push(nft);
  nftCount++;
  return nft;
}
 
function listNFTs() {
  for (let i = 0; i < nftCount; i++) {
    const nft = nfts[i];
    console.log("name: " + nft.name);
    console.log("eye color: " + nft.eyecolor);
    console.log("bling: " + nft.bling);
    console.log("shirt type: " + nft.shirtType);
    console.log("")
  }
}
 
function getTotalSupply() {
  return nftCount;
}
 
const nft1 = mintNFT("vibhanshu", "black", "golden watch", "chacked");
const nft2 = mintNFT("yash", "brown", "silver watch", "chacked");
const nft3 = mintNFT("aasrush", "white", "silver watch", "column");
const nft4 = mintNFT("sagar", "black", "golden watch", "chacked");
const nft5 = mintNFT("navdeep", "brown", "sliver watch", "chacked");
const nft6 = mintNFT("Amrit", "red", " golden watch", "plain");
 
listNFTs();
console.log("total : " + getTotalSupply());
