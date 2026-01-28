# Sha1 Hash Cracking Practice (hashcat)

This repository is created for **ethical hacking learning and practice** purposes.  
Here I practiced cracking **sha1 hashes** using **hashcat** with the **RockYou wordlist** .

---

## Clone the Repository 

```bash
git clone https://github.com/samrat-xyz/sha1_hash-cracking-by-hashcat.git
cd sha1_hash-cracking-by-hashcat
hashcat -m 100 -a 0 sha1hash.txt /usr/share/wordlists/rockyou.txt
hashcat -m 100 sha1hash.txt --show     