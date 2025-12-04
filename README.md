# staticrypt-ga [![staticrypt status](https://github.com/royfrancis/staticrypt-ga/workflows/staticrypt/badge.svg)](https://github.com/royfrancis/staticrypt-ga/actions?workflow=staticrypt)

Every push to the `main` branch triggers a GitHub Actions workflow that runs StatiCrypt, encrypts every HTML file in `docs/` directory in place. The encryption password comes from the repository secret `STATICRYPT_PASSWORD`. After encryption, the workflow uploads `docs/` as a Pages artifact and deploys it to GitHub Pages, so the protected files are always available from the latest run.

Visit <https://www.royfrancis.com/staticrypt-ga/> and enter the password **mylongpassword** to view the encrypted site.

---

2026 • Roy Francis
