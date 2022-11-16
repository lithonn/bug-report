# Broken Access Control

Discoverer(s)/Credits: CMCSOC Redteam (@lithonn)

- Ngo Van Tu (@leecybersec)
- Tran Thi Nho (@nhott)
- Huynh Nhat Hao (@h40huynh)
- Le Thi Huyen My (@Huy3nMy)

The product(s): https://www.sourcecodester.com/php/15748/book-store-management-system-project-using-php-codeigniter-3-free-source-code.html

Affected product(s)/code base: https://www.sourcecodester.com/sites/default/files/download/oretnom23/bsms_ci.zip

Affected component(s):

- /bsms_ci/index.php/dashboard/*
- /bsms_ci/index.php/category/*
- /bsms_ci/index.php/book/*
- /bsms_ci/index.php/transaction/*
- /bsms_ci/index.php/history/*
- /bsms_ci/index.php/user/*

Proof of Concept: Access all URLs without logging in and use all actions like an admin like edit, detele, add new account.

1. Send a request Add new account without cookie

Burpsuite Request:

``` txt

```

Image:

![image](link)

2. Send a request Delete account without cookie

Burpsuite Request:

``` txt

```

Image:

![image](link)