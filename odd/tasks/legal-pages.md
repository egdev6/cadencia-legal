# Cadencia legal pages
Publish a standalone legal-information site; application code and data remain private.
Target: egdev6/cadencia-legal; local path /home/egdev/proyectos/cadencia-legal.

## Specs
S1. User: «qué urls de privacidad y términos pongo? no tengo ningunas».
S2. User: «el tema es que de momento la app es privada. No sé si la haré publica. No tengo dominio de momento. Qué podríamos hacer para configurarlo temporalmente y completarlo cuando pueda?».
S3. User approved «¿Autorizás crear ese repositorio público y publicar las páginas?» with «si»; target egdev6/cadencia-legal, a homepage, privacy and terms, GitHub Pages, keeping Cadencia private.
S4. User selected «Sí, usar esa carpeta» for /home/egdev/proyectos/cadencia-legal and «Perfil de GitHub @egdev6» as public contact; do not publish an email address.

## Tasks
T1 | S1-S4 | done | writer: static homepage, privacy, terms; no app code or personal data | commit: 3b483d4
T2 | S1-S4 | done | parent: content/link/scope checks, authorized publication | commit: 3b483d4
T3 | S1-S4 | done | parent: HTTP 200 and expected titles for homepage/privacy/terms; CSS 200; Pages built and HTTPS enforced; app repository private | commit: 3b483d4 (site), closing evidence in subsequent docs commit

## Log
L1. User: «qué urls de privacidad y términos pongo? no tengo ningunas».
L2. User: «el tema es que de momento la app es privada. No sé si la haré publica. No tengo dominio de momento. Qué podríamos hacer para configurarlo temporalmente y completarlo cuando pueda?».
L3. Assistant offered creating public egdev6/cadencia-legal with homepage, privacy and terms and publishing on GitHub Pages, preserving the private application. User: «si».
L4. User authorized /home/egdev/proyectos/cadencia-legal and selected the public GitHub profile as contact. No email publication authorized.
L5. Created repository, verified isPrivate:false and exact matching origin. Cadencia source repository remains untouched. No Discord, notifications, labels, projects or governance workflows requested; optional bootstrap modules are omitted.
L6. Bootstrap plan succeeded with no actions; no apply needed. Writer T1 completed S1-S4. Parent read all served HTML, corrected ambiguous hosting-data wording, checked local link confinement and no secrets/placeholders. Incidental worker robots file preserved in ignored .local, excluded from publication. Date verified 2026-11-03. Legal content is factual information, not professional legal advice or a provider-approval guarantee.

L7. Job-56 passed: homepage, privacy/ and terms/ return HTTP 200 and expected titles; styles.css returns 200. GitHub Pages status built, HTTPS enforced, source main:/docs. GitHub API confirms egdev6/cadencia remains private. No TikTok console changes or provider approval claimed.
