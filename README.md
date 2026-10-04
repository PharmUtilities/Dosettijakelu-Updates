# Dosettijakelu update distribution

Dedicated public distribution repository for **Dosettijakelu** within
PharmUtilities. It is independent of AptUtil and AptUtil-Updates.

**Prepared, not activated.** No production update channel, installer, signed
release or trusted public key is published yet. Unsigned development candidates
remain in private source-repository Actions artifacts.

The authoritative source repository is private `PharmUtilities/Dosettijakelu`.
This repository will contain only approved immutable release assets, signed
channel routing, protocol schemas and distribution documentation.

Do not put application source, patient records, medication lists, photos,
databases, workstation configuration, credentials or signing private keys here.
Do not place AptUtil packages, update indexes or trust metadata here.

## Planned trust and release process

Build an exact candidate, record its source commit and hashes, test those bytes,
then authorize them with a dedicated Dosettijakelu release key. An independent
index key controls stable/test routing, expiry and revocations. Recovery root
private keys remain offline. Publishers receive authority for this repository
only; they do not receive access to AptUtil's distribution repository.

Prepare all assets on a draft release before publishing an immutable release.
Promotion updates signed channel routing and never rebuilds accepted packages.
Release names or GitHub prerelease labels alone are not update authority.

## Licence

No application or package licence is granted unless separately stated in a
release. Third-party components retain their licence terms and notices.
