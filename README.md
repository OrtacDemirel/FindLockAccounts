Active Directory yapısında kilitlenen kullanıcı hesapları DC lerde ayrı ayrı kayıt altına alınmaktadır. Her DC ye ayrı ayrı bakmak ve ilgili kayıtları bulup okumak zor olabileceğinden bu işi daha pratik hale getiren bir program yazdım.

Hazırladığım bu program ile tek bir DC üzerinden tüm kilitlenen hesapları bulabilirsiniz. Ayrıca hangi kaynak üzerinden kilitlendiği de yazmaktadır.

Domain yapınızdaki herhangi bir DC üzerinden programı çalıştırmanız gerekmektedir. Çıktı da yer alan “Caller Computer Name” hangi kaynak üzerinden hesabın kitlendiğini göstermektedir.

Program kilitlenen hesapları en yakın kilitlenen hesaba göre tarih sırası ile göstermektedir.
