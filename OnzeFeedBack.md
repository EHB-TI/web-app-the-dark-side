# Feedback


## Gebruikte tools


## Testen:
- DAST
    - Zed Attack Proxy(https://www.zaproxy.org/)
- SAST
    - Semgrep(https://semgrep.dev/)
    - Coverity(https://scan.coverity.com/)
    - SonarQube(https://www.sonarqube.org/features/security/)
- SCA
    - Dependabot(https://docs.github.com/en/code-security/supply-chain-security/managing-vulnerabilities-in-your-projects-dependencies/about-alerts-for-vulnerable-dependencies)
    - Snyk(https://snyk.io/test/)
    - npm audit(https://docs.npmjs.com/cli/v7/commands/npm-audit)

### Acceptance criteria

| Criteria                                                                              |  Passed | Notes |
| ------------------------------------------------------------------------------------- |  :----: | ----- |
| Als klant kan ik een account aanmaken | :white_check_mark: |
| Als klant kan ik mij inloggen op mijn account | :white_check_mark: |
| Als klant kan ik een overzicht zien van actuele en/of toekomstige films | :white_check_mark: |
| Als klant kan ik een beschrijving lezen van een film | :white_check_mark: |
| Als klant kan ik een programma zien van wanneer een film zal worden afgespeeld | :white_check_mark: |
| Als klant kan ik mijn klantgegevens wijzigen/bekijken | :x: |
| Als klant kan ik uitloggen van mijn account | :white_check_mark: |
| Als klant kan ik online tickets aankopen | :x: |
| Als klant kan ik me uitschrijven van de website | :white_check_mark: |
| Als beheerder kan ik inloggen op mijn account | :white_check_mark: |
| Als beheerder kan ik films toevoegen | :white_check_mark: |
| Als beheerder kan ik het programma aanmaken voor de films |  | Voegt geen ticket toe voor datum |
| Als beheerder kan ik uitloggen van mijn account | :white_check_mark: |
| Als beheerder kan ik me uitschrijven van de website | :x: |
| Als beheerder kan ik andere beheerders toevoegen | :x: |
| Als bezoeker kan ik een overzicht zien van actuele en/of toekomstige films | :white_check_mark: |
| Als bezoeker kan ik een beschrijving lezen van een film | :white_check_mark: |
| Als bezoeker kan ik een programma zien van wanneer een film zal worden afgespeeld | :white_check_mark: |

### HTTPS

### Aanmelden

### Wachtwoorden

### Web vulnerabilities
Er werden 5 alerts vermeld als uitkomst door de webpagina aan te vallen met behulp van ZAP.
Alerts:
- X-Frame-Options Header Not Set (medium risk)
- Incomplete or No Cache-control Header Set (low risk)
- Timestamps Disclosure – Unix (low risk)
- X-Content-Type-Options Header missing (low risk)
- Information Disclosure – Suspicious Comments (informational)

### REST API
Er werden 5 alerts vermeld als uitkomst door de webpagina aan te vallen met behulp van ZAP.
Alerts:
- Incomplete or No Cache-control Header Set (low risk)
- Timestamp Disclosure - Unix (low risk)

## Threat Model


## Aanbevelingen


## Bijlage
