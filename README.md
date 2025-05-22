

<!DOCTYPE html>
<html lang="ro">
<body>
  <article>
    <header>
      <h1>Documentație HCI - LegoMR</h1>
      <p>Autori: Lăcătuș Ștefania, Iacobuț Denisa-Delia</p>
    </header>
    <section id="introducere">
      <h2>1. Introducere</h2>
      <p>În această documentație sunt prezentate pattern-urile folosite pentru interacțiuni, deciziile de proiectare și un manual de instrucțiuni pentru aplicația LegoMR, aplicație ce este disponibilă atât pentru mobil cât și pentru VR/MR. Aceasta poate fi utilizată atât de un părinte alături de copilul său cât și de un adolescent ce dorește să construiască și să descopere lumea Lego într-un mod interactiv. Aplicația LegoMR te captează într-o lume a jocului și îți oferă posibilitate de a te relaxa și destinde prin diversele opțiuni disponibile. Oferă atât instrucțiuni și ajutor pentru construcție cât și posibilitatea de a da viață figurinelor construite printr-un joc. Aceste funcții sunt disponibile în aplicația mobile dar și în VR.</p>
      <p>Obiectivul principal este de a facilita colaborarea, de a simplifica procesul de construire și de a adăuga o caracteristică interactivă prin jocuri virtuale.</p>
    </section>
    <section id="modele-proiectare-interactiune">
      <h2>2. Modele de proiectare a interacțiunii</h2>
      <p>Proiectarea interacțiunii se bazează pe principii HCI (Human-Computer Interaction) și modele de design care pun în prim plan colaborarea și utilizarea mai interactivă. Printre modelele utilizate se numără:</p>
      <ul>
        <li><strong>Modelul „Choice-Based Navigation” (Navigare bazată pe selecție)</strong>: Atât aplicația mobilă, cât și cea VR permit utilizatorilor să aleagă între construirea unei figurine LEGO sau încercarea unui joc virtual. Utilizatorii au la dispoziție o listă cu previzualizări vizuale ce fac ca deciziile să fie mai rapide și informate.</li>
        <li><strong>Modelul „Progressive Disclosure” (Dezvăluire progresivă)</strong>: În aplicația mobilă, pașii de construire sunt afișați secvențial, cu instrucțiuni detaliate pentru fiecare pas și butoane „<-” și „->” pentru navigare. Acest model reduce supraîncărcarea cognitivă, prezentând doar informațiile relevante pentru pasul curent.</li>
        <li><strong>Modelul „Augmented Step-by-Step Guidance” (Ghidare augmentată pas cu pas)</strong>:În aplicația VR, instrucțiunile de construire sunt suprapuse pe setul LEGO fizic, evidențiind piesele necesare și pozițiile lor. Butonul „Done” confirmă finalizarea construcției.</li>
        <li><strong>Modelul „Content Personalization” (Personalizare conținut)</strong>: Aplicația mobilă permite adăugarea figurinelor la favorite și explorarea alternativelor de construcție cu aceleași piese. Acest model susține creativitatea utilizatorilor prin oferirea de opțiuni flexibile și personalizate.</li>
        <li><strong>Modelul „Gamified Transition” (Tranziție gamificată)</strong>: După finalizarea unei figurine, ambele aplicații oferă opțiunea de a juca un joc virtual asociat figurinei. Instrucțiunile jocului sunt accesibile înainte de start, utilizând un model de tip „Tutorial Preview” pentru a pregăti utilizatorii.</li>
        <li><strong>Modelul „User Profile Management” (Gestionarea profilului utilizatorului)</strong>: Aplicația mobilă include o secțiune de setări cu butoane pentru „Schimbă parolă” și „Schimbă nume”, care duc la formulare de actualizare cu validare prin buton, asigurând o gestionare sigură și intuitivă a datelor utilizatorului.</li>
        <li><strong>Modelul „Historical Record Navigation” (Navigare în istoricul înregistrărilor)</strong>: Aplicația mobilă oferă o funcție „Istoric” care afișează o listă cronologică a figurinelor construite, cu detalii precum timpul de finalizare și nivelul de dificultate, permițând utilizatorilor să reviziteze proiectele anterioare.</li>
        <li><strong>Modelul „Informative Metadata Display” (Afișare metadate informative)</strong>: Nivelul de dificultate al fiecărei figurine și joc este afișat în meniul de selecție, folosind indicatori vizuali (stele) pentru a ghida alegerea utilizatorilor. La finalizarea unei figurine este afișat timpul ce a fost necesar pentru construcție. </li>
      </ul>
    </section>
    <section id="decizii-proiectare">
      <h2>3. Decizii de proiectare</h2>
      <p>Deciziile de proiectare au fost luate pentru a optimiza experiența utilizatorilor, pentru a susține colaborarea și pentru a spori implicarea în contextul descoperirii frumuseții LEGO: </p>
      <ul>
        <li><strong>Interfață simplă pentru aplicația mobilă</strong>: Interfața folosește un design minimalist cu butoane mari și text clar pentru a oferi o interacțiune mai intuitivă.</li>
        <li><strong>Opțiuni flexibile pentru figurine</strong>: Pentru figurinele selectate în aplicația mobilă, utilizatorii pot alege între „Start”, „Adaugă la favorite” sau „Alternative”. Aceste opțiuni sunt prezentate ca butoane mari, clar etichetate. Motiv: Susțin personalizarea și creativitatea, permițând utilizatorilor să exploreze variații fără a devia de la mediul principal.</li>
       <li><strong>Navigare secvențială în pașii de construire</strong>: În aplicația mobilă, instrucțiunile de construire sunt afișate pas cu pas, cu butoane „->” și „<-” plasate vizibil în partea de jos a ecranului. Motiv: Reduce erorile și oferă control clar asupra progresului.</li>
        <li><strong>Integrare jocuri virtuale</strong>: După finalizarea unei figurine, ambele aplicații oferă un buton „Încearcă joc” sau „Simulare” care lansează un joc virtual asociat. Instrucțiunile jocului sunt disponibile printr-un buton „Instrucțiuni” înainte de start. Motiv: Crește implicarea utilizatorilor prin conectarea construcției fizice cu experiențe interactive.</li>
        <li><strong>Gestionarea setărilor utilizatorului</strong>: Secțiunea „Setări” din aplicația mobilă include butoane pentru „Schimbă parolă” și „Schimbă nume”, care deschid formulare cu validare prin buton, și „Istoric” care afișează o listă a figurinelor construite, cu detalii precum timpul alocat și dificultatea. Motiv: Asigură o experiență personalizată și permite utilizatorilor să reviziteze proiectele anterioare.</li>
        <li><strong>Afișarea nivelului de dificultate</strong>: Nivelul de dificultate este afișat în meniul de selecție pentru figurine și jocuri, folosind indicatori vizuali stele. Motiv: Ajută utilizatorii, în special adolescenții, să aleagă activități potrivite nivelului lor de experiență.</li> 
      </ul>
    </section>
    <section id="manual-utilizare">
      <h2>4. Manual de utilizare</h2>
      <section id="manual-aplicatie-mobila">
        <h3>4.1 Aplicația mobilă</h3>
        <ol>
          <li><strong>Instalare și autentificare</strong>: Descărcați aplicația din App Store sau Google Play și conectați-vă cu un cont LEGO.</li>
          <li><strong>Selecția figurinei sau jocului</strong>: În meniul principal, alegeți o figurină sau un joc. Fiecare opțiune afișează o previzualizare și nivelul său de dificultate.</li>
          <li><strong>Gestionarea figurinelor</strong>: Pentru o figurină selectată, apăsați „Start” pentru a începe construirea, „Adaugă la favorite” pentru a o salva sau „Alternative” pentru a explora alte modele cu aceleași piese.</li>
          <li><strong>Construirea figurinei</strong>: Urmați instrucțiunile pas cu pas, care includ imagini și animații 3D. Navigați folosind butoanele „<-” și „->” din partea de jos a ecranului.</li>
          <li><strong>Joc virtual</strong>: După finalizarea figurinei, apăsați „Încearcă joc” pentru a lansa un joc asociat. Accesați „Instrucțiuni” pentru a citi regulile jocului înainte de a începe.</li>
          <li><strong>Setări</strong>: Accesați „Setări” din meniu și selectați:
            <ul>
              <li>„Schimbă parolă” pentru a actualiza parola. Completați formularul și apăsați „Save” sau „Back” pentru a te întoarce la pagina principală.</li>
              <li>„Schimbă nume” pentru a actualiza numele sau username-ul. Completați formularul și apăsați „Save” sau „Back” pentru a te întoarce la pagina principală.</li>
              <li>„Istoric” pentru a vedea o listă cronologică a figurinelor construite, cu detalii precum timpul necesar finalizării și nivelul de dificultate.</li>
            </ul>
          </li>
        </ol>
      </section>
      <section id="manual-aplicatie-mr">
        <h3>4.2 Aplicația pentru ochelari MR</h3>
        <ol>
          <li><strong>Configurare</strong>: Porniți ochelarii MR și instalați aplicația LEGO MR din magazinul de aplicații al dispozitivului.</li>
          <li><strong>Calibrare</strong>: Poziționați ochelarii și calibrați spațiul de lucru scanând setul LEGO fizic cu camera integrată.</li>
          <li><strong>Selecția figurinei sau jocului</strong>: În meniul principal, alegeți o figurină sau un joc din lista de opțiuni, afișată cu previzualizări vizuale și nivelul de dificultate.</li>
          <li><strong>Construirea figurinei</strong>: Activați modul pentru a vedea suprapunerile vizuale care indică poziția pieselor și pașii de asamblare. Apăsați butonul „Done” pentru confirmarea finalizării construcției.</li>
          <li><strong>Joc virtual</strong>: După finalizarea figurinei, selectați „Simulate” pentru a lansa un joc virtual asociat.</li>
        </ol>
      </section>
    </section>
    <section id="concluzii">
      <h2>5. Concluzii</h2>
      <p>Aplicațiile descrise facilitează colaborarea între părinte și adolescent prin integrarea tehnologiei mobile și MR în procesul de construire LEGO. Modelele de proiectare, cum ar fi navigarea bazată pe selecție, ghidarea augmentată și afișarea istoricului, reduc complexitatea, iar deciziile de design, precum afișarea nivelului de dificultate și gamificarea, sporesc implicarea. Manualul de utilizare oferă instrucțiuni clare, potrivite pentru utilizatori de toate vârstele. Limitările includ dependența de dispozitive compatibile și necesitatea unei dorințe de a fi captivat în lumea Lego.</p>
    </section>
    <section id="AI">
      <h2>Ajutor AI</h2>
      <p>Am folosit AI pentru idei interfață MR, la resurse pentru aplicații similare, idei pentru modelele de proiectare și alte idei de implementare. </p>
    </section>
  </article>
</body>
</html>
