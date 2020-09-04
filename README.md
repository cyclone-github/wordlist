I've compiled a wordlist, cyclone_hk, for our hashkiller members.

While there's no "best wordlist", cyclone_hk has proven to be an effective wordlist against multiple databases I've tested it with.

This wordlist has been compiled from several dozen public wordlists / leaks such as hashkiller (jan 2020), hashes.org, crackstation, weakpass, etc, and does not contain any private wordlists or leaks.

This wordlist has been compiled, cleaned, sorted by probability, deduped, and the top 250 million plaintext (257,823,993 lines, 2.6gb) saved to cyclone_hk.txt. This method of wordlist generation is more efficient when cracking compared to running large, multi-gigabyte wordlists that are sorted alphabetically, especially when cracking slow algos or using large rulesets.

Feel free to test cyclone_hk with your hash list + rules and report your findings on this thread.

Enjoy.

~cyclone

http://www.mediafire.com/file/j3ofd9enlas5ba2/cyclone_hk.7z/file

PS

I have not included a test set for cyclone_hk like I did on Hashcat Rules Comparison due to cyclone_hk wordlist contains about 98% of the stockx plaintext which gives it an unfair advantage.
