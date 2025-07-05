Kullanıcının girdiği sayısal bir ifadeye karşılık gelen harf kombinasyonlarını oluşturur ve bunlar arasında sözlükte bulunanları ekrana yazdırır.
Bu program, telefon tuş takımlarındaki gibi harflere karşılık gelen rakamları kullanarak, girdiğiniz rakam dizisinin oluşturabileceği anlamlı kelimeleri bulmak için yazılmıştır. Bu, T9 kelime tahmin sistemlerine benzer bir işlemdir.
Sözlüğü okur: dictionary.txt dosyasından kelimeleri alır ve belleğe yükler.
Kelime ağacı (Trie) oluşturur: insertWord() fonksiyonu, her kelimeyi rakamsal karşılığına göre Trie veri yapısına yerleştirir.
Kullanıcıdan sayı girişi alır.
Girilen sayıya karşılık gelen harf kombinasyonlarını dener (findWordsUtil()), bu kombinasyonların Trie’de olup olmadığını kontrol eder.
Eğer Trie'deki yol bir kelimenin sonunu gösteriyorsa ve bu kelime sözlükte varsa, sonucu yazdırır.
