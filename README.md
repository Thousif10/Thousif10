# IG-Brute v1.0
## Author: https://github.com/Thousif10

### Don't copy this code without give me the credits 
IG-Brute is an updated Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of +400 passwords/min using 20 threads.

## Legal disclaimer:
Usage of IG-Brute for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

![insta]### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies


### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh

```
Give the Instagram Account ID

```
passwords.lst
```
limit (like <20 to 50000)

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking. 
The script uses Instagram-py algorithm.
