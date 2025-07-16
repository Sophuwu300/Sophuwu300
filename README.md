# Sophie Kisiel
I write code and stuff. Some of that is here on GitHub. I also do more stuff you can see on the about me page.
## My Links
* [Self-Hosted Git](https://git.sophuwu.com) 
* [Blog and Art Portfolio](https://sophuwu.com/)
* [RedGifs](https://www.redgifs.com/users/helpless-cutie)
## Add My Apt Repository
Script:
```bash
curl https://cdn.sophuwu.com/deb/addrepo.sh | sudo sh
```
Manually:
```bash
sudo wget -O /usr/share/keyrings/soph-deb.gpg "https://cdn.sophuwu.com/deb/key.gpg"
echo 'deb [signed-by=/usr/share/keyrings/soph-deb.gpg] https://cdn.sophuwu.com/deb/ sophuwu main' | sudo tee /etc/apt/sources.list.d/sophdeb.list
sudo apt-get update
```

## Contact
* Discord: @sophuwu
* Email: sophie@sophuwu.com
