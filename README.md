# azurepipelines-reactnative-android-build-mobsf
Exemplo de pipeline do Azure DevOps em ambiente macOS para build de um app React Native em Android. Inclui ainda o uso de um container do serviço MobSF, a fim de detectar vulnerabilidades no arquivo .apk gerado durante o build.

Links importantes:
- Mobile Security Framework (MobSF): https://github.com/MobSF/Mobile-Security-Framework-MobSF
- Imagens do MobSF no Docker Hub (as análises são executadas a partir de containers): https://hub.docker.com/r/opensecurity/mobile-security-framework-mobsf/ 

---

## Evidências dos testes

Arquivo SARIF (gerado via PowerShell):

![Visualização do arquivo SARIF](img/sarif-01.png)

Report PDF gerado via MobSF:

![Visualização do arquivo SARIF 1](img/pdf-01.png)

![Visualização do arquivo SARIF 2](img/pdf-02.png)

![Visualização do arquivo SARIF 3](img/pdf-03.png)

![Visualização do arquivo SARIF 4](img/pdf-04.png)