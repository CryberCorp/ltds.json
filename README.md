# 🌐 Liste exhaustive des TLDs 2025 (tlds.txt, tlds.json, tlds.ts)

> **Édition 2025 propre, extraite de [tld-list.com](https://tld-list.com/), libre d'utilisation**

---

## 🇫🇷 Description

Cette liste fournit **tous les TLDs mondiaux** (domaines de premier niveau), formatés pour un usage direct en `.txt`, `.json` et `.ts`.  
- **Sources :** données officielles et actualisées au 10 décembre 2025, issues de [tld-list.com](https://tld-list.com/)
- **Licence :** libre (MIT), partage et utilisation encouragés

### Cas d’utilisation

- Vérification de la validité d’un nom de domaine ou d’email
- Création d’autocomplétions ou de suggestions de domaines
- Analyses, filtres anti-spam, parsing, validation de TLD
- Recherche et documentation
- Intégration dans des outils web, scripts, apps, etc.

### Exemples

- Filtrer les emails avec des TLDs valides :
    ```js
    // Javascript
    import { tlds } from "./tlds.ts"
    function isValidTLD(email) {
      const tld = email.split('.').pop()
      return tlds.includes('.' + tld)
    }
    ```
- Utilisation avec Python ou bash :
    ```bash
    grep "\.dev$" tlds.txt
    ```

### Détails

- **Fichiers fournis :**
    - `tlds.txt`  : liste simple, un TLD par ligne
    - `tlds.json` : tableau JSON prêt à l’emploi
    - `tlds.ts`   : export ES module (`export const tlds = [...]`)
- **Aucune dépendance, usage immédiat**

---

## 🇬🇧 Description

This repository provides a **complete and up-to-date list of all worldwide TLDs (Top-Level Domains)**, formatted for direct use in `.txt`, `.json`, and `.ts` files.

- **Source:** Latest official data from [tld-list.com](https://tld-list.com/) (as of Dec 10, 2025)
- **License:** MIT (free, open, and reusable)

### Use cases

- Domain name or email validation
- Domain suggestion/autocomplete
- Filtering, anti-spam, parsing, validation tools
- Research, documentation, web development
- Integration in scripts, apps, web tools, etc.

### Examples

- Validate TLD in JavaScript :
    ```js
    import { tlds } from "./tlds.ts"
    const tld = email.split('.').pop()
    const valid = tlds.includes('.' + tld)
    ```
- Use in Python or bash :
    ```bash
    grep "\.ai$" tlds.txt
    ```

### Details

- **Provided files:**
    - `tlds.txt`  – one TLD per line
    - `tlds.json` – ready-to-use JSON array
    - `tlds.ts`   – ES module export (`export const tlds = [...]`)
- **No dependencies required, instant use**

---

## 🇪🇸 Descripción

Este repositorio ofrece una **lista completa y actualizada de todos los TLDs mundiales (dominios de nivel superior)**, lista para usar en `.txt`, `.json` y `.ts`.

- **Fuente:** [tld-list.com](https://tld-list.com/) (datos oficiales a fecha 10 diciembre 2025)
- **Licencia:** MIT (libre y reutilizable)

### Usos posibles

- Validar dominios o emails
- Sugerencias/autocompletado de dominios
- Filtros anti-spam, parsing, validaciones
- Análisis, documentación, desarrollo web
- Integración en scripts, apps, herramientas, etc.

### Ejemplos

- Validación en JavaScript:
    ```js
    import { tlds } from "./tlds.ts"
    const tld = email.split('.').pop()
    const valido = tlds.includes('.' + tld)
    ```
- Uso en Python o bash:
    ```bash
    grep "\.es$" tlds.txt
    ```

### Detalles

- **Archivos incluidos:**
    - `tlds.txt`  – un TLD por línea
    - `tlds.json` – array JSON listo
    - `tlds.ts`   – export ES module (`export const tlds = [...]`)
- **Sin dependencias, uso inmediato**

---

## ℹ️ Informations & License

- **Source principale** : [tld-list.com](https://tld-list.com/)  
- **Date de la dernière mise à jour** : 10 décembre 2025  
- **Licence** : MIT – libre d’usage, partagez, réutilisez  
- **Aucune donnée personnelle, purement technique**  
- **Contact / suggestions** : issues GitHub

---

> ⚡️ Maintenu pour la communauté – n’hésitez pas à contribuer ou à signaler une mise à jour si la liste évolue !

