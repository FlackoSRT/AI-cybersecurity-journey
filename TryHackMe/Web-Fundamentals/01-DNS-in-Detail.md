# DNS in Detail

## 🧠 What I Learned
DNS (Domain Name System) is like the phonebook of the internet. It translates human-friendly domain names (like `tryhackme.com`) into IP addresses that computers use to identify each other on the network.

When I enter a URL into my browser, a DNS query is made to resolve the domain into an IP address. This involves several steps — from my local cache to recursive resolvers and authoritative name servers.

## 💡 Key Concepts
- DNS = Domain Name System
- UDP port 53 is used by default
- A record = IP address of domain
- CNAME = Alias to another name
- MX = Mail exchange (email servers)
- TXT = Metadata (used for SPF, DKIM, etc.)
- Tools: `nslookup`, `dig`, `host`

## 🧪 Hands-On / Tasks
- Ran `nslookup tryhackme.com` to find its IP address
- Used `dig tryhackme.com ANY` to get all record types
- Learned how recursive DNS servers contact authoritative servers
- Tried `host -t MX tryhackme.com` to get email server info

## 🧩 Reflections / Notes
- I didn’t know how many DNS record types there were!
- `dig` gives more detailed results than `nslookup`
- DNS is usually cached for speed — but sometimes you need to flush it

## 🏁 Completed: ✅

