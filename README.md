 ansible und openstack Vortrag #toolbox
==================================

Hier gibt es die Vortrags-Daten und -Folien/Diagramm zum Vortrag über Ansible und OpenStack in der Toolbox am Tag der offenen Tür 2018 (L3D und Matt)


 Übersicht des Vortrages:
--------------------------
Geplanter Zeitslot: ``13:30 - 14:30``
grobe Vortragsaufteilung:
  + ~13 Minuten ansible
  + ~33 Minuten OpenStack
  + ~15 Minuten Fragen

 Ansible Vortragsaufbau
-------------------------
 + Erklärung was Ansible ist
 + Wie es funktioniert
 + was man alles mit machen kann...
 + Beispiel zeigen (mit [asciinema](https://asciinema.org/) als Komandozeile um F\*ckups zu vermeiden...)
   + Beispiel ist vermutlich der [Waffelzähler](https://github.com/ToolboxBodensee/ansible-waffelzaehler)
 
  run the themo with this command:
```bash
asciinema play -i 2.5 cast-ansibel.cast
```  
   
 Openstack Vortragsaufbau
-------------------------
 + Was ist Openstack - Funktion - Aufbau (die Openstack-Komponenten) - Zusammenspiel der Komponenten - Historie und Versionen
   (https://www.draw.io/#HToolboxBodensee%2Fansible-openstack-vortrag-TdoT%2Fmaster%2FUntitled%20Diagram.xml)
 + Welche Hardware verwenden wir dafür in der Toolbox und wie sieht die aus? + Vernetzung
 + Openstack mit Ansible aufsetzen...sehr sehr langes Thema - sind ingesamt unfassbare 36 Ansible-Rollen und 88 Playbooks!
 + Wie haben wir das in der Toolbox gemacht? - Openstack-Helm verwendet, zur ersten Installation einfachere Version. Baut auf Kubernetes      auf und verwendet Docker, um die einzelenen Openstack-Komponenten auf einem einzigen (unserem) Server laufen zu lassen
 + läuft auch in der Toolbox (Beispiel) - openstack live zeigen
 + Anmelden, einloggen und anlegen einer Beispiel-VM, eigenen Webserver installieren.
 + Future Work - was sind unsere nächsten Schritte (2 neue/weitere Server, bestehende Installation erweitern, Ansible Rollen an Toolbox      anpassen, IPv6-Adressvergabe, VMs von aussen erreichbar machen, Sicherheit...)
