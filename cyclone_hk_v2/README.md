### cyclone_hk_v2

It's time for a new, updated cyclone_hk wordlist.

"cyclone_hk_v2" aka "V2" supersedes "cyclone_hk" as V2 includes all the plains from the original cyclone_hk.

V2 has been compiled from dozens of public wordlists / leaks such as hashkiller (jan 2020), hashes.org (2020), crackstation, facebook names, weakpass, etc, and now includes over 2.5GB of plains from Hashmob.

V2 has been compiled, cleaned, deduped and sorted by probability.

Please test V2 and report your findings.

All credits go to the original wordlist creators.

Enjoy,

~cyclone

download cyclone_hk_v2.txt here: 
- https://hashkiller.io/downloads/cyclone_hk_v2.txt.7z
- https://hashmob.net/api/v2/downloads/research/wordlists/cyclone_hk_v2.txt
- https://anonfiles.com/pcfaI613yf/cyclone_hk_v2_7z

cyclone_hk_v2.txt sha1 57a2268fa6904f2b2aa743316f1b71aba900ec03  

hashkiller forum post: https://forum.hashkiller.io/index.php?threads/cyclone-wordlist.42089/

###############################################################

Testing:

Test set is a combination of 50% plains from several dozen sources (dubsmash, stockx, poshmark, etc) + 50% mangled plains using various cyclone.rules.
All plains are 9+ char len and include at least 1 upper, lower & digit.
Test set was narrowed down from 100M to 1M by the following command:

shuf test_100m.txt | rg '[a-zA-Z0-9]{9,}' | head -n 1000000 > test_plains.txt

Test set md5 hashes: ~https://anonfiles.com/Gca9pb16y6/test_md5_hash_7z~

Test set plains: ~https://anonfiles.com/y9a9pb14y4/test_plains_7z~

See "comparison.png" for head to head comparison.
