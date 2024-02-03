meme_dict = {
            "CRINGE": "Algo excepcionalmente raro o embarazoso",
            "LOL": "Una respuesta común a algo gracioso",
            "idk": "yo que se",
            "WEON": "amigo, persona, objeto, estupido, para nombrar a alguien, usa situacion tonta, estupuda o frustrante",
            "A": "respuesta con significado neutro ante algo",
            "CHAMBA": "trabajo",
            }
word = input("Escribe una palabra que no entiendas (¡con mayúsculas!): ")
if word in meme_dict.keys():
    print(meme_dict[word])
else:
    # ¿Qué hacer si no se encuentra la palabra?
    print("no se encontro la palabra")
