meme_dict= {
            "CHRİNGE":"garip ya da utandırıcı bir şey",
            "LOL":"komik bir şeye verilen cevap",
            "ROFL":"bir şakaya karşılık cevap",
            "SHEESH":"onaylamamak",
            "CREEPY":"korkunç",
            }
word = input("Anlamadığınız bir kelime yazın (hepsini büyük harflerle yazın!): ").upper()
if word in meme_dict.keys():
    print(meme_dict[word])
else:
    print("aradığınız kelime bende bulunmuyor")
