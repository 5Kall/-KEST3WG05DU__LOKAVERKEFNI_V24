### 1. IP-úthlutun og DHCP
   - Stýrikerfið á útstöðinni þarf að fá IP-tölu frá DHCP með netmaskanum 192.168.10.0/24. 
   - LAN IP-talan á servernum á að vera fyrsta nothæfa talan á netinu. 
   - Síðustu 15 tölur netins eru úthlutaðar með DHCP.

### 2. Active Directory skráning yfir starfsmenn
   - Yfirmenn þurfa að skrá sig í Active Directory.
   - Forstjóri er yfirmaður allra deildarstjóra.
   - Deildarstjórar eru yfirmenn starfsmanna sinnar deildar.

### 3. Remote Desktop innritun
   - Allir notendur geta loggað sig inn með Remote Desktop á útstöðina.

### 4. Start Screen í stað Desktop
   - Í UT síu skal sjálfkrafa koma upp Start Screen í stað Desktop þegar tengt er við útstöðina.

### 5. Eigin möppur og My Documents
   - Hver starfsmaður þarf að fá sína eigin möppu á servernum.
   - My Documents möppa hverrar notanda á að vísa á serverinn.
   - Möppan skal mappast sem H: drifbókstafur.

### 6. Sameiginlegar möppur og drifbókstafir
   - Hver deild á að eiga sameiginlega möppu á servernum.
   - Möppan á að mappast sem R: drifbókstafur.
   - Tryggja að starfsmaður einnar deildar komist ekki í möppu annarrar deildar.
   - Allir hafa aðgang að sameiginlegri möppu sem mappast sem S: drifbókstafur.

### 7. Möppa fyrir stjórnendur á sameiginlega drifinu
   - Á sameiginlega drifinu S: á að vera möppan Stjórnendur.
   - Eingöngu forstjóri og deildarstjórar hafa aðgang að henni.
   - Þeir hafa bæði les- og skrifaðgang að möppunni.
   - Möppan skal ekki deila með öðrum.

### 8. Firefox uppsetning
   - Allar tölvur eiga að hafa Firefox uppsett.
   - MSI skráin er á \\skra\sameign\win.

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

### 15. Disknotkunar kvóta
   - Setjið kvóta á 10MB disknotkun hjá öllum notendum.

### 16. Internet Explorer ræsingu
   - Þegar notendur í UT tengjast útstöð ræsist Internet Explorer sjálfkrafa.

### 17. Innskráningartakmarkanir fyrir framleiðsludeild
   - Notendur í framleiðsludeild geta ekki loggað sig inn á Windows útstöð frá kl. 16:00 á föstudögum til kl. 08:00 á mánudögum.
