import socket
import requests
import geocoder

print("Örnek Website: https://google.com")
url = input("Website giriniz: ")
httporhttps = url[:7]
httporhttps2 = httporhttps.find("s")

if httporhttps2 == -1:
        ipadd = socket.gethostbyname(url[7:])
        g = geocoder.ipinfo(ipadd)
        print("Ülke: ",g.country)
        print("Şehir: ", g.city)
elif httporhttps2 != -1:
        ipadd = socket.gethostbyname(url[8:])
        g = geocoder.ipinfo(ipadd)
        print("Ülke: ",g.country)
        print("Şehir: ", g.city)


else:

        print("Hatalı giriş...")
        
