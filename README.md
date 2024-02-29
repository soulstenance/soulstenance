### Soulstenance
 Welcome to my little profile! What follows is a quick summary about myself and what you can expect from repos I publish here.

#### About
I go by Soulstenance or Soul, anywhere on the internet. I'm a gamer, tech nerd, newbie coder/game dev, and last but certainly not least - a huge proponent of Linux and free and opensource software. While I personally prefer to use the GPL v3 or higher for my projects, other, more permissive opensource licenses have their place as well.

#### My repos
This is a list of currently active, official repos, created by me and freely available for your use.
[Spgu](https://github.com/soulstenance/spgu) - Also know as Soul's Pretty Good Updater (for Debian based systems)

#### My GPG key
From Feb 27, 2024 and onward, I have started signing all my commits, tags, and releases on all my official repos with my official GPG signing key, also sometimes called a PGP key. This adds an extra level of authenticity to my projects and also gives you the peace of mind that when you download one of my projects, you are getting the exact version I intended for you to get.

While GPG can be quite confusing to set up and use, actually verifying a signature is fairly straightforward. To get started, you will need my public key, which is available at [keys.openpgp.org](https://keys.openpgp.org) via their web interface or using the command line. Simply search for my email address. Be sure the fingerprint matches `7647635565F349C740B589EEC2D7FEF79A7901B1`.

To verify the key has the correct fingerprint first run `gpg --show-keys --with-fingerprint example-key.asc` replacing the example key with the name of the key you just downloaded. If it looks right, run `gpg --import example-key.asc`.

Now you're ready to verify your download! Look for the .sig file for the package you downloaded, which is a digital signature file. Run `gpg --verify example-file.sig` replacing the example file with the name of the actual file. The result should say *Good signature from Soulstenance*. If it does, you're good to go. If it says *BAD signature*, it means the file was modified or otherwise corrupted in transit - **delete** the file and download it again. If you are still unable to verify it, please open an issue for that repo and I will be happy to help.

#### Software I use
**OS:** My favorite Linux distros to use currently are Linux Mint and Debian, due to their high stability and ease of use.
**Editor:** In the command line I prefer Nano - simple and easy to use. Otherwise I like Xed for the same reasons. Both come preinstalled on Linux Mint. Notepadqq is also really good if you are familiar with Notepad++ or need more advanced features.
**Office suite:** I have been using LibreOffice since they forked from the now mostly dead OpenOffice many years ago. I absolutely love it!
**Games:** I love dark fantasy RPG games as well as grand strategy and building/automation games. Some examples are Dark Souls, Elden Ring, Europa Universalis IV, Factorio and more. I particularly like to support Linux friendly and opensource games such as [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon).

#### Contact
You can contact me privately at the listed **email** (visible to signed in users). I'm also available on **Discord** at the same username though this is not a private communication method! I use **Signal** as well though I'll only give out that info on a case by case basis, due to the phone number requirement. You can always send me secure private messages on any platform, using my **GPG key**!
