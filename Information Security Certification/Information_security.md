# [Information Security](https://www.freecodecamp.org/learn/information-security/)
learning Information Security with code camp

## Information Security with HelmetJS

- HelmetJS is a tool for Express-based web apps.
- It helps secure your site by setting HTTP headers automatically.
- This prevents sensitive information from being shared accidentally.
- It helps protecting your website from attacks.

Note: I use Gitpod to complete the tasks

### ⚫ [Install and Require Helmet](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/install-and-require-helmet)

**Solution**

![Solution](img/day1.png)

1. Open your package.json file, locate the dependencies section, and add or update the Helmet entry to specify version 3.21.3.

2. Submit the link.

### ⚫ [Hide Potentially Dangerous Information Using helmet.hidePoweredBy()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/hide-potentially-dangerous-information-using-helmet-hidepoweredby)

**Solution**

![Solution](img/day2_1.png)

1. Start the project on Gitpod, and copy and paste the simple browser link

2. click on submit on challenge

3. Right-click to enter inspect mode, go to Network > app-info > Headers > X-Powered-By: Express. Let's solve this issue. 

![Solution](img/day2_2.png)

4. Add this code to hide the dangerous information.

5. Run `npm run start`

6. Submit the link.

### ⚫ [Mitigate the Risk of Clickjacking with helmet.frameguard()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/mitigate-the-risk-of-clickjacking-with-helmet-frameguard)

**Solution**

### ⚫ [Mitigate the Risk of Cross Site Scripting (XSS) Attacks with helmet.xssFilter()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/mitigate-the-risk-of-cross-site-scripting-xss-attacks-with-helmet-xssfilter)

**Solution**

### ⚫ [Avoid Inferring the Response MIME Type with helmet.noSniff()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/avoid-inferring-the-response-mime-type-with-helmet-nosniff)

**Solution**

### ⚫ [Prevent IE from Opening Untrusted HTML with helmet.ieNoOpen()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/prevent-ie-from-opening-untrusted-html-with-helmet-ienoopen)

**Solution**

### ⚫ [Ask Browsers to Access Your Site via HTTPS Only with helmet.hsts()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/ask-browsers-to-access-your-site-via-https-only-with-helmet-hsts)

**Solution**

### ⚫ [Disable DNS Prefetching with helmet.dnsPrefetchControl()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/disable-dns-prefetching-with-helmet-dnsprefetchcontrol)

**Solution**

### ⚫ [Disable Client-Side Caching with helmet.noCache()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/disable-client-side-caching-with-helmet-nocache)

**Solution**

### ⚫ [Set a Content Security Policy with helmet.contentSecurityPolicy()](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/set-a-content-security-policy-with-helmet-contentsecuritypolicy)

**Solution**

### ⚫ [Configure Helmet Using the ‘parent’ helmet() Middleware](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/configure-helmet-using-the-parent-helmet-middleware)

**Solution**

### ⚫ [Understand BCrypt Hashes](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/understand-bcrypt-hashes)

**Solution**

### ⚫ [Hash and Compare Passwords Asynchronously](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/hash-and-compare-passwords-asynchronously)

**Solution**

### ⚫ [Hash and Compare Passwords Synchronously](https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/hash-and-compare-passwords-synchronously)

**Solution**


# Python for Penetration Testing


### ⚫ [Intodection and setup](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/introduction-and-setup)

**Solution**

What code editor and extension does the instructor recommend for developing penetration testing tools in Python?

- VSCode and Microsoft's Python extension.

### ⚫ [Understanding Sockets and Creating a TCP Server](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/understanding-sockets-and-creating-a-tcp-server)

**Solution**

Which of the following functions creates a socket object?

- socket.socket(socket.AF_INET, socket.SOCK_STREAM)

### ⚫ [Creating a TCP Client](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/creating-a-tcp-client)

**Solution**

Which socket object method lets you set the maximum amount of data your client accepts at once?

- .recv(1024)

### ⚫ [Developing an Nmap Scanner part 1](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/developing-an-nmap-scanner-part-1)

**Solution**

What is the correct command to install the Python 3 version of the python-nmap library?

pip3 install python-nmap

### ⚫ [Developing an Nmap Scanner part 2](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/developing-an-nmap-scanner-part-2)

**Solution**

Which of the following allows you to scan for UDP ports between 21 to 443?


.scan(ip_addr, '21-443', '-v -sU')

### ⚫ [Developing a Banner Grabber](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/developing-a-banner-grabber)

**Solution**

Fill in the blanks to complete the banner function below:

def banner(ip, port):
    s = socket.socket()
    s.__A__((ip, __B__))
    print(s.recv(1024))

A: connect
B: int(port)

### ⚫ [Developing a Port Scanner](https://www.freecodecamp.org/learn/information-security/python-for-penetration-testing/developing-a-port-scanner)

**Solution**

What is the main difference between the .connect() and .connect_ex() methods?

If there is an error or if no host is found, .connect() raises an exception while .connect_ex() returns an error code.


Information Security Projects

### ⚫ [Stock Price Checker](https://www.freecodecamp.org/learn/information-security/information-security-projects/stock-price-checker)

**Solution**

### ⚫ [Anonymous Message Board](https://www.freecodecamp.org/learn/information-security/information-security-projects/anonymous-message-board)

**Solution**

### ⚫ [Port Scanner](https://www.freecodecamp.org/learn/information-security/information-security-projects/port-scanner)

**Solution**

### ⚫ [SHA-1 Password Cracker](https://www.freecodecamp.org/learn/information-security/information-security-projects/sha-1-password-cracker)

**Solution**