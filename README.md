# Topics on Computer Security

Principles to keep in mind if you want your applications to be secure:

- Never trust any input!
- [Validate input](http://www.ibm.com/developerworks/library/l-sp2.html) from all untrusted sources - use whitelists not blacklists
- Plan for security from the start - it's not something you can bolt on at the end
- Keep it simple - complexity increases the likelihood of security holes
- Keep your [attack surface](http://en.wikipedia.org/wiki/Attack_surface) to a minimum
- Make sure you [fail securely](http://www.owasp.org/index.php/Fail_securely)
- Use [defence in depth](https://buildsecurityin.us-cert.gov/bsi/articles/knowledge/principles/347-BSI.html)
- Adhere to the principle of [least privilege](https://buildsecurityin.us-cert.gov/bsi/articles/knowledge/principles/351-BSI.html)
- Use [threat modelling](http://www.owasp.org/index.php/Threat_Risk_Modeling)
- [Compartmentalize](http://www.cgisecurity.com/owasp/html/ch04s09.html) - so your system is not all or nothing
- Hiding secrets is hard - and secrets hidden in code won't stay secret for long
- Don't write your own crypto
- Using crypto doesn't mean you're secure (attackers will look for a weaker link)
- Be aware of [buffer overflows](http://www.linuxjournal.com/article/6701) and how to protect against them

Books about the subject:

- [**Writing Secure Code 2nd Edition**](http://rads.stackoverflow.com/amzn/click/0735617228)
- [**Security Engineering**](http://www.cl.cam.ac.uk/~rja14/book.html)
- [Building Secure Software: How to Avoid Security Problems the Right Way](http://rads.stackoverflow.com/amzn/click/020172152X)
- [Secure Programming Cookbook](http://rads.stackoverflow.com/amzn/click/0596003943)
- [Exploiting Software](https://docs.google.com/viewer?url=http://www.usenix.org/events/sec04/tech/slides/mcgraw.pdf)
- [Secure Programming for Linux and Unix HOWTO](http://www.dwheeler.com/secure-programs/Secure-Programs-HOWTO/index.html)

Application security best practices:

- [Codebashing](http://www.codebashing.com/sql_demo) (paid)
- [Security Innovation](https://www.securityinnovation.com/training/application-security) (paid)
- [Security Compass](https://www.securitycompass.com/training/) (paid)
- [OWASP WebGoat](https://www.owasp.org/index.php/OWASP/Training/OWASP_WebGoat_Project) (free)
