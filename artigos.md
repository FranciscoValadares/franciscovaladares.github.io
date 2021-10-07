---
layout: page
title: Artigos
permalink: /artigos/
---

Página para os artigos


### GitHub: Add an SSH Key
1)  ssh-keygen -t rsa -b 4096 -C "valadares.francisco@gmail.com"
2)  ssh-add ~/.ssh/id_rsa
3)  Add the SSH Key on GitHub
    clip < ~/.ssh/id_rsa.pub
    And past on GitHub in your web browser
