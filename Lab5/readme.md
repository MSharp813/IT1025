# Executive Summary

With this lab we have learned how to use Lucidchart, a little about networking, cyber security, and encryption. We also made a model of a network topology, did some encrypting and decrypting, learned about brute-force attacks, etc. 

# Lucidchart

I liked using the Lucidchart. It helps in the planning phase of making a website.Those who are plnning to  make a website could use this to help them.

# Introduction to Networking

## Data Transmission

Packet, Packet-Switching, IP Address, DNS, Protocol
Packet: Unit of data When a device intends to send a message to another device it breaks the message down into smaller pieces, called packets.
Packet-Switching: Technology that allows packets of data to be routed based on destination addres
IP Address: Unique identifying number
DNS: (domain name system) Directory of IP address common names.  For example 54.239.26.214 might be the IP address of amazon.comacts as the directory on the Internet. When a request to access a device with a domain name is given, a DNS server is queried. It returns the IP address of the device requested, allowing for proper routing.
Protocol: Set of rules to allow devices to communicate 

## Networking Hardware

Both devices, the switch and the hub have multiple ports that accepts Ethernet connections from Network Devices, but unlike a hub a switch is intelligent a switch it learns the physical addresses of the devices that are connected to it and stores these physical addresses called Mac addresses in its table. So when a data packet is sent to a switch. It's only directed to the intended destination port.
The benefits of routers over hubs and switches is that it can receive data outside of a local connection.

## Network Topologies

Single point failure is when a central hub or a switch failing that causes all computers on that central point to be affected, and will cause the whole network to go down. Star and ring topologies suffer from a single point failure.
Infrastructure topology has a combination of wired and wireless connections and a wireless mesh topology has only a wireless connection. I believe infrastructure is better because there is a wired and wireless connection.

## Network Design

I designed my network like a infrastructure topology. The router has a wired connection between the two computers and the printer and a wireless connection with the wireless access point.

## NSA/CSS

The National Security Agency/Central Security Service (NSA/CSS) leads the U.S. Government in cryptology that encompasses both signals intelligence (SIGINT) cybersecurity products and services, and enables computer network operations (CNO) in order to gain a decision advantage for the Nation and our allies under all circumstances.

#  Cybersecurity and Encryption

## Information Systems Security

If I was a part of the Amazon.com online chat I would have to make sure that peoples sensitive information would be protected and restricted from any unauthorized people. I would also need to have integrity to not alter the information I have accessed. I would also have to make sure that the servers would be available twenty-four hours a day, seven days a week. 

Unlocking an iphone, logging in to a computer, and withdrawing money from an ATM all require authentication. They could be converted to multi-factor authentication by asking for a finger print and a passcode for iphone, a facial scan and a password for unlocking a computer, and a ask for a pin and the card for the ATM. 

An access control list, or ACL is when a list of users who have the ability to take specific actions can be created
for each information resource that an organization wishes to manage. ACLs are simple to understand and maintain, but each information resource is managed separately, so if a security administrator wanted to add or remove a user to a large set of information resources, it would be quite difficult. And as the number of users and resources increase, ACLs become harder to maintain.
With RBAC, instead of giving specific users access rights to an information resource, users are assigned to roles and then those roles are assigned the access. This allows the administrators to manage users and roles separately, simplifying administration and, by extension, improving security.
To send an encrypted message, you obtain the public key, encode the message, and send it. The recipient then uses the private key to decode it.
We need public key encryption to help with cybersecurity. Public key enryption makes it harder for unauthorized people to get other's personal information.

# Cryptography

In Caesar Cipher the encryption message changed based on the number which shifted the letters so each letter stood for a different letter. Hello with a shift of four is Khoor.

In the frequency fingerprint encryption the letters you typed in the message were used to fill up a bar the messured how many times you typed in the message. The only difference it would have in a different language would be the letters. Hello in this encryption would fill up the h, e, and o bar once and the l bar twice. Typing jdqnn with a shift word of bye leaves the decrypted message as hello.

## Brute-Force

A brute-force attack tries every possible decryption key for a cipher. Kerckhoffs’s principle states that a cipher should still be secure even if everyone knows how the cipher works and someone else has the ciphertext. Kerckhoff believes that a ciphr should still be secure even if there is a brute force attack.

A polyalphabetic cipher is any cipher based on substitution, using multiple substitution alphabets.

# Conclusion

With this lab we have learned how to use Lucidchart, a little about networking, cyber security, and encryption.
