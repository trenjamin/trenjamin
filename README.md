## Hi there 👋

`#101 global hackerone` // `maldev` // `reverse engineering` // `cloud infrastructure` // `Google: trenjamin hacker one`

> "i don't care about your cve count. i care about the assumptions your architecture makes when it thinks no one is looking at the edge cases."

> "The people I work with i like to get em undisclosed all you're getting is "NoneyBaloney, he helps me with OSINT & Pred catching" - "DJ" Learning Cyber Security & a good friend of mine - "AnavarKid" helps in pentesting - "ROIDADDICT" most rep working with me, always there whenever i'm working on something.

---

### About Me
- Founder @ **KillByteHub**
- Ranked **#101 Worldwide** on HackerOne  
- **CTF Competitor**
- **Malware Analyst**
- **Reverse Engineer & Maldev**
- **0day / Vulnerability Research**
- **Verified Provider — paid pentesting, not just bounty hunting**
- **500+ Preds Caught - Pred Catching**

---

### whoami
i'm 17. i break things that cost millions to build, mostly because the people who built them assumed nobody would look at the weird gRPC endpoints or the custom memory allocators. i specialize in offensive security, malware development (c/c++/rust), reverse engineering, and tearing apart cloud infrastructure. 

currently running private operations for AWS and doing high-end web security audits. if i'm not in ida pro, x64dbg, or windbg, i'm probably writing a custom loader, chaining an SSRF, or staring at a heap dump trying to figure out why your parser just gave me arbitrary code execution.

i don't use automated scanners to find bugs. i use them to map the surface, then i write the python script that exploits the logic flaw the scanner missed.

search "trenjamin hackerone" and you'll read about me. can't find my account on hackerone? probably because my real name isn't trenjamin, smartass. verified provider with paid pentesting, private engagements, and actual deliverables — not just a profile link.

---

### the work (highlights & disclosures)
* **aws internal pentest (iam & tenant isolation):** found a medium-severity IAM misconfiguration that wasn't just a dangling policy. it was a scoped role assumption combined with a wildcard resource ARN that allowed lateral movement across isolated organizational units. chained it with a metadata service leak (bypassing IMDSv2 token requirements via a compromised sidecar container) to prove full tenant impact. 
* **cloud microservices (ssrf & protocol smuggling):** bypassed standard WAF rules to hit an internal routing table. standard scanners missed it because the payload required a specific, undocumented state in the microservice's protobuf handler. managed to desync the gRPC stream and leak internal routing tables.
* **web api token exposure (jwt/jws):** tore down a proprietary session management lifecycle. found improper cryptographic signing on refresh tokens (they were using `none` algorithm fallback in a custom java library) that allowed full session hijacking and privilege escalation across their production fleet.
* **0day / vulnerability research:** currently sitting on a couple of unreported UAF (Use-After-Free) primitives in a widely used open-source C library. working on weaponizing the heap layout before disclosure.
**OSINT & Predator Apprehension: verified ethical hacker specializing in deep OSINT investigations and predator catching. successfully identified and assisted in the apprehension of 500+ predators and extortionists. currently providing intelligence gathering and operational support for upcoming streamer Kadenem [Twitch](https://www.twitch.tv/kadenem_) [YouTube](https://www.youtube.com/@kadenmarriott) in collaboration with NoneyBaloney.**

* **if you need access to something that shouldn't be accessible, dm me on discord. bring context not aids.**

---

### Achievements & Work Highlights
- Reported a **medium‑severity IAM misconfiguration** during an AWS pentest that improved internal access‑control hygiene  
- Identified a **minor SSRF‑adjacent behavior** in a cloud microservice that contributed to a broader security review  
- Helped a client resolve **token exposure** in a web API during routine security testing  
- Consistently deliver **high‑quality triaged reports** across multiple bug bounty programs

---

### Most Reputable Testimonial (Amazon Vulnerability Research Program)
"We had the pleasure of working with trenjamin through our bug bounty program, and their contributions have been exceptional. trenjamin’s ability to identify critical security vulnerabilities, combined with deep technical expertise and a methodical approach to ethical hacking, has significantly enhanced our security posture. trenjamin consistently demonstrates professionalism, responsiveness, and an attacker’s mindset, all while upholding the highest ethical standards. Rather than relying solely on standard tools, trenjamin thinks like an adversary, allowing them to uncover sophisticated vulnerabilities before they could be exploited. We highly recommend trenjamin to any organization seeking to strengthen its security through ethical hacking and responsible disclosure. Their dedication, technical skill, and strategic mindset make them a valuable asset to any security team and set them apart in the bug bounty community."

### PAID PENTEST ACHIEVMENTS

- Conducted security assessments and pentesting for major tech entities including Amazon, Cloudflare, and Apple.
- Reported a medium‑severity IAM misconfiguration during an AWS pentest that improved internal access‑control hygiene.
- Identified a minor SSRF‑adjacent behavior in a cloud microservice that contributed to a broader security review.
- Helped a client resolve token exposure in a web API during routine security testing.
- Consistently deliver high‑quality triaged reports across multiple bug bounty programs.

---

### HELP THE PUBLIC | OSINT & Apprehension Operations

i don't just look at code; i look at people. as a verified ethical hacker specializing in predator catching and deep-dive OSINT, i’ve helped identify and facilitate the apprehension of 500+ predators and extortionists.
currently providing intelligence gathering and operational support for upcoming streamer Kadenem Twitch(https://www.twitch.tv/kadenem_) YouTube(https://www.youtube.com/@kadenmarriott) in collaboration with NoneyBaloney. we track the trackers and turn their own footprints against them.
Testimonial (Private Apprehension Operation):

"trenjamin doesn't just find data; he finds the person behind the screen. his OSINT work was surgical—turning a few leaked IPs and a blurry screenshot into a full physical location and identity within 48 hours. professional, discreet, and terrifyingly effective. if you're hiding, he's already found you."

### 📫 How to reach me
Discord: **._ trenjaminbutton _.**
### 📫 How to reach me
* Discord: **._ trenjamin _.**
* [Guns.lol](https://guns.lol/trenjamin) & [UNCHECKED (Paid Pentesting)](https://paidunchecked.netlify.app/)

---

*note: i don't do generic networking, and i don't teach beginners. if you message me, bring a technical problem, a pcap, a binary, or a bounty split. script kiddies and recruiters will be blocked.*
