### 1. IP-úthlutun og DHCP
   - Stýrikerfið á útstöðinni þarf að fá IP-tölu frá DHCP með netmaskanum 192.168.10.0/24. 
   - LAN IP-talan á servernum á að vera fyrsta nothæfa talan á netinu. 
   - Síðustu 15 tölur netins eru úthlutaðar með DHCP.

   - ![Static iptala](https://cdn.discordapp.com/attachments/1166754036557553676/1237425500893478922/image.png?ex=664625cd&is=6644d44d&hm=2d7399abc24325f0d64084d748262a5c305bea6c4af4a74e076c932aea9ec97c&)

   - ![Dhcp setup](https://media.discordapp.net/attachments/1166754036557553676/1240392674733850686/image.png?ex=66466533&is=664513b3&hm=d59ee4cef0e10b23d22bdfc4d7fe3e443679b53003eb39f4e686fba5ed93b81e&=&format=webp&quality=lossless&width=987&height=203)


### 2. Active Directory skráning yfir starfsmenn
   - Yfirmenn þurfa að skrá sig í Active Directory.
   - Forstjóri er yfirmaður allra deildarstjóra.
   - Deildarstjórar eru yfirmenn starfsmanna sinnar deildar.

   - ![Notendur](https://media.discordapp.net/attachments/770413099111022625/1240394723668004924/Screenshot_2024-05-02_103717.png?ex=6646671b&is=6645159b&hm=902f312436ff52b6adb3ef1c2099721ef3808874d81751160fd1a1f96de348af&=&format=webp&quality=lossless&width=785&height=592)

### 3. Remote Desktop innritun
   - Allir notendur geta loggað sig inn með Remote Desktop á útstöðina.

   - ![](https://media.discordapp.net/attachments/770413099111022625/1240397373641850972/image.png?ex=66466993&is=66451813&hm=378147eec7bc9d186c0ecb254619eb1bf3e0592a8231a7a230324eef7e352fca&=&format=webp&quality=lossless&width=502&height=369)

### 4. Start Screen í stað Desktop
   - Í UT síu skal sjálfkrafa koma upp Start Screen í stað Desktop þegar tengt er við útstöðina.

   - ![](https://media.discordapp.net/attachments/770413099111022625/1240396147156320267/image.png?ex=6646686e&is=664516ee&hm=fb9a515be0943e7b669bff972f02fd156ffd5807faff217b207e49322cc81c04&=&format=webp&quality=lossless&width=718&height=581)

### 5. Eigin möppur og My Documents
   - Hver starfsmaður þarf að fá sína eigin möppu á servernum.
   - My Documents möppa hverrar notanda á að vísa á serverinn.
   - Möppan skal mappast sem H: drifbókstafur.

   - ![moppur](https://media.discordapp.net/attachments/770413099111022625/1240399599114522644/image.png?ex=66466ba5&is=66451a25&hm=3305efce2aa0496c25b6843ff956409b80597e20273ef7f45113fa5a490e6dd8&=&format=webp&quality=lossless&width=716&height=511)

### 6. Sameiginlegar möppur og drifbókstafir
   - Hver deild á að eiga sameiginlega möppu á servernum.
   - Möppan á að mappast sem R: drifbókstafur.
   - Tryggja að starfsmaður einnar deildar komist ekki í möppu annarrar deildar.
   - Allir hafa aðgang að sameiginlegri möppu sem mappast sem S: drifbókstafur.

   - ![mynd](https://media.discordapp.net/attachments/770413099111022625/1240405344316952677/image.png?ex=664670ff&is=66451f7f&hm=2de5d1261309136748438453300c78823fedd4d06effee5385a7dbba6d123fb4&=&format=webp&quality=lossless&width=717&height=579)

### 7. Möppa fyrir stjórnendur á sameiginlega drifinu
   - Á sameiginlega drifinu S: á að vera möppan Stjórnendur.
   - Eingöngu forstjóri og deildarstjórar hafa aðgang að henni.
   - Þeir hafa bæði les- og skrifaðgang að möppunni.
   - Möppan skal ekki deila með öðrum.

   - ![security stillingar](https://media.discordapp.net/attachments/770413099111022625/1240406699198644224/image.png?ex=66467242&is=664520c2&hm=e166c45113126c5a4070b79caa6a6d72d9008b09d5d8f9e601884e13e75c03c6&=&format=webp&quality=lossless&width=603&height=479)

### 8. Firefox uppsetning
   - Allar tölvur eiga að hafa Firefox uppsett.
   - MSI skráin er á \\skra\sameign\win.

   - ![group policy](https://media.discordapp.net/attachments/770413099111022625/1240408393718562916/image.png?ex=664673d6&is=66452256&hm=fdace03081b66372a28843b82b5e9e4189dccf0d29dbd24c5ceb3cb65cdb1597&=&format=webp&quality=lossless&width=717&height=581)

### 9. Firefox ræsingu takmörkun
   - Starfsmenn í framleiðsludeild eiga ekki að geta ræst Firefox.

### 10. Internet Explorer upphafssíða
   - Upphafssíða Internet Explorer á að vera Kauphöllin fyrir fjármáladeildina.

### 11. Favorites í Internet Explorer
   - Linkur á tskoli.is í Favorites möppunni fyrir alla notendur.

### 12. Admin réttindi fyrir UT starfsmenn
   - Starfsmenn í UT deild hafa full admin réttindi á öllum útstöðvum.

### 13. Sýna skráarendingar
   - Öllum notendum þarf að sýna allar skráarendingar (file extensions).

### 14. Upplýsingar á Desktop
   - Upplýsingar um nafn vélar, IP tölu og stærð minnis á Desktop hverrar notandavigurstöðu.
   - Notaðu BGInfo og logon script til að útfæra þetta.

   - ![upplysingar](https://media.discordapp.net/attachments/770413099111022625/1240410579915771954/image.png?ex=664675df&is=6645245f&hm=3f8ce5937f0e358bd2d34bb618b1f5bebc16a45eaee5135c52aed38f28591a02&=&format=webp&quality=lossless&width=341&height=262)

### 15. Disknotkunar kvóta
   - Setjið kvóta á 10MB disknotkun hjá öllum notendum.

   - ![Diskanotkunar kvóta](https://media.discordapp.net/attachments/770413099111022625/1240408892912177182/image.png?ex=6646744d&is=664522cd&hm=6603cd78ffc6e3cd09eb53b0c6d3393227cdaa3ba9c2e18d3a47375eb1824f0b&=&format=webp&quality=lossless&width=714&height=578)

### 16. Internet Explorer ræsingu
   - Þegar notendur í UT tengjast útstöð ræsist Internet Explorer sjálfkrafa.

### 17. Innskráningartakmarkanir fyrir framleiðsludeild
   - Notendur í framleiðsludeild geta ekki loggað sig inn á Windows útstöð frá kl. 16:00 á föstudögum til kl. 08:00 á mánudögum.
