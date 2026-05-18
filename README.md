# Lab_14_MobileSecurity
# LAB-14-Bypass-Root-Detection-sur-Android-Techniques-Dynamiques-avec-Frida-Objection-et-Hooks-Natif
## Étape 1 — Préparer l’
![](./images/047e7016-2c28-4cce-995b-5ce8860024bc)
![](./images/7c230d07-e269-43ef-84dd-5ce5112472b4)
![](./images/a67a9857-ef39-4c57-ad5b-8e0e62390f3b)
## Étape 2 — Démarrer frida-server sur l’appareil
![](./images/60ce9960-4666-49c8-8390-4440e81a0f1e)
![](./images/e74acdd8-be0a-4d0f-9312-85fbf5dc30d8)
![](./images/e7edca9a-ccb3-48a1-b221-f58db4ee763d)
![](./images/23760fff-ec33-4857-886e-026d5cf2bc77)
![](./images/3d08cd6c-6583-44b1-bf5d-90282d681ccb)
## Étape 3 — Frida: comprendre en 10 minutes
![](./images/3464e1fb-8687-4dbd-8469-ed321e799471)
![](./images/3cbb2d3b-b16c-4e61-a8c8-05f0afd530f5)
## Étape 4 — Bypass de la détection de root avec Frida
![](./images/d30a6b64-1e4c-4a0d-9da4-9aef4b017bcc)
![](./images/a9934350-cce2-4b8d-a512-d166f2528b76)
## Étape 5 — Faire la même chose plus facilement avec Objection
![](./images/d2e4f7f2-cd6e-4ae4-9b27-9abc85321bef)
![](./images/ff50ed70-221d-47bc-aa61-3fa4671118e2)
## Étape 6 — Medusa
![](./images/bb13b96b-477e-42d4-82ad-8785659ad06b)
![](./images/99633242-cc3b-43bb-a986-00cdfd425c07)
## Étape 7 — Quand préférer Magisk
Magisk est utilisé lorsqu’on veut masquer le root directement au niveau du système Android, 
contrairement à Frida, Objection ou Medusa qui agissent uniquement à l’intérieur de l’application pendant son exécution. 
Il devient particulièrement utile lorsque les applications utilisent des protections avancées comme Play Integrity ou SafetyNet, ou lorsqu’elles vérifient des paramètres profonds du système
(propriétés Android, bootloader, environnement root). L’avantage de Magisk est qu’il permet un masquage global du root pour toutes les applications, sans avoir besoin d’injecter des scripts à chaque lancement. Cependant, 
certaines protections très fortes basées sur du matériel ou des vérifications strictes de type “strong integrity” restent difficiles, voire impossibles, à contourner uniquement avec cette approche.
