#################################
ISCSI
#################################

ISCSI (Internet Small Computer System Interface) - это протокол передачи данных,
позволяющий передавать блочные данные через сеть IP. Он широко используется для
доступа к удаленным блочным устройствам, таким как жесткие диски (HDD) и
твердотельные накопители (SSD). Документация предоставляет следующие методы для
управления ISCSI-устройствами:

- **sessions**: API для получения списка доступных ISCSI сессий.
- **login()**: Метод для входа в ISCSI-устройство, предоставляющее доступ к
  блочным данным.
- **logout()**: Метод для выхода из ISCSI-устройства и завершения сеанса
  передачи данных.
- **get_host_iqn()**: Метод для получения идентификатора квалифицированного
  имени хоста (IQN), используемого для идентификации устройства в сети.
