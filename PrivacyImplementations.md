# Privacy Protection Methods for GPS Data

## General
* Have a single point of data storage
  => Delete raw uploaded files after 1 day or week
* Access control to DB

## Anonymization and Pseudonymization
* Just do not ask for username
* Randomize/delete trip to user matching

## Randomization and Obfuscation
* Add gaussian noise
* Report area IDs instead of GPS positions
* k-Anonymity: Report the location of the k-1 nearest other users.
* Mixing Zones. Assign new ids, when in a region with many users.
* Hashing of textual data: tags

 
# Risks / Attacks
* Infer Home Location -> Address, Name
* Even mixing different users GPS data withough ID often gives restorable data
* GPS tracks can be restored from e.g. velocity information

# Literature
* Krum - A survey on computational location privacy
* Westin - Privacy and Freedom
* Duckham et. al. -  A spatiotemporal model for Location Privacy Protection
