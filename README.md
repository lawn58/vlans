# vlans

1. равести вланами
testClient1 <-> testServer1
testClient2 <-> testServer2
Чтобы проверить введите команды:

vagrant ssh testServer1
vagrant ssh testClient1
vagrant ssh testServer2
vagrant ssh testClient2


2. между centralRouter и inetRouter
"пробросить" 2 линка (общая inernal сеть) и объединить их в бонд
проверить работу c отключением интерфейсов
Чтобы проверить введите команды:

vagrant ssh inetRouter
vagrant ssh centralRouter
