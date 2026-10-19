# Cobblemon Daycare v0.15.0 BETA — TEST ONLY

Changes: automatic egg production every 10 minutes per compatible pen into egg bag (max 32), with wall-clock catch-up while owner is online; eggs never hatch at generation; withdrawal to party if room, else PC.

Important: **NOT CRASH-PROOF**. The custody/party/PC updates are not a single atomic transaction. A crash during a transfer may leave a duplicate or a recovery problem. Test only on an isolated server with disposable Pokemon and full backups. Egg/PC persistence also needs validation. No claim of full anti-duplication or four complete safeguards.

Build on GitHub with bundled Actions workflow. Do not use on production.
