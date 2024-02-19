---
tags: 
created: 2023-10-18
last_modified_at: 2024-02-02
---
#### Description

Using netcat (nc) is going to be pretty important. Can you connect to `jupiter.challenges.picoctf.org` at port `64287` to get the flag?

> [!hint]- Hint
>nc tutorial


---

### Step 1
1. open up command prompt (windows) or terminal (linux)
2. check if netcat is installed
### Step 2
using ncat you can preform the following command to find the flag 
Usage: ncat \[host] \[port]  
```
ncat jupiter.challenges.picoctf.org 64287
libnsock ssl_init_helper(): OpenSSL legacy provider failed to load.

You're on your way to becoming the net cat master
picoCTF{***********************}
```

<details>
  <summary><h2>Flag</h2><hr></summary>picoCTF{nEtCat_Mast3ry_284be8f7}
</details>