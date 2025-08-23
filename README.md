# win
我的鑰匙
ssh-keygen -t ed25519 -C "your_email@example.com"
 Generating public/private ALGORITHM key pair.
 Enter file in which to save the key (/c/Users/YOU/.ssh/id_ALGORITHM):[Press enter]
 Enter passphrase (empty for no passphrase): [Type a passphrase]
Enter same passphrase again: [Type passphrase again]
# start the ssh-agent in the background
Get-Service -Name ssh-agent | Set-Service -StartupType Manual
Start-Service ssh-agent
ssh-add c:/Users/YOU/.ssh/id_ed25519
ssh-keygen -t ed25519-sk -C "your_email@example.com"
Enter a file in which to save the key (c:\Users\YOU\.ssh\id_ed25519_sk):[Press enter]
 Enter passphrase (empty for no passphrase): [Type a passphrase]
Enter same passphrase again: [Type passphrase again]
