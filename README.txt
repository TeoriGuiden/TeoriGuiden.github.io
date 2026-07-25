TEORIGUIDEN WEBSITE – TJEKLISTE FØR OFFENTLIGGØRELSE

1. Søg i alle filer efter:
   [UDFYLD
   [INDSÆT
   [RET
   [ANGIV
   [HVIS

2. Udfyld som minimum:
   - TeoriGuiden ApS' CVR-nummer
   - Virksomhedens juridiske adresse
   - Telefonnummer
   - Dato for privatlivspolitik og vilkår
   - Reel svartid for support
   - App Store-link, når appen er oprettet
   - Præcis sti til "Slet konto" i appen
   - Reel slettefrist og backupperiode
   - Om Firebase Analytics og Crashlytics anvendes
   - Om brugerens fremgang gemmes lokalt eller i Firebase

3. App Store Connect:
   - Support URL: https://DIT-DOMÆNE/support.html
   - Privacy Policy URL: https://DIT-DOMÆNE/privatlivspolitik.html
   - Marketing URL: https://DIT-DOMÆNE/ (valgfri, men nyttig)
   - Terms of Use: link til vilkaar.html i appens metadata/purchase flow,
     hvis appen har automatisk fornyende abonnement.
   - User Privacy Choices URL: kan pege på slet-konto.html eller en samlet
     side for privatlivsvalg. Feltet er valgfrit.
   - App Privacy-svar skal matche den faktiske app og alle SDK'er.

4. Inde i appen:
   - Synligt link til privatlivspolitikken
   - Synligt link til vilkår fra abonnements-/købsskærmen
   - Gendan køb
   - Administrér/opsig abonnement
   - Start sletning af konto direkte i appen
   - Tydelig pris, periode og automatisk fornyelse i købsskærmen

5. GitHub Pages:
   - Upload alle filer til roden af repository.
   - Aktivér Settings -> Pages -> Deploy from a branch.
   - Vælg main og /(root).
   - Test alle links på mobil.
   - Brug eget domæne og HTTPS, hvis muligt.

6. Vigtigt:
   - Denne version bruger ingen JavaScript, cookies eller webanalyse.
   - Tilføjes analyse eller marketing senere, skal cookie-/privatlivsteksten
     revurderes.
   - Privatlivspolitikken og App Store Privacy Label skal altid stemme overens
     med appens faktiske dataindsamling.
