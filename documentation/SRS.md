
# Software Requirements Specification
### Contents
1. [Introduction](#1-introduction) <br>
  1.1 [Purpose](#11-purpose) <br>
2. [Overall Description](#2-overall-description) <br>
  2.1 [Software Interfaces](#21-software-interface) <br>
  2.2 [User Interfaces](#22-user-interface) <br>
  2.3 [User Characteristic](#23-user-characteristic) <br>
  2.4 [Assumptions and Dependencies](#24-assumptions-and-dependencies) <br>
3. [System Requirements](#3-system-requirements) <br>
  3.1 [Functional Requirements](#31-functional-requirements) <br>
  3.2 [Non-Functional Requirements](#32-non-functional-requirements) <br>  
  3.2.1 [Software Quality Attributes](#321-software-quality-attributes)


---

# <ins>1. Introduction</ins>

### 1.1 Purpose

The purpose of this document is build a web-application ***Crown-shop*** to selling different products and provide to user convenient way to overview entire amount of books, which shop provide to customer

---

# <ins>2. Overall description</ins>

### 2.1 Software Interfaces

Main language - *JavaScript*. Operation system - *Windows 10 Pro* (with *WSL Ubuntu 20.04 LTS*). Development environment - Text editor *Visual Studio Code*.
Used libraries:
- Front-End:
  - React.js
  - Redux
  - Redux-Saga
  - React-Stripe
  - node-scss
- Back-End:
  - Node.js
  - Express
  - Stripe


### 2.2 User Interfaces

App has 4 main pages:
- Home page ([Figure 1](https://github.com/Xyrmovich/Crown-shop/blob/master/documentation/mokups/home-page.png))
- Sign In and Sign Up page ([Figure 2](https://github.com/Xyrmovich/Crown-shop/blob/master/documentation/mokups/sign-in-and-sign-up-page.png))
- Shop page ([Figure 3](https://github.com/Xyrmovich/Crown-shop/blob/master/documentation/mokups/shop-page.png))
- Collection overview page ([Figure 4](https://github.com/Xyrmovich/Crown-shop/blob/master/documentation/mokups/collection-overview-page.png))

### 2.3 User Characteristics

The user will be able explore which shop provides without signing in and will be able to add products to cards and then buy them after singing in. If user doesn't have an account yet, it's possible create an new user account on "Sign In and Sign Up page"

### 2.4 Assumptions and Dependencies

Web-application ***Crown-Shop*** can't functional properly without Internet connection

---

# <ins>3. System Requirements</ins>

### 3.1 Functional Requirements

User have possibilities to:
- View all categories of products
- View all products of particular category
- Create new account in ***Crown-shop***'s system
- Sing In in ***Crown-shop***'s system
- Add products to cart(if signed in)
- Pay for products via card

### 3.2 Non-Functional Requirements

##### 3.2.1 Software Quality Attributes

#### Security

  Application have to have enough security level to prevent intruders from stealing user personal information or getting access to back-end server payment process

---
