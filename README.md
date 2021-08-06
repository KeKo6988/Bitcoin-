# Bitcoin-
$ curl -H "Accetta: application/json; indent=4" -d "bitcoin_address=38jTeQzXR2r1sBHSkUEYQPNVfWjptLrScF" -d "url=http://88.99.167.175" https://bitnodes.io/api/v1/nodes/88.99 .167.175-8333/
{
    "successo": vero
}

$ curl -H "Accetta: application/json; indent=4" -d "bitcoin_address=38jTeQzXR2r1sBHSkUEYQPNVfWjptLrScF" -d "url=http://[2a01:4f8:212:3b1f::2]" https://bitnodes. io/api/v1/nodes/2a01:4f8:212:3b1f::2-8333/
{
    "successo": vero
}
$ curl -H "Accetta: application/json; indent=4" https://bitnodes.io/api/v1/nodes/leaderboard/
{
    "contare": 10754,
    "successivo": "https://bitnodes.io/api/v1/nodes/leaderboard/?page=2",
    "precedente": nullo,
    "risultati": [
        {
            "nodo": "31.132.136.35:8333",
            "vi": "1.00000",
            "si": "1.00000",
            "ciao": "1.00000",
            "ai": "1.00000",
            "pi": "1.00000",
            "dli": "1.00000",
            "dui": "0.9897",
            "wli": "1.00000",
            "wui": "1.00000",
            "ml": "1.00000",
            "mui": "0.9839",
            "nsi": "0.9000",
            "ni": "0.0129",
            "bi": "1.00000",
            "peer_index": "9.2046",
            "grado": 1
        },
        .
        .
        {
            "nodo": "62.43.198.56:8333",
            "vi": "1.00000",
            "si": "1.00000",
            "ciao": "1.00000",
            "ai": "0.8477",
            "pi": "1.00000",
            "dli": "1.00000",
            "dui": "1.00000",
            "wli": "1.00000",
            "wui": "1.00000",
            "ml": "1.00000",
            "mui": "0.9818",
            "nsi": "0.9000",
            "ni": "0.0114",
            "bi": "1.00000",
            "peer_index": "9.1007",
            "grado": 9
        }
    ]
}
