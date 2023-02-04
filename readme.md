### Função de chamadas dos cards
@showcards(menu_001)

- O playload é o corpo, 

- Chamada do playload @showcards(menu_001)

```
{
    "soulmachines": {
        "menu_001": {
            "type": "options"
        }
    }
}
```

- O Playload é uma strutura de dados em Json, o corpo editável é apartir da indice data, para montar

```
 "data": {
    "options": [
        {
            "value": "1",
            "label": "1 - Confirmação de minha Viagem"
        },
        {
            "label": "2 - Alteração na Reserva",
            "value": "2"
        },
        {
            "label": "3 - Cancelar minha Viagem",
            "value": "3"
        },
        {
            "label": "4 - Documentos Necessários para entrar na Nova Zelândia",
            "value": "4"
        }
    ]
}

```