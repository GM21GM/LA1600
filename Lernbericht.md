#Lern-Bericht
##Einleitung
Unser Projekt war es eine Website zu erstellen auf der man eine Auswahl an Spielen vorfindet.
Was haben wir gelernt?
Wir haben gelernt, wie man @media-Regeln verwendet, um das Layout einer Webseite an verschiedene Bildschirmgrößen anzupassen.

##Beschreibung
Textliche Beschreibung
Bei der Erstellung einer Webseite ist es wichtig, dass sie auf verschiedenen Geräten gut aussieht und benutzerfreundlich ist. Mit Hilfe von @media-Regeln in CSS kann das Layout einer Webseite basierend auf der Bildschirmgröße des Geräts angepasst werden.

Ein Beispiel für die Verwendung von @media-Regeln ist die Erstellung einer responsiven Navigation. Bei größeren Bildschirmen kann die Navigation horizontal angezeigt werden, während sie bei kleineren Bildschirmen vertikal angezeigt wird. Durch die Verwendung von @media-Regeln können spezifische CSS-Stile für verschiedene Bildschirmgrößen definiert werden.

![image](https://github.com/GM21GM/LA1600/assets/111045891/fff16e15-bbc2-4761-a5cb-0c62e2a56859) ![image](https://github.com/GM21GM/LA1600/assets/111045891/154306f6-50cb-45c9-97c9-7a1bb8c30f34)




Code-Fetzen
``` css
@media (max-width: 1000px) {
  .gridcontainer {
    display: grid;
    grid-template-columns: auto 20%;
    grid-template-rows: auto auto auto 50px;
  }

  header {
    grid-row: 1 / span 1;
    grid-column: 1 / span 2;
  }

  nav {
    grid-row: 2 / span 1;
    grid-column: 1 / span 2;
  }

  main {
    grid-row: 3 / span 1;
    grid-column: 1 / span 1;
  }

  aside {
    grid-row: 3 / span 1;
    grid-column: 2 / span 1;
  }

  footer {
    grid-row: 4 / span 1;
    grid-column: 1 / span 2;
  }
}

```

Verifikation
Die textliche Beschreibung erklärt den Zweck und die Verwendung von @media-Regeln in CSS, um das Layout einer Webseite responsiv zu gestalten.

Das Bild veranschaulicht die Auswirkungen der Verwendung von @media-Regeln auf das Layout einer Webseite und zeigt die Anpassung basierend auf der Bildschirmgröße.

Die obige @media-Query wird angewendet, wenn die maximale Bildschirmbreite 1000px beträgt. Innerhalb dieser @media-Query werden bestimmte Anpassungen am Grid-Layout vorgenommen, um es besser für kleinere Bildschirme geeignet zu machen. Die Elemente Header, Navigation, Hauptinhalt, Seitenleiste und Footer werden neu positioniert, um eine optimale Darstellung auf mobilen Geräten zu ermöglichen.
Zusammen liefern diese Medien einen umfassenden Überblick über das gelernte Konzept der Verwendung von @media-Regeln für responsives Webdesign.

Reflexion zum Arbeitsprozess
👍 Etwas, was gut lief: Die Teammoral blieb stetig hoch, da man trotz Problemen sich versucht hat zu unterstützen und zu motivieren.

👎 Etwas, was nicht gut lief: Der Gruppenleiter konnte seine Rolle nicht gut bewältigen, was zu einem teilweise chaotischem Projekt führte.

Verbesserungsvorschlag: Damit das beim nächsten Mal nicht passsiert sollte der Gruppenleiter früh kommunizieren, dass er es nicht schaffen wird.
