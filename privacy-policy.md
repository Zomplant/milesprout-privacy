# MileSprout Privacy Policy

Last updated: October 25, 2026

MileSprout is an Android mileage-tracking app published by ZomPlant Apps. This policy explains what information the app uses, what stays on your device, and when information may reach another service. For privacy questions, contact MileSprout@mail.com.

## Trips and location

MileSprout stores trip dates and times, distances, classifications, notes, and recorded GPS route points in the app's private storage on your device. It uses this information to record and display your trips, calculate mileage totals, and create exports. MileSprout does not provide a trip cloud-sync account.

You can enter a missed trip manually without granting location permission. If you use GPS recording, the app accesses your device's location to record a route. Automatic drive detection is optional. If you enable it and separately grant background location permission, the app can use location to detect and record drives when the app is closed or not in use, subject to Android's restrictions. You can turn automatic detection off in MileSprout or revoke location permission in Android Settings.

## Optional online map

Saved GPS routes can be previewed without downloading map tiles. If you choose Open Map, your device requests tiles from the OpenStreetMap Foundation's online tile service. Tile requests can reveal your network address, the map area and zoom level you view, and ordinary request information to that service and network intermediaries. MileSprout supplies the saved route to the map view locally; it does not put the full route into the tile request URL. You do not need the online map to record or save trips.

## Optional Google Play subscriptions

Google Play handles subscription purchases and payment information. MileSprout communicates directly with Google Play Billing to retrieve offers, complete and acknowledge purchases, and check subscription ownership. The app checks Google's purchase signatures on your device. MileSprout does not send purchase tokens to a ZomPlant Apps verification server. Subscription checks do not include your trip records or GPS route points.

MileSprout stores a subscription-status record on your device, including a SHA-256 digest of the purchase token rather than the raw token, the time of the last successful check, and an offline-access deadline. Previously confirmed access can continue for up to seven days without another successful check. Google processes payment and purchase information under its own privacy practices. Subscription management and cancellation are available through Google Play.

## Exports and sharing

You can create CSV or spreadsheet exports in MileSprout's app storage and save a copy to a location you choose. An export can include trip dates, mileage, classification, and start or end coordinates for GPS trips. If you choose Share, Android sends a copy to the app or destination you select. That destination handles the copy under its own terms and privacy practices. MileSprout does not automatically upload your trip records as part of exporting them. Report encryption is optional. When selected, the report is placed in an AES-encrypted ZIP file before saving or sharing; no separate unencrypted report file is written by that operation. The ZIP reveals a generic report filename and file sizes, but its report contents require the password. MileSprout does not save, send, or recover the password. Give it to recipients separately. They need software that supports AES-encrypted ZIP files. Unencrypted exports and copies extracted by recipients can be read by anyone with access to those files. Encrypting a new report does not protect previously saved or shared copies.

## Storage, retention, and deletion

Backup & restore lets you save a complete trip backup to a location you choose through Android's file picker. It includes trip dates and times, exact distances, classifications, notes, and full recorded GPS routes. Password protection is optional and selected by default when you create a backup. If you keep it on, the backup file is encrypted with a password you choose. If you turn it off, a warning explains that anyone with access to the unencrypted file can read your trip and location history. MileSprout does not save or send your backup password and cannot recover it. Keep both the file and its password, preferably storing the password in a password manager. Longer, unique passwords provide better protection. Unencrypted MileSprout backups, including older files, remain readable and are identified during preview; creating a new encrypted backup does not encrypt or delete old copies. A storage provider you choose may transfer or store the file under its own privacy practices. MileSprout does not automatically upload backups. Restoring decrypts password-protected backups in memory and reads the selected trips into local app storage after you confirm; existing trips are kept. Backup encryption protects the backup file, not the app's local trip database or CSV and spreadsheet reports. Backups do not contain subscription purchase tokens, phone permissions, or app settings. Temporary working files are removed after the operation; an interrupted process may leave a copy in the app's private temporary storage until it is cleared. Working files for password-protected backups are encrypted. Creating or selecting an unencrypted backup creates an unencrypted temporary copy.

Local trip and route records remain until you delete them or remove the app. You can delete an individual trip and its saved route from Trip Detail or by pressing and holding the trip in Trips, then confirming deletion. In Settings, Delete Trip Data can remove all trips or trips in a selected date range, together with their stored route points. The option labelled All data means all trip and route records; it does not remove prior export files, subscription or quota settings, or copies already shared. If you enable automatic cleanup, MileSprout deletes trip records older than two years when the app starts.

To remove the app's remaining local storage, use Android's Clear storage control or uninstall MileSprout. You may need to delete exports or copies saved elsewhere separately. MileSprout requests that Android not back up its app data, but device transfers, backups outside the app, or a service you chose for sharing may retain copies. Contact MileSprout@mail.com if you have a privacy or deletion question. Shared destinations, Google Play, and OpenStreetMap handle their own service records under their respective policies.

## Security and other services

MileSprout keeps its app data in Android's private app storage. Its optional map requests use HTTPS, and Google Play handles billing communications. Exports and shared copies may receive different protection depending on where you save or send them. MileSprout does not use trip or route records for advertising.

MileSprout is intended for people recording driving mileage and is not directed to children. We do not knowingly seek information from children through the app.

## Changes to this policy

We may update this policy as MileSprout's features or data handling change. The updated text and date will appear in the app. Contact MileSprout@mail.com with questions about this policy.
