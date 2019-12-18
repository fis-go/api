[![Dreamkas](https://avatars3.githubusercontent.com/u/18038967?s=200&v=4)]()

# FisGo API

##### JSON explanation

```json
{
  "type": "SALE",
  "payments": [
    {
      "type": "CASHLESS",
      "sum": 1000
    }
  ],
  "deviceId": 3420,
  "timeout": 5,
  "attributes": {
    "email": "m.savchenko@dreamkas.ru",
    "phone": "+79101179441"
  },
  "total": {
    "priceSum": 1000
  },
  "positions": [
    {
      "type": "COUNTABLE",
      "name": "С банковским агентом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 1
        },
        {
          "tag": 1171,
          "value": "+79101179442"
        },
        {
          "tag": 1225,
          "value": "Наименование поставщика банковского агента"
        },
        {
          "tag": 1226,
          "value": "111111111112"
        },
        {
          "tag": 1044,
          "value": "ОП.ПЛ АГЕНТА"
        },
        {
          "tag": 1005,
          "value": "Адрес оператора перевода"
        },
        {
          "tag": 1016,
          "value": "222222222223"
        },
        {
          "tag": 1073,
          "value": "+79101179443"
        },
        {
          "tag": 1075,
          "value": "+79101179444"
        },
        {
          "tag": 1026,
          "value": "Оператор перевода"
        }
      ]
    },
    {
      "type": "COUNTABLE",
      "name": "С банковским платёжным субагентом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 2
        },
        {
          "tag": 1171,
          "value": "+79101179445"
        },
        {
          "tag": 1225,
          "value": "Наименование поставщика банковского платёжного субагента"
        },
        {
          "tag": 1226,
          "value": "333333333334"
        },
        {
          "tag": 1073,
          "value": "+79101179445"
        },
        {
          "tag": 1044,
          "value": "ОП.ПЛ АГЕНТА"
        },
        {
          "tag": 1005,
          "value": "Адрес оператора перевода"
        },
        {
          "tag": 1016,
          "value": "444444444445"
        },
        {
          "tag": 1026,
          "value": "Оператор перевода"
        },
        {
          "tag": 1075,
          "value": "+79101179446"
        }
      ]
    },
    {
      "type": "COUNTABLE",
      "name": "С платёжным агентом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 4
        },
        {
          "tag": 1171,
          "value": "+79101179447"
        },
        {
          "tag": 1225,
          "value": "Наименование поставщика платёжного агента"
        },
        {
          "tag": 1226,
          "value": "555555555556"
        },
        {
          "tag": 1073,
          "value": "+79101179447"
        },
        {
          "tag": 1074,
          "value": "+79101179448"
        }
      ]
    },
    {
      "type": "COUNTABLE",
      "name": "С платёжным субагентом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 8
        },
        {
          "tag": 1171,
          "value": "+79101179449"
        },
        {
          "tag": 1225,
          "value": "Наименование поставщика платёжного субагента"
        },
        {
          "tag": 1226,
          "value": "666666666667"
        },
        {
          "tag": 1073,
          "value": "+79101179449"
        },
        {
          "tag": 1074,
          "value": "+79101179450"
        }
      ]
    },
    {
      "type": "COUNTABLE",
      "name": "С поверенным",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 16
        },
        {
          "tag": 1171,
          "value": "+79101179451"
        },
        {
          "tag": 1226,
          "value": "777777777778"
        }
      ]
    },
    {
      "type": "COUNTABLE",
      "name": "С комиссионером",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
"price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 32
        },
        {
          "tag": 1171,
          "value": "+79101179452"
        },
        {
          "tag": 1225,
          "value": "Наименование поставщика комиссионера"
        },
        {
          "tag": 1226,
          "value": "888888888889"
        }
      ]
    },
    {
      "type": "COUNTABLE",
      "name": "С агентом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1057,
          "value": 64
        },
        {
          "tag": 1171,
          "value": "+79101179453"
        },
        {
          "tag": 1225,
          "value": "Наименование поставщика агента"
        },
        {
          "tag": 1226,
          "value": "999999999990"
        }
      ]
    },
    {
      "type": "SERVICE",
      "name": "С акцизом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1229,
          "value": 3
        },
        {
          "tag": 1230,
          "value": "123"
        },
        {
          "tag": 1231,
          "value": "Код 123"
        }
      ]
    },
    {
      "type": "SHOES",
      "name": "С кодом товара",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1162,
          "value": "1520043f52d350383277666C345066453973707575"
        }
      ]
    },
    {
      "type": "SERVICE",
      "name": "С дополнительным реквизитом",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100,
      "tags": [
        {
          "tag": 1191,
          "value": "Доп. рек. позиции"
        }
      ]
    },
    {
      "type": "SERVICE",
      "name": "Без тегов",
      "quantity": 1,
      "tax": "NDS_NO_TAX",
      "price": 100
    }
  ],
  "taxMode": "SIMPLE_WO",
  "tags": [
    {
      "tag": 1085,
      "value": "Доп. рек. пользователя"
    },
    {
      "tag": 1086,
      "value": "Значение доп. рек. пользователя"
    },
    {
      "tag": 1192,
      "value": "Доп. реквизит чека (БСО)"
    }
  ]
}
```