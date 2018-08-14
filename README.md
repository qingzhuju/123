var abiCoder = new ethers.utils.AbiCoder()
return abiCoder.encode(['string'], ['Hello World'])
