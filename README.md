# AlignedLayer_testnet_proof 

![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/53deb9a6-5329-46f4-a483-9b717fe62d24)


## Getting Srtarted 

```
sudo apt update -y
sudo apt upgrade -y
```

### Install curl 
```
sudo apt-get install curl -y
```

### Download ALignedProof 
![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/b23d6ec4-ac66-49da-bdf3-5c9b0e3fd5e1)

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```

```
source /root/.bashrc
```


### Download an example SP1 proof file with it's ELF file 
![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/7b2d66df-6e3e-41c6-a234-65a6cfa50f9b)


```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```


### Sending proof 
![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/caec5745-8e99-466a-b8b1-e6a37da05343)


```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

use this code to get the log you will screenshot for your X post
```
aligned verify-proof-onchain \
--aligned-verification-data ~/aligned_verification_data/*.json \
--rpc https://ethereum-holesky-rpc.publicnode.com \
--chain holesky
```


Use the explorer link in CMD to check if verified and you'll also see below image. 
![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/d1540ee0-3fa9-492b-870c-4ab5fe8d76a1)


![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/3e2df540-73e4-415e-bfb3-d4b58dff32a8)


-------------
----------------------
### Tweet exactly as screenshot and Submit Proof in Dscord 

<img width="459" alt="image" src="https://github.com/raghav353/Alignedlayer-testnet-proof/assets/151916837/c9a62ca8-6c64-4835-be7a-282f44fc124c">



--------------------------
### Submit in Discord 
![image](https://github.com/sivapichala/AlignedLayer_testnet_proof/assets/152256858/9e8e29e5-8814-4e0b-8b62-96446286c24c)


# JOIN DISCORD FROM PROFILE 
https://linktr.ee/AlignedLayer



