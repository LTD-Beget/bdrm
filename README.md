# BDRM : Beget Domain Registration Microservice API

This API provides full functionality for registering and managing domain names

![status](https://img.shields.io/badge/status-dead-red.svg)
![host](https://img.shields.io/badge/host-bdrm.api.beget.com-blue.svg)
![port](https://img.shields.io/badge/port-6565-blue.svg)
![version](https://img.shields.io/github/release/LTD-Beget/bdrm/all.svg)
![guidelines](https://img.shields.io/badge/guidelines-complied-green.svg)

## Glossary

|Term|Definition|
|---|---|
|Domain|Domain name is an identification string that defines a realm of administrative autonomy, authority or control within the Internet.|
|IDN|Domain that contains at least one label that is displayed in software applications, in whole or in part, in a language-specific script or alphabet, such as Arabic, Chinese, Cyrillic, Tamil, Hebrew or the Latin alphabet-based characters with diacritics or ligatures, such as French.|
|TLD|Top-level domain (TLD) is one of the domains at the highest level in the hierarchical Domain Name System of the Internet.|
|Delegate domain|Location and storage of information about DNS servers of the delegated domain in the DNS servers of the top-level domain.|
|Register domain|Process of acquiring a domain name from a domain name registrar.|
|Renew domain|Process of renewal of registration of the domain, whose registration expires, without canceling the domain and removing information about the current domain administrator.|
|Certificate|Certificate is a document that has legal force and certifies the right to administer a domain name|
|Voucher|Certifies the registration of a domain name|
|AuthInfo|Unique secret key provided by the registrar that is associated with the domain is used to transfer the domain between registrars.|
|WHOIS| Query and response protocol that is widely used for querying databases that store the registered users or assignees of an Internet resource, such as a domain name, an IP address block, or an autonomous system, but is also used for a wider range of other information.|
|Registrar|Organization or commercial entity that manages the reservation of internet domain names.|
|Owner|Person who manages a domain name within the system, but does not always have legal domain ownership rights.|
|Administrator|The actual owner of a domain name, both an individual and an organization that has the full right to manage the domain name at the time of its registration|
|Template|Pre-filling administrator template|
|Authoritative name server|DNS server that stores the main copy of the dns zone file.|
|Subordinate name server|Server that has an Internet address of the form qq.domain-name.tld, where qq is the name of the server of domain name, and domain-name.tld is the domain name|