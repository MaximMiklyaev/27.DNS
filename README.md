# DNS

#добавлен еще один сервер client2

#заведены в зону dns.lab имена

          web1 - смотрит на клиент1
          web2 - смотрит на клиент2

#добавлена еще одна зона newdns.lab в ней запись

          www - смотрит на обоих клиентов

#настроена split-dns

          клиент1 - видит обе зоны, но в зоне dns.lab только web1
          клиент2 - видит только dns.lab

#настроено все без выключения selinux