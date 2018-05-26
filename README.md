#How to crack Hashes?

Follow the following steps if you have got the target hash:

1.)Save the hashesthat you target in file(not more than 5)

2.)Now run Hash-identifier on Kali linux to know the type of hash

3.)For brute forcing we need a wordlist which Kali has already prepared

4.)For this type the following code in sequence in terminal:

  i)locate rockyou.txt.gz
  
  ii)cp "_file location_" "./Desktop"
  
  iii)gunzip "_file location_"
  
 5.)Now for MD5 hash we use following code:
 
 hashcat --force -a 0 -m 0 'hash file path' '_file location_' 
  
  
  #-a stands for attack mode
  
  #-m stands for hash type
  
  #one can choose the value for same using:
     hashcat --help

