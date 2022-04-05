---
layout: page
title: Recenze
subtitle: ⭐⭐⭐⭐⭐ <br/> (4.5 z 5)
---

Pokud se vám kniha líbila, zanechte prosím [recenzi na Amazonu][amazon]. Pomůže 
to šířit povědomí o knize a potěší to algoritmické bohy naší doby. Děkuji!

---

{% for r in site.reviews %}
{% include review.html review=r %}
---
{% endfor %}

Nechcete svůj názor sdílet veřejně? Neváhejte se obrátit [přímo na mě][contact]. 
Rád vás vyslechnu. Pokud nemáte rádi Amazon, můžete také zanechat recenzi na 
[Goodreads][goodreads] nebo na jiné platformě pro hodnocení knih.

[amazon]: https://amzn.to/2VXmQgp
[contact]: https://dergigi.com/contact
[goodreads]: https://www.goodreads.com/book/show/50376693-21-lessons
