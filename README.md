Angellist-Emailer
====

### Taking Angellist's API to the next level

Angellist-Emailer is an open source project that allows you to email blast startups listed on Angellist's Api. 


How it works:
---

Angellist-Emailer is a python script which queries Angellist's api for startups and emails them at their 'jobs@' + #{company url} email address. To setup an instance, add your gmail username & password, compose an email to send, and specify a MongoDB url(optional). (Our implementation is running at `917-791-3098` Give it a try!)


Body and Subject Markup:
---

- ** name **
- ** url **
- ** angellist_url **


Queries:
---

Put one of the following letters, a colon, and your query in your text. The letter helps whit route your query to the correct API.

- **p**: {a person's name}
- **c**: {a company's name}
- **s**: {a stock ticker code}
- **w**: {a wikipedia query name}

Screenshots:
---

As promised, here's a couple of screenshots, showing Whit in action:

![Person](images/person.png)
![Company](images/company.png)
![Stock](images/stock.png)
![Wiki](images/wiki.png)

