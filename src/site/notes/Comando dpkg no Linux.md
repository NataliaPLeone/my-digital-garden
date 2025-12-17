---
{"tags":null,"dg-home":null,"dg-publish":true,"dg-show-local-graph":true,"date created":"quarta-feira, dezembro 17º 2025","date modified":"quarta-feira, dezembro 17º 2025","permalink":"/comando-dpkg-no-linux/","dgShowLocalGraph":true,"dgPassFrontmatter":true,"created":"2025-12-17T02:21:31.125-03:00","updated":"2025-12-17T02:24:11.747-03:00"}
---

Comando dpkg no [[Linux\|Linux]]

O dpkg é quem faz o gerenciamento de pacotes em sistemas Debian. Ele pode:
- instalar pacotes
- analisar o conteúdo do pacote

> [!warning] Se uma dependência não for satisfeira, haverá falha
> Visto que o comando sabe o que está instalado no sistema e o que é dado na linha de comando, mas não sabe nada dos outros pacotes disponíveis  [^1]

[^1]: https://debian-handbook.info/browse/pt-BR/stable/sect.manipulating-packages-with-dpkg.html

## Comparação com outros comandos
- apt
	- o dpkg está em uma camada mais baixa que o apt
- rpm
- o dpkg faz algo parecido com o que o rpm faz em distros baseadas em [[Red Hat\|Red Hat]] [^2]	

[^2]: https://e-tinet.com/linux/comando-linux-dpkg/
