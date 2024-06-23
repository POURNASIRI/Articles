# What will you learn through this article?
![alt text](image.png)

Before introducing authentication methods, it is essential to understand the concepts of `identification`, `authorization`, authentication, access control, and their relationships. By understanding these fundamentals, you can build a solid foundation for comprehending the topic as a whole.

## What is identification?
**Identification is the process of verifying a person’s identity.** It involves providing information that can be used to uniquely identify a person, such as their `name`, `address`, or `date` of `birth`.
**In simpler terms, it means you need to prove that you are who you claim to be.**
Here are some common authentication techniques that are used to verify a person’s identity:

1. **Identification card:** An identification card is a physical document that contains a person’s unique identifying information.
2. **Username and password:** A username and password are a combination of characters that are used to log in to a computer system or website.
3. **User’s mobile phone:** A user’s mobile phone can be used to verify their identity by sending a `one-time password (OTP)` or by scanning a QR code.
4. **User’s email:** A user’s email address can be used to verify their identity by sending an OTP or by clicking on a link in an email.
5. **User’s biometric features:** Biometric features, such as fingerprints or facial scans, can be used to verify a person’s identity.

## What is authorization?
In the field of information security, **authorization refers to the process of granting users or services the right to access certain resources or perform certain actions.** This is done to ensure that only authorized users have access to sensitive data or systems.

In real-world scenarios, examples of authorization include:

1. **Bank cards issued by banks,** which allow users to withdraw money from ATMs or make purchases.
2. **Access cards are distributed by property management companies,** which allow residents to enter buildings or access certain areas.
3. **Keys are provided by landlords**, which allow tenants to enter their homes.

On the internet, examples of authorization mechanisms include:

- **Sessions:** A session is a temporary authenticated state that a user has with a website or application. Once a user has logged in, they are assigned a session ID, which is used to track their activity on the website or application.
- **Cookies:** Cookies are small text files that are stored on a user’s computer by a website or application. Cookies can be used to store session IDs, user preferences, or other information.
- **Authorization tokens:** Authorization tokens are a type of cryptographic token that is used to grant access to resources. Authorization tokens are typically issued by an authorization server and are used to authenticate users to a resource server.

`Authorization` is an important part of information security. By ensuring that only authorized users have access to sensitive data or systems, organizations can help to protect themselves from unauthorized access, data breaches, and other security incidents.


## What is authentication?
**Authentication is the process of verifying the identity of an entity and confirming the authenticity of the rights claimed by that entity.** It is a critical component of information security, as it helps to protect systems and data from unauthorized access.

**Authorization is the process of determining what permissions an authenticated entity has. It is closely related to authentication, but it is a separate process.**

In real-world scenarios, authentication can be seen in the use of access cards, bank cards, and passwords. When you swipe your access card at a door, the card reader verifies that the card is valid and that you are authorized to enter the door. When you enter your bank card PIN at an ATM, the ATM verifies that the PIN is correct and that you are authorized to withdraw money from your account.

On the internet, authentication is used to verify the identity of users and to protect their sessions. When you log in to a website, the website verifies your username and password to confirm that you are who you say you are. The website then creates a session for you, which is a temporary identifier that is used to track your activity on the website.

**Authentication is a crucial link between authorization and permission control. Authorization determines what permissions an authenticated entity has, and permission control enforces those permissions. Authentication provides the foundation for authorization and permission control, and it is essential for protecting systems and data from unauthorized access.**

## What is access control?
**Access control is the process of defining a list of permissible operations and determining whether an operation is allowed or prohibited. It is a fundamental security concept that is used to protect systems and data from unauthorized access.**


**Access control involves two components: permissions and control. Permissions are abstract logical concepts that define what actions a user or system is allowed to perform. Control represents the concrete implementation methods that are used to enforce permissions.**


In real-world scenarios, access control can be implemented using a variety of methods, such as access cards, passwords, and biometrics. For example, one access card may have permission to open staff entrance doors in a company, while another access card may have administrative privileges, allowing it to open all doors within the company.

On the internet, access control is achieved through web backend services that control access to APIs, granting or denying access requests.

Here are some of the benefits of access control:

- It helps to protect systems and data from unauthorized access.
- It can help to prevent fraud and theft.
- It can help to improve the overall security of a system.

Here are some of the challenges of access control:

- It can be complex to implement and manage.
- It can be difficult to keep permissions up-to-date.
- It can be vulnerable to attack.

![alt text](image-1.png)
You should note that these four links sometimes occur simultaneously.

When you log in with a username and password, authentication and authorization are completed together, while authentication and permission control occur in subsequent access requests, such as when purchasing items or paying.

# frontend authentication methods and the differences between them:


## 1. HTTP Basic Authentication
In HTTP, Basic Authentication is an authentication scheme that allows the client `(typically a web browser) `to authenticate the user’s identity by providing a username and password in the request.

![alt text](image-2.png)

