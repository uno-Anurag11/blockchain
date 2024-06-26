# *Blockchain*  
- Blockchain is a public, decentralized, and distributed digital ledger that records transactions across multiple computers
<img width="850" alt="Screenshot 2024-03-08 115051" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/52d1b0b1-2c90-43eb-b7bc-ea5fb3eca26e">

- A *block* is a page of a ledger or account book that stores some or all of the recent transaction details in a blockchain that have not yet entered any of the prior blocks.
<img width="850" alt="Screenshot 2024-03-08 115657" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5fd606a5-8dee-483e-8958-e9e4350e5301">

-------------  


### *Applications of Blockchain*
- Product tracking-Product tracking in blockchain is a way to track the movement of goods through a supply chain.
- Smart contracts-A smart contract is a computer program that is stored on a blockchain and automatically executes agreements when certain conditions are met and runs on ethereum blockchain.
- Healthcare system
- International wire transfer
  - *Examples*

    <img width="650" alt="Screenshot 2024-03-08 121359" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/73c47da4-43ba-4a5c-b92b-56c1e4c31430">
    <img width="650" alt="Screenshot 2024-03-08 121416" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/55fa38a2-f74a-4e8f-aa9c-2b82a2796aeb">  
    <img width="650" alt="Screenshot 2024-03-08 123640" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/2ed7ac0d-3448-421c-bd86-a06b948c5c16">       

  
---------------  

### *Hashing Algorithm*  
<img width="850" alt="Screenshot 2024-03-08 124012" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/38ba5141-33c4-4f0b-b61c-78104cfa0b65">     
<img width="850" alt="Screenshot 2024-03-08 124145" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/3a5b2c47-23a6-4741-bd3b-509e892d1c52">  
<img width="850" alt="Screenshot 2024-03-08 124435" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/0794d6c1-fceb-46bc-83aa-0dbfef2cbc92">

- Hash is generated by "SHA 256" algorithm
- *Requirements of hash algorithm*
  - Hash algorithm is a one way(data can be converted to encrypted data but vice versa is not possible)
  - It generates the same output irrespective of how many times we give input
  - It should be fast and withstand collisions(cyberattacks)
  - Avlanche effect(even a minor change in inpute leads to change the whole output)

--------  


### *Immutable Ledger*
- It is a record-keeping system that cannot be altered or modified once information is added to it.
<img width="850" alt="Screenshot 2024-03-08 130644" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/8f885086-420f-42f8-acd9-1c80f31d06c7">

--------  

### *P2P Network*
<img width="850" alt="Screenshot 2024-03-08 130924" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/2ff1db3d-88d4-4aa2-a4be-5539bbdf83a1">    
<img width="850" alt="Screenshot 2024-03-08 131143" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/716de2da-b003-4a38-b71f-66f232b00285">  
<img width="850" alt="Screenshot 2024-03-08 131437" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/784206e1-85ba-45b6-825f-bd2b9468e0e0">  

- If A mine a block in a network then it sends information about it to the other computers in the network
- After checking the validity of that block each computer then add that block to their own blockchain
- If a hacker attacks a blockchain of any computer and corrupts its blocks then, the other computers in the network sends information of mismatched data and the corrupted block can be recovered as it was earlier

 ------------  

 ### *Blockchain Mining*  
 - Blockchain "mining" is a metaphor for the computational work that network nodes undertake to validate the information contained in blocks.
<img width="850" alt="Screenshot 2024-03-08 171420" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/c4c0cf72-4adb-4617-9af6-e111a9132320">
<img width="850" alt="Screenshot 2024-03-08 171931" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/ace615d2-906c-45c8-91b0-5fa28b9d906e">
<img width="850" alt="Screenshot 2024-03-08 172138" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/1494ab11-03df-41dc-94e2-ee25cfc8ad5a">



### *Consensus Protocol*
- A consensus mechanism is a protocol that brings all nodes of a distributed blockchain network into agreement on a single data set.
- Types of consensus protocol
   - Proof of work(POW)
   - Proof of stake(POS)
   - Others
<img width="850" alt="Screenshot 2024-03-08 173517" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/63a3a4e1-f6a1-49ea-bced-7bc29e23a067">

- If a malicious activity is detected by any attacker then incentive and that block is not given to that attacker and following algorithm runs on each system to validate the mine activity
<img width="850" alt="Screenshot 2024-03-08 173811" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/b4fe1bb1-50a8-4195-af2a-3def1ff8b6c1">
<img width="850" alt="Screenshot 2024-03-08 174455" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/49e90f92-352a-445f-80db-9b0711d806f1">
<img width="853" alt="Screenshot 2024-03-08 174508" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/1df3c93b-ddb3-4293-82af-9f3d4fa09a4d">

- If all nodes have same computational power then the network which is bigger will be able to mine its next block faster than smaller network and the earlier mined block or smaller network will be replaced(discarded) by newly two mined blocks of larger network.The discarded blocks are called orphan blocks
<img width="850" alt="Screenshot 2024-03-08 174855" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/cfcc478f-a58f-43fa-bc91-2c64cd1e8e41">









 
 





 
